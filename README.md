# My Vim Configurations

## Before

### Install git (ubuntu)

    sudo apt-get install git-core

### Install git-subtree for install vim plugins

	mkdir $HOME/git; cd $HOME/git
	git clone git://github.com/apenwarr/git-subtree.git
	sudo bash git-subtree/install.sh

## Usage

    cd $HOME
    git clone https://github.com/fadying/my-vim.git .vim
    ln -s .vim/.vimrc .vimrc

### To install or update vim plugins from github

    cd $HOME/.vim
    bash github-plugin-install.sh tpope/vim-pathogen

## Installed plugins for vim

- mattn/emmet-vim
- scrooloose/snipmate-snippets
- plasticboy/vim-markdown
- tpope/vim-rails
- scooloose/nerdtree
- msanders/snipmate.vim
- tpope/vim-pathogen
- vim-ruby/vim-ruby

snipmate-snippets will replace original snippets in snipate. Use rake to install.

Not known the use of this vim-markdown. There is a tpope/vim-markdown, too.


