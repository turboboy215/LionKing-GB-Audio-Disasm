# LionKing-GB-Audio-Disasm
The Lion King (Game Boy) audio disassembly

A disassembly of the sound engine and data from The Lion King for Game Boy, fully labeled and commented. Can be built with RGBDS; the sound data of the resulting ROM is verified to match the sound data from the original ROM exactly. However, the resulting ROM itself on its own is not playable, as no additional code is included. A text file is also included which documents how the music, sound effect, and instrument data is structured for this game as well as other games using versions of the same sound engine.

This game uses a later version of the sound engine in R-Type II as well as its predecessor R-Type; see https://github.com/turboboy215/RType2-GB-Audio-Disasm for a text file which documents how the music, sound effect, and instrument data is structured for these games as well as other games using versions of the same sound engine. This game's sound engine code is also identical to Alfred Chicken (https://github.com/turboboy215/Alfred-GB-Audio-Disasm), but with different ROM and RAM addresses used, and the "duplicate partial" frequency table absent.
