# GAMEBOY-74XX-512KB-PLCC
MBC1 compatible cart using 74 series logic with reflashable storage

Using footprints from https://github.com/HDR Be sure to check out their designs as well.

This is a more user friendly version of my other discrete logic cart. This uses a flash chip that can be programmed with FlashGBX. No need for UV eraser tools.

## Photos

![Gameboy 512KB Cart Discrete Logic PLCC Rev2](https://github.com/sillyhatday/GAMEBOY-74XX-512KB-PLCC/assets/65309612/cf5d6ac9-99bd-4fd6-8699-821561da8367)

## Game compatibility:

Put simply if you want to run early Gameboy games this is the cartridge you need. This is the rewritable version of the EPROM version. This is much more practical for most people.

The MBC1 can use 32KB to 2MB of game storage and 8KB to 32KB of save storage. Very few games used 2MB storage. Pokemon generation 1 in Japan is on the MBC1, fitting the whole game into 512KB. This cart will not run those games.

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
 
 **Compatability**
 
 Every single MBC1 based game under 512KB that doesn't require saving works perfectly. Well that is the theory, but I've tried a bunch of games and they all work great. This is great for early games from the Gameboys life. Mostly they didn't have a save function back then, so you just remembered your high scores. Look in the compatibility file for games I have tested myself.

**Game Suggestions**

Ballon Kid
Burgertime Deluxe
Money Idol Exchanger
Monster Max
Rodland

## Also

Check out these links:

https://ko-fi.com/nataliethenerd

https://ko-fi.com/bucketmouse

https://ko-fi.com/jamo_mods

https://ko-fi.com/lesserkuma

https://ko-fi.com/sillyhatday

https://discord.gg/moddedgameboyclub

https://github.com/lesserkuma
