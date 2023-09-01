This is a mirror of http://www.vim.org/scripts/script.php?script_id=1573

Since there didn't seem to be a SystemVerilog syntax file yet for Vim, I wrote this.
It's based on the existing Verilog mode from Vim 6.3.
All language keywords are defined, as are most builtin method/task/function names.

# How to use
1) download the file and copy it to : `~/.vim/syntax/verilog_systemverilog.vim`

2) find .gvimrc (or .vimrc) in you home directory and add the follwing script at the end 

```
au BufNewFile,BufRead *.v,*.sv,*.vh,*.svh so ~/.vim/syntax/verilog_systemverilog.vim
