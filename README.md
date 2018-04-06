# Dotfiles

## vimrc

1. Clone the repo
1. Delete or move your current .vimrc
1. Create a symlink in your home directory `ln -s ~/link/to/vimrc .vimrc`
1. Open the .vimrc with vim and run `:PluginInstall` to install all the plugins. You may also need to clear previously installed plugins with `:PluginClean`
1. There are two color schemes included. Solarized seems to work out of the box while One requires some jiggering. See the [Vim-One Repo](https://github.com/rakr/vim-one) for info. Feel free to add more!
