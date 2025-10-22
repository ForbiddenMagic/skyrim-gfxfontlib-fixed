Example with __"lockpickingmenu.swf"__

  When opening interface (.swf) files with [JPEXS](https://github.com/jindrapetrik/jpexs-decompiler)
it prompts you to load missing __"gfxfontlib.swf"__ file,
all tutorials say you to ingore that, but that will make it harder to modify visuals,
because you wont see text.

You can put that file next to ui you are editing to display some fonts, 
but the main issue that main font that the game uses is missing ($EverywhereMediumFont)
and you are just going to see some text, not all.

<img width="161" height="49" alt="files-together" src="https://github.com/user-attachments/assets/3bbc2e4f-cc96-4ee8-9a92-812a6912d6b6" />

# __Solution:__
Place this fixed - gfxfontlib.swf
next to your edited interface file

and it should display all text correctly, like this:
<img width="1274" height="715" alt="fixed-font" src="https://github.com/user-attachments/assets/b050853c-5612-4678-8e03-a8d6d766f4e4" />

whithout fix:
<img width="1274" height="717" alt="without-fix" src="https://github.com/user-attachments/assets/aec443b3-867b-4f3f-bff5-601fffdd75ef" />
