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

- [mattn/emmet-vim]
- [scrooloose/snipmate-snippets]
- [plasticboy/vim-markdown]
- [tpope/vim-rails]
- [scrooloose/nerdtree]
- [msanders/snipmate.vim]
- [tpope/vim-pathogen]
- [vim-ruby/vim-ruby]
- [vim-scripts/taglist.vim]
- [panozzaj/vim-autocorrect]
- [sickill/vim-monokai]
- [ctrlpvim/ctrlp.vim]
- [terryma/vim-expand-region]
- [tpope/vim-surround]
- [mileszs/ack.vim]

snipmate-snippets replaced original snippets in snipate. Used `rake` to install.


[mattn/emmet-vim]: https://github.com/mattn/emmet-vim
[scrooloose/snipmate-snippets]: https://github.com/scrooloose/snipmate-snippets
[plasticboy/vim-markdown]: https://github.com/plasticboy/vim-markdown
[tpope/vim-rails]: https://github.com/tpope/vim-rails
[scrooloose/nerdtree]: https://github.com/scrooloose/nerdtree
[msanders/snipmate.vim]: https://github.com/msanders/snipmate.vim
[tpope/vim-pathogen]: https://github.com/tpope/vim-pathogen
[vim-ruby/vim-ruby]: https://github.com/vim-ruby/vim-ruby
[vim-scripts/taglist.vim]: https://github.com/vim-scripts/taglist.vim
[panozzaj/vim-autocorrect]: https://github.com/panozzaj/vim-autocorrect
[Lokaltog/powerline-fonts]: https://github.com/Lokaltog/powerline-fonts
[sickill/vim-monokai]: https://github.com/sickill/vim-monokai
[ctrlpvim/ctrlp.vim]: https://github.com/ctrlpvim/ctrlp.vim
[terryma/vim-expand-region]: https://github.com/terryma/vim-expand-region
[tpope/vim-surround]: https://github.com/tpope/vim-surround
[mileszs/ack.vim]: https://github.com/mileszs/ack.vim
