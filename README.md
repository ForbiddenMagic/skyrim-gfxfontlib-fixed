Example with __"lockpickingmenu.swf"__

  When opening interface (.swf) files with [JPEXS](https://github.com/jindrapetrik/jpexs-decompiler)
it prompts you to load missing __"gfxfontlib.swf"__ file,
all tutorials say you to ingore that, but that will make it harder to modify visuals,
because you wont see text.

You can put that file next to ui you are editing to display some fonts, 
but the main issue that main font that the game uses is missing ($EverywhereMediumFont)
and you are just going to see some text, not all.



# __Solution:__
Place this fixed - gfxfontlib.swf
next to your edited interface file

and it should display all text correctly, like this:
