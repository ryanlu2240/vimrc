# vimrc
```
set nu
set ai
set cursorline
set tabstop=4
set shiftwidth=4
set mouse=a

inoremap ( ()<Esc>i
inoremap " ""<Esc>i
inoremap ' ''<Esc>i
inoremap [ []<Esc>i
inoremap {<CR> {<CR>}<Esc>ko

set expandtab

filetype indent on

hi LineNr cterm=bold ctermfg=DarkGrey ctermbg=NONE
hi CursorLineNr cterm=bold ctermfg=Green ctermbg=NONE

syntax enable
```
