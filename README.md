# dot-vimrc

## Installing

Plugins
1. Install Pathogen [https://github.com/tpope/vim-pathogen](https://github.com/tpope/vim-pathogen)
1. 
1. Instll CtrlP `git clone https://github.com/kien/ctrlp.vim.git ~/.vim/bundle/ctrlp`

Download .vimrc
1. clone into `~/dot-vimrc`
1. make sure old .vimrc does not exist/ move it  to backup location
1. create symlink `ln -s ~/dot-vimrc/.vimrc ~/.vimrc`
1. create symlink for bundles `ln -s ~/dot-vimrc/ ~/.vim/`
1. cd into `~/.vim/` and install submodules `git  submodule update --init --recursive`

## Adding or updating list of pathogen plugins

1. `cd ~/dot-vimrc/bundle` Note: you want to be in the bundle directory
1. `git submodule add [giturl]`
1. commit changes to git

## Upgrading all plugins
`git submodule foreach git pull origin master`

## Resources

* Guide to using  submodules to manage pathogen plugins [http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)
