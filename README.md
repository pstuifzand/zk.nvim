# zk.nvim

A lightweight neovim (lua-based) wrapper around [`zk`](https://github.com/mickael-menu/zk).

The primary goals of this plugin are to provide handy maps, commands, and
user-interface elements around the fantastic golang library,
[`zk`](https://github.com/mickael-menu/zk).


## Install

#### paq-nvim

`paq { "megalithic/zk.nvim" }`

#### packer.nvim

`use { "megalithic/zk.nvim" }`

#### vim-plug

`Plug "megalithic/zk.nvim"`


## Configuration


```lua
require("zk").init({})
```

#### Default config

```lua
{
  debug = false,
  root_target = ".zk",
  default_notebook_path = ""
}
```


## Usage


#### Install `zk`

Install the `zk` binary (as long as `go` is installed in your system's `PATH`).

```viml
:ZkInstall
```


#### Create a new note

Create a new `zk` note, with an optional title string.

```viml
:ZkNew Optional Title
```

### Credit

- Mickael Menu (https://github.com/mickael-menu/zk)
- Evan Travers (http://evantravers.com/articles/tags/zettelkasten/)
