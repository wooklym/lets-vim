# lets-vim

## .vimrc

```
execute pathogen#infect()
syntax on
filetype plugin indent on

" crtlp
set runtimepath^=~/.vim/bundle/ctrlp.vim

" emmet
let g:user_emmet_leader_key='<C-Z>'


"if has("unix")
"set encoding=euc-kr
"elseif has("win32")
"set encoding=cp949
"endif

"if v:lang =~ "^ko"
"set encoding=cp949
"set fileencodings=utf-8,cp949
"endif

"if v:lang =~ "utf8$" || v:lang =~ "UTF-8$"
"set encoding=utf-8
"set fileencodings=utf-8,cp949
"endif

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
