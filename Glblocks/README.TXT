                    GLBlocks (C) 1999 Andreas Gustafsson

[Introduction]-----------------------------------------------------------------

GLBlocks is a simple puzzle/tetris-style game, where the object is to make the
blocks disappear by placing the blocks so that four or more of the same color
is next to eachother.


[Installation notes]-----------------------------------------------------------

Just unzip the game to a directory of your choice, then run GLBLocks.exe.


[Playing the game]-------------------------------------------------------------

Start the game by running GLBlocks.exe. Choose your resolution and if you want
sound or not. Two different gametypes are available, swinging and static
playfield. With swinging playfield you get yet another dimension of difficulty,
the longer you play, the more the playfield will swing and rotate, making it
harder to see where to place those pieces!
Once the game starts you control the falling pieces of 2 by 2 blocks with the
arrow keys.
Left-arrow to move it left, right-arrow to move it right, up-arrow rotates
the piece, and down-arrow makes it fall faster.
Try placing the pieces so that blocks of the same color end up next to
eachother. Once 4 or more of the same color are next to eachother, they will
disappear, and blocks that are 'hanging in the air' will fall down.
If a 'chain-reaction' is created, more points will be scored.


[System requirements]----------------------------------------------------------

GLBlocks uses OpenGL to draw all graphics, so you will need a rather fast
system to play it, especially if you don't have a 3D accelerator with FULL
OpenGL support. When the playfield starts to get filled, there can be more than
1000 polygons on screen, all rendered with realtime lighting.
Software OpenGL is included in the later versions of Windows 95 and Windows 98.
When you play using the software OpenGL renderer, you might want to try the
lowest resolution (512x384) for best performance. If your system is really
slow, you might want to stick with the 'static playfield' option, since the
low framerate will be less apparent in this game mode.
If you have a 3dfx card and want to use it, you will have to download the
unsupported beta OpenGL drivers from 3dfx's site. The MiniGL is NOT sufficient
to play GLBlocks, since GLBlocks uses the lighting functions in OpenGL.
Download 3dfx OpenGL beta drivers: http://www.3dfx.com/view_io.asp?ID=26
Once installed, copy the 3dfxOpenGL.dll file to your GLBlocks directory and
rename it to OpenGL32.dll.

Minimum system:
Pentium 166
Windows 95/98 with OpenGL drivers installed.

Recommended system:
Pentium 200MMX or faster.
Windows 95/98
3D accelerator with FULL OpenGL driver.


[News/Changes]-----------------------------------------------------------------

1.2 : Wrote a completely new frontend in Visual C++ to replace the old one
      (which was written in Visual Basic...).
      Added the possibility to use texturemapped blocks (but, since I'm no
      artist, the textures are really ugly!).
1.0 : Initial release.



[Credits]----------------------------------------------------------------------

All coding by Andreas Gustafsson. The game is written in Visual C++ 5.0.
The charset and sound effects were found on the net.
Thanks to Martin Rystrand for some coding tips.


[Contact info]-----------------------------------------------------------------

Later I will put up a homepage for this game where you can download the latest
version etc. This page will be found at :
http://www.lysator.liu.se/~sdw/glblocks/
You can also mail me at : sdw@lysator.liu.se


[Legal info]-------------------------------------------------------------------

This program is used at your own risk. The author takes no responsibility for
any damages caused by it.
You are free to distribute this game as long as no fee is charged and no files
are modified/added/removed.


-------------------------------------------------------------------------------
