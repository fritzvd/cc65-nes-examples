Note: These examples are from [Shiru's NES programming tutorial](http://shiru.untergrund.net/articles/programming_nes_games_in_c.htm); I merely changed @jmk's Makefile so I could mess around on Linux. The original readme follows.

Original examples to be downloaded here: https://shiru.untergrund.net/files/src/cc65_nes_examples.zip

If you want to play with this. The easiest way to set up cc65 on your local debian-like is through these repo's:
http://spiro.trikaliotis.net/debian

For extra credit try this recompiler: https://github.com/andrewrk/jamulator. It can recompile .nes roms as a native app.

---

This is a set of very simple examples of programming NES software in C using CC65 compiler and my low level code library. To get more information you can check out my article on this topic: http://shiru.untergrund.net/articles/programming_nes_games_in_c.htm

How to compile: download CC65 from http://cc65.org/, unpack into a directory, unpack this folder into that directory (where /bin/ etc is located), run compile_all.bat


Examples

1. outputs some text
2. moving balls using sprites
3. pad polling and nametable updating when rendering is enabled
4. metasprites, two pads polling, collision detection
5. unpacking a RLE-packed nametable created with NES Screen Tool into the VRAM

mailto:shiru@mail.ru  
http://shiru.untergrund.net
