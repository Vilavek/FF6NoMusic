# Final Fantasy VI No Music IPS Patch

No Music IPS Patch for Final Fantasy III/VI for the SNES. This works by patching the header for each song in the ROM to point to the Silence track's data (or lack there of). Tested on Final Fantasy III (USA) ROM (CRC32 A27F1C7A), and Worlds Collide randomizer using said ROM.

I created this patch to be compatible with the Worlds Collide randomizer. I play it casually and use fast-forward a lot in emulators and got tired of hearing the music get garbled, so with this I can disable the music in-game and keep the sound effects while playing music externally. Felt kind of wrong silencing this wonderful OST <3

Special thanks to the following resource:
https://www.ff6hacking.com/wiki/doku.php?id=ff3:ff3us:doc:asm:list:music

# Updates
#### 1.1 Update

Celes's Aria de mezzo caraterre performance requires music data or else the game freezes, so I updated the IPS patch to leave this one song unsilenced (sadly the song doesn't have a F4 byte instruction to control song volume as an alternative way to mute)
