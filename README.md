# 🌍 me dotfiles

all the dotfiles for my minimal terminal-and-vim-based Artix Linux environment

```txt
baul@art
----------------- 
OS: Artix Linux (OpenRC)
Host: Dell XPS 15 9560
Kernel: 5.14.12
Shell: zsh 5.8
WM: dwm 6.2
Terminal: st 0.8.4
```

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- zathura (pdf viewer)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/baulml/dwm) (window manager)
- [dwmblocks](https://github.com/baulml/dwmblocks) (statusbar)
- [dmenu](https://github.com/baulml/dmenu) (dynamic menu)
- [st](https://github.com/baulml/st) (terminal emulator)

## Install these dotfiles and all dependencies

Use Luke Smith's [LARBS](https://larbs.xyz) to autoinstall everything:

```
curl -LO larbs.xyz/larbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/LukeSmithxyz/LARBS/blob/master/progs.csv).
