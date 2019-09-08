# install extensions
tool -> extensions and updates


# extensions

## github
support:
- easily open a remote repository on github from inside visual studio
- handy `git clone` from ==team resource manager -> github==

## VsVim
**VsVim** is an **awesome** extension.
It provides excellent vim emulation for visual studio.
### features
- excellent support for vim ==normal mode==
supported commands:
-- gt
-- zz
-- H, M, L
-- {/}
- excellent support for vim ==ex mode==
supported commands:
-- substitute
-- split
-- vsplit
-- write
-- quit
-- delete
-- yank
-- put
-- print
-- echo
### configuration
configuration is via visual studio preferences(**ctrl-,**) 
ctrl-, -> VsVim -> keyboard
#### resolving conflict
configuration is actually resolving keyboard conflict in VsVim
#### keys which needs to be configured to be handled by VsVim instead of visual studio
> the configuration works both in ==normal mode== and ==insert mode==
+ Ctrl-[(insert)
+ Ctrl-e(insert, normal)
+ Ctrl-y(insert, normal)
+ Ctrl-n(insert, ex, normal)
+ Ctrl-p(insert, ex, normal)
+ Ctrl-j(insert)
+ Ctrl-r(insert)