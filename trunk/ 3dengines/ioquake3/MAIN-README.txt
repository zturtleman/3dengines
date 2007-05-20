Source Code Notes:
-------------------------------------------------------
Currently, basic changes are taking place to get ioquake where
I need it in order to be able to move over the changes that I
had previously done to the Evolution engine.

When building the source code. Make sure to build in Release!

The ioquake3.exe and dll's will be copied to /ioquake3/engine/release with
all of the additional compiled libraries and such in /release/output to make
this easier.


Current Changelog:
-----------------------------------------------

1. Mac + Linux support is almost gone. I need MSVC and support for windows only.

2. Checksum checks removed. Need to load any or all pak files



Current TODO List:
-----------------------------------------------

1. Remove vm support. I will be using .dll's.. Horde3D and other libraries will not work in a vm.

2. Incorporate snow, fog, rain, vehicle support and horde 3d from test version.