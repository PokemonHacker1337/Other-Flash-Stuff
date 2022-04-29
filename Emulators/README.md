Yes, there are SWF files that take ROMs. As of now, I have emulators for NES, SNES, Gameboy (color), GBA (Gameboy Advance) as well as Sega Genesis. Now, for obvious reasons, I cannot and will not include regular ROMs. You will have to get those on your own. 

The main thing of interest with these emulators are the fact that you can essentially "inject" a ROM into the .SWF and you can play the ROM from the .SWF. Of course, there's little point in this today considering we have way better emulators for the [NES](https://fceux.com/web/download.html), [SNES](https://www.snes9x.com/default.asp), [Gameboy](https://digiex.net/threads/tgb-dual-vol-8-3-1-english-download-gameboy-emulator-with-link-cable-support.14666/) and so on. You can even emulate these on a mobile phone. For the Android users, you don't even need to look outside of the Play Store. As for the Apple folk, they don't need to worry, they can use an emulator like [Eclipse](https://eclipseemu.me/play/) for free through their web browser.

So, what's the point in these? Honestly, there isn't really a real point, since these emulators are quite outdated. However, these still do exist, and it is quite nice that you can literally just inject a ROM into it and be done. Sure, it's pointless, but just remember that we have smartass programmers who run the first person shooter DOOM on quite literally everything from [printers](https://www.youtube.com/watch?v=NPWi5yJK3zo) to a [literal pregnancy test](https://twitter.com/foone/status/1302820468819288066?lang=en)

So, what's included? Obviously, as said earlier, I am not going to provide retail ROMs, so everything inside the emulators consist of nothing more than homebrew applications that I found somewhere. They are compatible with retail games, but you will have to find them yourself.

NES: A port of the famous mobile game [2048](https://en.wikipedia.org/wiki/2048_(video_game)). [(source)](https://www.romhacking.net/homebrew/65/)
SNES: An input test ROM that I found online. Credit to [tepples on nesdev.org](https://forums.nesdev.org/viewtopic.php?p=151447).
GB: A custom homebrew game called [The Bouncing Ball made by HuCABBAGE](https://gamejolt.com/games/the-bouncing-ball-gb/86699).
GBA: An input test ROM from ROMHacking.net. Credit goes to [Hammer Keyboard Studios](https://www.romhacking.net/homebrew/142/)
Sega: An input test ROM for the 6 button Sega Genesis controllers. Credit goes to [Hugues Johnson](https://www.romhacking.net/homebrew/126/)

I cannot in good faith redistribute the emulators as I originally found them, as all but 1 came with a copyrighted ROM (the only exception is the Gameboy emulator, which came with The Bouncing Ball). The NES one came with a Japanese copy of Contra. The Genesis one came with a copy of Super Shinobi, and so on. For obvious reasons, I had to change these to free homebrew applications so I wouldn't get DMCA notices filed against me. However, I have tested a small amount of games, and even ROM hacks still work nicely. I've tested the popular ROM hack [Pokémon Crystal Clear](https://www.youtube.com/watch?v=PQYBsZ78fdI), Earthbound, Super Castlevania 4, Sonic the Hedgehog (including a hack allowing the player to spindash), Pokémon Red, Blue, Yellow, Gold, Silver, Crystal as well as Emerald, Contra 3 - The Alien Wars and Castlevania: Dracula X. All of them have worked great. There were minor issues, but nothing that's impossible to work with (aside from the fact that I'm trash at old and hard games). 

Default controls:

# NES: 
Z: A

X: B

Arrow Keys: D-Pad

Enter: Start

Space: Select

# SNES: 

Z: A

X: B

A: X

S: Y

Arrow Keys: D-pad

D: L

C: R

Enter: Start

Space: Select.

# GB (cannot be reconfigured):

Q: A

W: B

Arrow Keys: D-pad

Enter: Start

Space: Select

# Sega:

Z: A

X: B

C: C

A: X

S: Y

D: Z

Arrow Keys: D-pad

Enter: Start

Space: Mode

# GBA:

See NES, the L and R buttons are C and D respectively.

# How to inject ROMs:

I've been asked this a ton, it is quite easy. I suppose it's on me for not explaining how to do it. As always, download the latest version of [ffDec](https://github.com/jindrapetrik/jpexs-decompiler/releases) and have any ROM ready. I will not assist in finding ROMs, you have to do that yourself. For the Gameboy emulator, to change ROMs, you have to open Gameboy.swf and open the binaryData tab. Inside will be a file called DefineBinaryData (1: Rom). Right click that and click the Replace... button. This will open a new menu where you can select a file, in the case of the Gameboy emulator, you may select any .gb or .gbc file and then choose to open it. This will replace the ROM with the one that you chose. Assuming you already hooked up the [Flash projector](https://web.archive.org/web/20220401020702/https://www.adobe.com/support/flashplayer/debug_downloads.html), you can choose to run it and it will happily take your ROM file and display it.

The process for the other emulators is a little different, as they are a fork of the [NESBox emulator](https://nesbox.com/) that I had laying around, but I don't remember where I got them from exactly. Even if I did, I wouldn't be able to link them directly. As said above, they contained ROMs that I'm not allowed to distribute as they contain copyrighted content. This is why all of them contain homebrew software. 

I'm going to use the SNES emulator (Snes.swf) for this example. Open the .swf like you did for the Gameboy emulator. Expand the binaryData tab and look for the option DefineBinaryData (16: Nesbox2__res_cls_rom). This is where you will replace the existing ROM with your own game. Just like you did for the Gameboy emulator, right click the option and choose Replace..., then choose any .sfc or .smc ROM file and open that. Once it is injected, you will be able to play it through the emulator. You can place this on your website to run games if you'd like. I do not take any ownership over what you do with this. I can't be bothered to type a legal disclaimer, so, we'll just say that you have been warned and I take no responsibility if you get in trouble for anything.

Supported file types:

Nes: .nes

Snes: .sfc, .smc

Sega: .md, .bin

Gameboy: .gb, .gbc

Gameboy Advance: .gba
