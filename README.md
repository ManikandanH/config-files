## NeoVim config file 

Make the below folder in your home.

```cd ~/.config && mkdir nvim && touch init.vim```

* copy and paste this config file into the above init.vim file.
* Install the mentioned plugins using :PlugInstall(which will install all the plugins)
* since the abve config file used coc config(which is a autocompleter for all languages), do the below in order for this plugin to work

```cd ~/.config/nvim/plugged/coc.nvim && yarn install && yarn build```
