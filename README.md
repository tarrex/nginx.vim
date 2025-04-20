# nginx.vim

Vim config for nginx config file. Details in <https://github.com/nginx/nginx/tree/master/contrib/vim>.

### Install

+ Vim-Plug
  ```vimscript
  Plug 'tarrex/nginx.vim', {'for': 'nginx'}
  ```
  Then run the command `:PlugInstall` in Vim. See the [vim-plug](https://github.com/junegunn/vim-plug) for more detail.
+ Vundle
  ```vimscript
  Plugin 'tarrex/nginx.vim'
  ```
  Then run the command `:PluginInstall` in Vim. See the [Vundle](https://github.com/VundleVim/Vundle.vim) for more detail.
+ Pathogen
  ```shell
  cd ~/.vim/bundle
  git clone https://github.com/tarrex/nginx.vim
  ```
  See the [Pathogen](https://github.com/tpope/vim-pathogen) for more detail.

+ lazy.nvim
  ```lua
  {
    'tarrex/nginx.vim',
    ft = 'nginx'
  }
  ```
  See the [lazy.nvim](https://lazy.folke.io/spec/examples) for more detail.
