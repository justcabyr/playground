# vim-mode

h,j,k,l for basic movement.
w,b for word hopping. Effectively the same as Option/Ctrl + arrow keys
yy to "copy" a line, called Yank
dd to delete, and yank, a line
p and P to paste the contents of the implicit register below / above
Most of the ways to go into insert mode!
i and a for which side of the cursor
I and A for which side of the line
o and O for belowe / above line
zz - centre screen

gg | G - go to the top or buttom


:set scrolloff=8
:set number
:set relativenumber | :set rnu
:set norelativenumber

set tabstop=4 softtabstop=4
set shiftwidth=4
set expandtab
set smartindent

dd6j | V6jd |  
ctrl n | ctrl p - command scrolling