HOWTOINSTALL:

1. Clone the repository.
2. Open quake2.sln in Visual Studio.
3. Set game as startup solution.
4. Change debug to Release and make sure you have Win32.
5. Build the game.
6. Open quake2-full/game/release and find gamex86.dll file.
7. Open your local folder for your instalation of Quake 2.
8. Create a new folder (name does not matter).
9. Move gamex86.dll from the modded quake 2 game to the new folder.
10. Run Quake 2 original.
11. Open console using '~' key.
12. Type "set game <name of new folder>" and press enter.

Last step should run the modded version of Quake 2.

==============================================================================================================

This is the complete source code for Quake 2, version 3.19, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software


