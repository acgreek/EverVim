# EverVim: The Ultimate Vim Distribution
![EverVim](https://img.shields.io/badge/Coded%20with-EverVim-bd93f9.svg?style=flat-square)

![evervim-header](http://i.imgur.com/yUVLKmB.png "EverVim with VimR on macOS")

* * *

## | [About](https://github.com/LER0ever/EverVim/blob/master/README.md#about) | [Installation](https://github.com/LER0ever/EverVim/blob/master/README.md#installation) | [Features](https://github.com/LER0ever/EverVim/blob/master/README.md#features) | [ScreenShots](https://github.com/LER0ever/EverVim/blob/master/README.md#screenshots) | [Documentation](https://github.com/LER0ever/EverVim/blob/master/DOC.md) | [License](https://github.com/LER0ever/EverVim/blob/master/README.md#license) |

## About
EverVim is the ultimate vim distribution that supports **NeoVim**, Vim, GVim and MacVim. It ships with tons of powerful features through vim plugins, which makes it easy to get started for both newcomers and experienced users.

The distribution is completely customizable using a ~/.EverVim.vimrc Vim config files.

EverVim started as a fork of spf13-vim, which is great but not actively maintained any more. Unlike spf13-vim, EverVim always keeps its modern features up-to-date. It uses [Vim-Plug](https://github.com/junegunn/vim-plug) as a plugin manager, which is async and is about 10x faster than Vundle. Keeping your plugins always up to date is just a command away. Vim-Plug uses a plugin bundle so that having lots of them won't mess up the folder structure.

The default config of EverVim is powerful and easy to use just out of the box, and is suitable for most vim users. Customization is easy as well. With `.local` files, you can customize the whole collection without modify the original files. That means you're still able to update the EverVim config using `git pull` without compromizing your own modification.

## Installation
#### Detailed installation instruction
##### | [Linux](https://github.com/LER0ever/EverVim/wiki/Installation-on-Linux) | [macOS](https://github.com/LER0ever/EverVim/wiki/Installation-on-macOS) | [Windows](https://github.com/LER0ever/EverVim/wiki/Installation-on-Windows) |
Finished the installation above?  
Before you started, please read the [Plugins Documentation](https://github.com/LER0ever/EverVim/wiki/Plugins) to have an overview about some of EverVim's essential plugins.

* * *

##### tl;dr. A brief how-to
<details>
<summary>0. Still</summary>
**You are strongly encouraged to use the full instruction on your first installation of EverVim.**
</details>
<details>
<summary>1. Install prerequisites and patched font</summary>
- Download and install the [Knack Nerd Font](https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/Hack/Regular/complete/Knack%20Regular%20Nerd%20Font%20Complete%20Mono.ttf)
- Make **git, curl** is on your system.
</details>
<details>
<summary>2. Clone and Boot</summary>
- `git clone https://github.com/LER0ever/EverVim ~/.EverVim`
- `cd .EverVim`
- `sh Boot-EverVim.sh` or `.\Boot-EverVim.ps1`
</details>
<details>
<summary>3. Install the plugins</summary>
- Fire up your vim
- Type `:PlugInstall`
- Wait for it to finish
- Restart Vim.
</details>

#### Before you get started !


# Features
### Cross Platform
- Support Vim 7.4.x, Vim 8, MacVim and of course Neovim
- Portable under windows
- Tested under all platforms
	- Windows (gvim, vim)
	- Linux (neovim, neovim-qt, vim, gvim)
	- macOS (MacVim, neovim)
	- BSD (vim)
	- Android (neovim, vim under Termux)

### Powerful & Easy to use
- Easy to setup, just one bash away.
- All the wonderful features are enabled out of the box
- Full IDE-like support for C/C++, Go, Rust, javascript, etc.
- Use YouCompleteMe by default, neocomplete as a windows fallback
- NERDTree as file explorer
- Git operation right inside vim with fugitive
- Syntastic provides syntax check on every save
- Jump to anywhere in 2 key with EasyMotion
- Markdown CTags support via markdown2ctags

### Pleasant to code
- Fancy Dracula Theme
- Lightline for statusline and tabline
- TagBar for code navigation
- Startup screen to pick up recent files (using Startify)

### Asynchronous
- Use Vim-Plug as vim plugin manager
	- Parallel installation
	- 10x faster initial PlugInstall

### Other Awesomeness
- Collaboration using CoVim

## ScreenShots
##### Startup Screen (under NeoVim-Qt)
![evervimstartify](http://i.imgur.com/SHu2yZv.png)
##### NeoVim Terminal
![evervimterm](http://i.imgur.com/lQVWBTH.png)
##### NeoVim GTK
![evervimnvimgtk](http://i.imgur.com/Kp2q00a.png)
##### GVim
![evervimgui](http://i.imgur.com/s8ga2Cv.png)
##### Older Shots
![evervimold](http://i.imgur.com/l8oK1Mj.png)

## [Documentation](https://github.com/LER0ever/EverVim/blob/master/DOC.md)

## License
EverVim is licensed under **Apache 2.0**

This repo contains part of code from [spf13-vim](https://github.com/spf13/spf13-vim), 
which is also licensed under [Apache 2.0](https://github.com/spf13/spf13-vim/blob/3.0/LICENSE.txt)
