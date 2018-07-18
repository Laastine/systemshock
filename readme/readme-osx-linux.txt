Shockolate - Same great System Shock, new great taste!
https://github.com/Interrupt/systemshock

Based on the source code for PowerPC released by Night Dive Studios, Incorporated.

This is a cross platform source port of the System Shock source code that was released,
using SDL2. This runs well on OSX and Linux right now, with some runtime issues to sort out.

The end goal for this project is something like what Chocolate Doom is for Doom: an
experience that closely mimics the original, but portable and with some quality of life
improvements - and mod support!

# Setup!

1. Copy res folder of original systemshock to this directory
2. Shockolate depends on 32bit SDL2. Install 32-bit SDL2 and SDL2_mixer by running `./install_32bit_sdl.sh`.
Linux needs sudo for this script. Script compiles and installs both libraries under `/usr/local/`, so make sure you know what you are doing.
3. Run shockolate `./systemshock`

There is basic midi music support if there are exported .mid files in /res/music/ like 'thm0.mid'.
Try this example music pack made of Chicajo MIDIs: https://drive.google.com/open?id=18KhiHpmPHGuTedMCPifnox2DWLd2GnCW

# Mod support!
You can point the game at Fan Mission folders or files via the command line:
systemshock.exe /Path/To/My/Mission