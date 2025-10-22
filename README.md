# The Problem:

Example with __"lockpickingmenu.swf"__
 
  When opening interface (.swf) files with [JPEXS](https://github.com/jindrapetrik/jpexs-decompiler)
it prompts you to load missing __"gfxfontlib.swf"__ file,
all tutorials say you to ingore that, but that will make it harder to modify visuals,
because <ins>you wont see text</ins>.
 
You can put that file (gfxfontlib.swf) next to interface you are editing to display some fonts, 
but the issue is that main font that the game uses is missing ($EverywhereMediumFont)
and <ins>you are just going to see some text, not all</ins>.
 
# Solution:

Place this fixed - gfxfontlib.swf
next to your edited interface file:

<img width="300" src="https://github.com/user-attachments/assets/3bbc2e4f-cc96-4ee8-9a92-812a6912d6b6" />
 
 
When opening swf file say yes, that you want to load gfxfontlib.swf:

<img width="300" src="https://github.com/user-attachments/assets/368935b5-8ece-471c-8e1c-57be4d5a5a4a" />
 
 
Now it should display all text correctly, like this:

<img width="300" src="https://github.com/user-attachments/assets/cef35838-074f-4cd7-8539-fea37f342433" />
 
 
This is without fix:

<img width="300" src="https://github.com/user-attachments/assets/aec443b3-867b-4f3f-bff5-601fffdd75ef" />

> [!WARNING]
> You dont need to include __"gfxfontlib.swf"__ in your interface mods!
> Game uses its own fonts.

