# Vim Configuration

Install configuration:
- clone this repository into ~/.vim folder: `git clone git@github.com:SimonLab/vimconfig.git ~/.vim`
- create alias to the .vimrc config file to allow vim to find the configuration in ~/.vimrc file: `ln -s ~/.vim/vimr ~/.vimrc`
- `cd ~/.vim` to install the plugins contained in `pack/plugins/start` use the git submodule commands to initialise and fetch the plugin from the repository of the plugin's authors:
  - `git submodule init`
  - `git submodule update`


see:

- http://vimcasts.org/episodes/packages/
- http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/
