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

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Cool! Create a single-commit PR.

## Versioning

We'll do it live!

## Authors

* **Kevin Ashcraft** - *Repo + Symlinks*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Vim-Awesome](https://vimawesome.com)
* [Tim Pope](https://github.com/tpope) (for pathogen and being cool)
* [Franco Lazzarino](https://github.com/flazz) (for introducing the idea of submodule and version-controlling .vim)

