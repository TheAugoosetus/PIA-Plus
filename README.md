# Chibi-Robo! Plus
## Abbreviated as PIA+

This project is based on the NTSC-U (GGTE01) version of the game. If you are using the xdelta patcher, please ensure you're using this version of the game. Please also ensure that you are using a `.iso` file. If you have a `.nkit.iso` file, please convert it to `.iso`.

## Features
- Works on native hardware! This project has been tested on a Gamecube via Flippydrive, as well as a Wii/Wii U via USB Loader GX with Nintendont
- Creates a supplementary PIA Plus Config save file (complete with a custom banner and icon) to store PIA+ settings and bindings
- Adds a vastly expanded Options menu (including a Widescreen toggle, Button Remapping, and Camera Inversion toggles)
- Allows mapping items and costumes to the D-Pad for equipment quick-swapping
- Implements the ability to press B to skip dialogue printing (doesn't automatically skip dialogue, which can be blocked by longer animations)
- Implements a prompt to skip the birthday party intro when making a new save
- Allows paging the save menu to access a new hard mode and, when unlocked, a new NG+ mode that adds three new items to the shop and begins with all utilibots unlocked.
- Adds new pajama icons so that your equipment menu matches the material you chose
- Adds various QOL changes
- Fixes various broken textures and retextures select items to reference later Chibi-Robo titles

While using it will overwrite the texture changes I've done, this should work with the HD Texture Pack by Ewzzy! This can be downloaded at [https://forums.dolphin-emu.org/Thread-chibi-robo-hd-texture-pack?page=4].

## Special Thanks
- The original development team for making the original and incredible game
- Derpky for making the most crucial tool of this entire project with Unplug
- EverydaySimpleDev for their dev notes from the Archipelago project, which saved me countless hours of work
- My friends in software engineering who helped answer my (many, many, many, many) questions
- Other Chibi-Robo modders for their work, all of which provided a base without which this project could not have happened (cited below)
- My wife and other friends who've never played the original who let me subject them to forced beta testings
- Chao-Etta, Fliksie, and Feminine Emininem for being invaluable Beta Buddies
- DreamOre for encouraging me to change the name
- Everyone in the Chibi-Robo discord for being so supportive!


## Work by Other Modders
*This mod would not be possible without the tools, discoveries, or previous mods done by other incredibly talented Chibi-Robo fans*
- Derpky's Unplug: [https://github.com/adierking/unplug]
- Emistro's Unplugger: [https://emistro.itch.io/unplugger]
- Kobazco's Text Skip: [https://discord.com/channels/172904892564766720/172904892564766720/834165282263400488] (it's a message from the Chibi-Robo discord)
- Darkludx's Widescreen Gecko Code: [https://wiki.dolphin-emu.org/index.php?title=Chibi-Robo!_(GC)]
- EverydaySimpleDev's Github: [https://github.com/EverydaySimpleDev/Chibi-Robo-Randomizer]

# Other Resouces
*General GameCube Modding Tools*
- Ghidra ([https://github.com/nationalsecurityagency/ghidra]): Reverse Engineering
	- Ghidra Gamecube Loader ([https://github.com/cuyler36/ghidra-gamecube-loader]): Enables loading of GCN binaries into Ghidra
	- I learned how to use Ghidra with a lot of trial and error and a few different guides, but this is a good place to start: [https://mariokartwii.com/showthread.php?tid=1193]
	- main.dol file documentation: [https://github.com/NicholasMoser/Naruto-GNT-Modding/blob/main/gnt4/docs/file_formats/dol.md]
	- By the time you read this, there may be a more up-to-date Ghidra map for Chibi-Robo! Look into the decomp efforts on [https://github.com/eavpsp/cbr_decomp]
- Debugger Version of Dolphin Emulator (use the command line to open this version of Dolphin)
	- Guide to Debugger Dolphin: [https://tasvideos.org/Forum/Topics/18555?CurrentPage=1&Highlight=443246#443246]
- BrawlCrate: [https://github.com/soopercool101/BrawlCrate]
- GCFT: [https://github.com/LagoLunatic/GCFT]
- BNRTool: [https://github.com/xchellx/bnrtool]
- Texture Editing: originally paint.net, but later moved to GIMP
- Model Editing: Blender 4.5.7 LTS (this version is used for compatibility with the below add-on)
	- GameCube Model Blender Addon: [https://github.com/StarsMmd/Blender-Addon-Gamecube-Models]
- Wii Explorer: [https://kuribo64.net/board/thread.php?pid=3245]
*Learning Coding*
- Beej's Guide to C Programming ([https://beej.us/guide/bgc/])
- PowerPC Full Beginner's Assembly Tutorial ([https://mariokartwii.com/ppc/])
- PowerPC Beginner's Tutorial ([https://community.wemod.com/t/powerpc-beginners-tutorial/2039])
- PowerPC Assembly Programming for the GameCube ([https://www.chibiakumas.com/powerpc/gamecube.php])
- ChibiAkuma's Multiplatform Assembly Programming ([https://www.chibiakumas.com/powerpc/])
- PowerPC ASM Cheatsheet ([https://zenith.nsmbu.net/wiki/Custom_Code/PowerPC_Assembly_Cheatsheet])
- Decomp Academy ([https://github.com/JackPriceBurns/decomp-academy-fe])
- Decomp Toolkit ([https://github.com/encounter/decomp-toolkit])
- devkitPPC ([https://wiibrew.org/wiki/DevkitPPC])
- Gecko Code Documentation: [https://github.com/AlexanderHarrison/HOW-TO-WRITE-GECKO-CODES]
*Misc.*
- Custom Nintendo Splash Logo: https://www.textstudio.com/

Generative AI Disclosure:
GenAI was not used for vibecoding, generating assets, or for any creative decisions. However, during the process of this project, the work of some modders (upon whose work I built from) was found to be GenAI-assisted. 
