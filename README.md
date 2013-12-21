# My Vim Configurations

## Before

### Install git (ubuntu)

    sudo apt-get install git-core

### Install git-subtree for install vim plugins

	mkdir $HOME/git; cd $HOME/git
	git clone git://github.com/apenwarr/git-subtree.git
	sudo bash git-subtree/install.sh

### Install PowerLine symbols

visit [powerline-fonts][powerline-fonts]

## Usage

    cd $HOME
    git clone https://github.com/fadying/my-vim.git .vim
    ln -s .vim/.vimrc .vimrc

### Some plugins to use

- `call AutoCorrect()` to use autocorrect
- `NERDTree` to use nerdtree
- `TlistOpen` to use taglist

### To install or update vim plugins from github

    cd $HOME/.vim
    bash github-plugin-install.sh tpope/vim-pathogen

## Installed plugins for vim

- [mattn/emmet-vim] [emmet-vim]
- [scrooloose/snipmate-snippets] [snipmate-snippets]
- [plasticboy/vim-markdown] [vim-markdown]
- [tpope/vim-rails] [vim-rails]
- [scooloose/nerdtree] [nerdtree]
- [msanders/snipmate.vim] [snipmate.vim]
- [tpope/vim-pathogen] [vim-pathogen]
- [vim-ruby/vim-ruby] [vim-ruby]
- [vim-scripts/taglist.vim] [taglist.vim]
- [panozzaj/vim-autocorrect] [vim-autocorrect]

snipmate-snippets replaced original snippets in snipate. Used `rake` to install.


[emmet-vim]: https://github.com/mattn/emmet-vim
[snipmate-snippets]: https://github.com/scrooloose/snipmate-snippets
[vim-markdown]: https://github.com/plasticboy/vim-markdown
[vim-rails]: https://github.com/tpope/vim-rails
[nerdtree]: https://github.com/scrooloose/nerdtree
[snipmate.vim]: https://github.com/msanders/snipmate.vim
[vim-pathogen]: https://github.com/tpope/vim-pathogen
[vim-ruby]: https://github.com/vim-ruby/vim-ruby
[taglist.vim]: https://github.com/vim-scripts/taglist.vim
[vim-autocorrect]: https://github.com/panozzaj/vim-autocorrect
[powerline-fonts]: https://github.com/Lokaltog/powerline-fonts
