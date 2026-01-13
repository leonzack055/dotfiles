**Documentation: https://daler.github.io/dotfiles/**

This repo captures hard-won settings and tool installations that I have
accumulated over time. Using the included modular setup script, starting from
a fresh installation of Ubuntu Linux or MacOS I can have everything I'm used to
-- programs and all -- in a few minutes.

It doubles as a "batteries included" set of configuration files that can be used
by others just starting out. It includes:

- bash config
- tmux config
- vim/neovim config
- various tool installation commands

If you don't want "batteries included", you can select only what is most useful
to you because:

- the `setup.sh` script is modular
- the [documentation]( https://daler.github.io/dotfiles/) explains everything
- the config files themselves are documented

**For more, see full documentation at https://daler.github.io/dotfiles/**

## Quickstart
1)  ./setup.sh --apt-install
2)  ./setup.sh --dotfiles
3)  ./setup.sh --install-conda
4)  ./setup.sh --set-up-bioconda
5)  ./setup.sh --install-fzf
6)  ./setup.sh --install-ripgrep
7)  ./setup.sh --install-zoxide
8) ./setup.sh --install-pyp
9) ./setup.sh --install-fd
`可选项，安装alacritty和tmux和cargo环境，可以使用RUST但你需要先安装显卡驱动`
10) ./setup.sh --install-alacritty
11) ./setup.sh --install-tmux
12) ./setup.sh --fix-tmux-terminfo
