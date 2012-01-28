#Collection of useful shortcuts for vim

##Modes

* `i` insert mode
* `a` append from marker
* `A` append from end of line
* `C-[` - exit mode

##Editing

* `o` - new line and insert
* `O` - new line and insert above
* `yy` - yank line
* `p` - paste after cursor
* `P` - paste before cursor
* `:r !pbpaste` - paste from osx clipboard
* `u` - undo
* `C-r` - redo
* `:%s/foo/bar/g` - Find/replace
* `:'<,'>s/red/green/g` - Find/replace in a selection.  Start with `v`, select text, `:` for a command

##Buffers/Windows

* `C-w =` - balance windows

##GREP

* `:grep` or `:vimgrep`
* `:cw` or `:copen`
* `:lgrep` `:lvimgrep`
* `:lw` or `:lopen`
* Sample: `:vimgrep /user/ ./**/*.rb` && `:copen`

##Magic and Unicorns

###Macros

* `:<up>` - command history with tab completion
* `q a` - begin recording macro into buffer a
* `q` - end recording macro
* `1@a` - repeat macro once
* `400@a` - repeat macro 400 times

###Autoindent
1. `:set filetype=xml`
2. `:filetype indent on`
3. `gg=G`