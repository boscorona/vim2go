Vim Starter Kit
===========

Get started using Vim, with all the features from your suboptimal text editor. 👨🏽‍💻

## Installation

Run this command in your bash or prefered shell.

```bash

echo "runtime vimrc" > ~/.vimrc && mkdir ~/.vim && cd ~/.vim && git clone https://github.com/nbosco/vim_starter_kit.git . && git clone https://github.com/kristijanhusak/vim-hybrid-material ~/.vim/bundle/vim-hybrid-material && mkdir colors && cp -R bundle/vim-hybrid-material/colors/./ ./colors/./ && git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim && vim +PluginInstall 

```

## Shortcuts

* `\y`: Copy to system clipboard
* `\d`: Cut to system clipboard
* `\p`: Paste below, from system clipboard
* `\>P`: Paste above, from system clipboard
* `\n`: New empty tab.
* `<Space>x`: Remove search highlight.
* `\]`: Open/Close NERDTree
* `\[` : Navigate between split views
* `<Tab>`: Buffer list (Normal Mode)
* `C-p`: Fuzzy finder
* ``\` ``: Swap the positions of the open splits
* `<Space>w`: Next sub-word in a camel cased word
* `<Space>b`: Previous sub-word in a camel cased word
* `<Space>e`: End of sub-word in a camel cased word


## Screenies

![Screenshot 1](http://i.imgur.com/gFeS2Y7.png)

![Screenshot 2](http://i.imgur.com/tqYhx1C.png)
