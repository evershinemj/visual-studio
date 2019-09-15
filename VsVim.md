**VsVim** is an **awesome** extension.
It provides excellent vim emulation for visual studio.

# features
## excellent support for vim ==normal mode==
supported commands:
- zf, zo, zc, zd
- gt, gT
- zz
- H, M, L
- {/}
- m
- `
- '
- ga
- ge
- gv
- ~, g~
- gU, gu
- /, ?
- *, #
- <<, >>
- </> + motion
- !
- gq
## excellent support for vim ==ex mode==
supported commands:
- substitute
- split
- vsplit
- help(opens VsVim github wiki page)
- vimhelp(vs-specific command; open vim official online help)
- fold(used in visual mode)
- write
- quit
- ls/buffers
- read
- shell
- cd
- pwd
- delete
- yank
- put
- print
- echo
- qa
- x
- !dir
## supports ==.vimrc==
## visual support for marks
this is a **fantastic feature**!

# configuration
configuration is via visual studio preferences(**ctrl-,**) 
---
ctrl-, -> VsVim -> keyboard
## resolving conflict
configuration is actually resolving keyboard conflict in VsVim
## keys which needs to be configured to be handled by VsVim instead of visual studio
> the configuration works both in ==normal mode== and ==insert mode==
+ Ctrl-[(insert)
+ Ctrl-e(insert, normal)
+ Ctrl-y(insert, normal)
+ Ctrl-n(insert, ex, normal)
+ Ctrl-p(insert, ex, normal)
+ Ctrl-j(insert)
+ Ctrl-r(insert, normal)
+ Ctrl-v(normal)

# the command-line window
note that the output window might block the command-line window, making ex commands
hidden. in this case, just close the output window to make command-line window visible
again
