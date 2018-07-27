
Blitz3D open source release.

To build Blitz3D you will need:

* Visual Studio Community 2017. Install "Desktop development with C++" plus "MFC and ATL support" plus "ASP.NET and web development".

Too lazt to build? Grab the prebuilt versions:
    V1.109 from https://github.com/davecamp/blitz3d_msvc2017/releases/tag/v1.109
    V1.108 from https://blitzresearch.itch.io/

Steps to build:

1) Open blitz3d.dsw in virtual studio 2017.

2) Select release config and rebuild the entire solution.

3) All done! You can find output files in the _release and _release/bin dirs. Feel free to delete .pdb and .ilk files here.

4) Note: This version of blitzplus uses the dynamic version of the fmod audio lib. When redistributing programs built with blitzplus_msvc2017, you will need to also include the fmod.dll file found in the _runtime/bin directory with your programs. This should be placed in the same directory as your program's executable.

5) You can also try building the debug version, although this hasn't been well tested.

Blitz3d is released under the zlib/libpng license.

The zlib/libpng License

Copyright (c) 2013 Blitz Research Ltd

This software is provided 'as-is', without any express or implied warranty. In no event will the authors be held liable for any damages arising from the use of this software.

Permission is granted to anyone to use this software for any purpose, including commercial applications, and to alter it and redistribute it freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.

2. Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.

3. This notice may not be removed or altered from any source distribution.
