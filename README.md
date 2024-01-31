# GAMEBOY-74XX-512KB-PLCC
MBC1 compatible cart using 74 series logic with reflashable storage

Using footprints from https://github.com/HDR Be sure to check out their designs as well.

This is a more user friendly version of my other discrete logic cart. This uses a flash chip that can be programmed with FlashGBX. No need for UV eraser tools.

## Game compatibility:

Put simply if you want to run early Gameboy games this is the cartridge you need. It’s not the most practical of carts but it’s one of my earlier ideas and wanted to keep it. I got a bunch of EPROM for free so I put them to use. This lacks any save ability but can run the MBC1 games up to 512KB. I will not give this a compatibility rating as it is impractical for most people.

The MBC1 can use 32KB to 2MB of game storage and 8KB to 32KB of save storage. Very few games used 2MB storage. Pokemon generation 1 in Japan is on the MBC1, fitting the whole game into 512KB. This cart will not run those games.

Unless you want to source obsolete ceramic EPROM or EEPROM that are even rarer, you can just run most games this uses on an MBC5 2MB cart instead. I am working on a version that uses a more regular flash chip that will make it rewritable in the usual Gameboy cart programmers

**FLASH**

Using a readily available AM29F040 PLCC chip. Origianlly I designed this for a socket but quality sockets are not cheap and the benefits are small to having removable storage. The cart is flashable on FLashGBX, so you are not stuck with one game. Originally the idea was to program the chips externally and swap them in and out.
 
 **Discrete Logic**
 
 You'll need 5 seperate 74XX logic chips to replicate the bank switching of an MBC1.
 | Part No | Description | Amount |
 | --- | --- | --- |
 | 74HC32 | Quad 2 input OR Gate | 1 |
 | 74HC27 | 3 Input NOR Gate | 1 |
 | 74HC174 | Hex D Type Flip Flop | 1 |
 | 74HC08 | Quad 2 Input AND Gate | 1 |
 | 74HC00 | Quad 2 Input NAND Gate| 1 |
 | 29F040 | Flash Storage | 1 |
 | 100nf Cap | 0603 | 1 |
 
 Make sure to get really nice solder joints when putting these on. I've seen perfect looking joints that do no make connection. Any problems when first trying out the cartridge, reflow all the 74XX chip legs.
 
 I haven't put any local filtering for the logic as mostly there isn't room and I've seen no need for it. There is no save function so a game crash will ruin your progress but not ruin a save. Maybe it's needed, I don't know, so there is a single bypass capacitor up by the EPROM. I personally haven't populated it.
 
 **Compatability**
 
 Every single MBC1 based game under 512KB that doesn't require saving works perfectly. Well that is the theory, but I've tried a bunch of games and they all work great. This is great for early games from the Gameboys life. Mostly they didn't have a save function back then, so you just remembered your high scores. Look in the COMPAT file for games I have tested myself.
 

**Also**

Check out these links:

https://ko-fi.com/jamo_mods

https://discord.gg/moddedgameboyclub

https://ko-fi.com/sillyhatday

https://github.com/lesserkuma

https://github.com/HDR
