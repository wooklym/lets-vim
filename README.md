# lets-vim

## .vimrc

```
execute pathogen#infect()
syntax on
filetype plugin indent on

" crtlp
set runtimepath^=~/.vim/bundle/ctrlp.vim

set nu
set ruler
set tabstop=4
set shiftwidth=4
set expandtab
set backspace=eol,start,indent
set showmatch
set foldmethod=marker
set list
set listchars=tab:>-,trail:~,extends:>,precedes:<

let g:indentLine_char = '︙'

colorscheme luna
```
