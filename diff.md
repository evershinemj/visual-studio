> visual studio has excellent support for diff
# view
> there is an icon on the toolbar controlling the view

> the icon consists of two parts:
1. the left part: illustration
2. the second part: drop list button
> note that clicking the left part has no effect. it is for illustration only(no toggling effect as in some other icons)
- split diff
- unified diff
- left file only
- right file only

# line diff
- <u>line diff</u> is rendered with **red/green background**, as opposed to some other implementations which render foreground color

# chunk diff
- <u>chunk diff</u> is **minor diff** within a line diff, which might be one word or several words
- <u>chunk diff</u> is rendered with **red/green boxes**

# slash patch
a slash patch stands for a patch where some code is added in the other file, while no code exists in the current file

# three modes of rendering
- slash patch versus green(add) 
- red versus slash patch(delete)
- red versus green(modify)

# right bar chunks
**the size of the chunks** on the right bar indicate **the number of lines modified**

# viewport box
the box on the right bar shows the viewport in the whole buffer.
