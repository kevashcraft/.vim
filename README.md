# Kevin's .vim Directory

my .vim directory, with a .vimrc file to be symlinked, and submodules for TPope's vim-pathogen + some bundles. 

## Getting Started

To get started clone this repo into your .vim directory (see [Installation](#Installation)).

### Prerequisites

Make sure vim and git are installed.

```
sudo apt-get install vim git -y
sudo yum install vim git
sudo pacman -S vim git
```

### Installation
Clone this repo into ~/.vim and create a symlink for .vimrc.
```
git clone https://github.com/kevashcraft/.vim.git ~/.vim &&
  cd ~ && ln -s .vim/.vimrc
```

## Built With

* [vim-pathogen](https://github.com:tpope/vim-pathogen.git)
* [colorschemes](https://github.com/flazz/vim-colorschemes.git)
* [youcompleteme](https://github.com/valloric/youcompleteme)
* [syntastic](https://github.com:vim-syntastic/syntastic.git)
* [vim-vue](https://github.com:posva/vim-vue.git)

## Contributing

Cool! Create a single-commit PR.

## Versioning

We'll do it live!

## Authors

* **Kevin Ashcraft** - *Repo + Symlinks*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Vim Org](http://www.vim.org/)
* [Vim-Awesome](https://vimawesome.com) - AWESOME VIM PLUGINS from ACROSS THE UNIVERSE

* [Tim Pope](https://github.com/tpope) - Vim plugin artist 
* [Franco Lazzarino](https://github.com/flazz) - introduced the idea of submodule and version-controlling .vim

