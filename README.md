## Overview

Contains the Neovim configuration I use between my personal and work laptop,
excluding all work specific stuff. This is very early stage, so there is no
work related plug-ins and configurations at the time of writing. When they
are added, they will be in a folder tracked in `.gitignore`.

## Usage

<details><summary> Linux and Mac </summary>
 
```sh
git clone https://github.com/mehmetefeumit/config-nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

<details><summary> Windows </summary>

If you're using `cmd.exe`:

```
git clone https://github.com/mehmetefeumit/config-nvim.git "%localappdata%\nvim"
```

If you're using `powershell.exe`

```
git clone https://github.com/mehmetefeumit/config-nvim.git "${env:LOCALAPPDATA}\nvim"
```
