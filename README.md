## Welcome to "CaveStoryModdingCommunity / FreewareHacks"

This is a publicly available repository of various hacks for the 1.0.0.6 freeware version of Cave Story, which you can [download here](https://www.cavestory.org/download/cave-story.php). The term "Hacks" is used within CS modding to refer to x86 assembly language modifications of the freeware executable file, whereas "Mods" is used to refer to playable standalone modifications of CS as a whole (with data files) which may or may not incorporate hacks to change aspects of the game. As such this repository contains assembly hacks you apply to the game and not playable mods.

The initial collection of hacks featured here come from over a decade of modding and hacking from [the Cave Story Tribute Site Forums](https://forum.cavestory.org/forums/modding-discussion.29/) and [The CS Modding Community (CSMC) Discord Server](https://discord.gg/xRsWpz6). This repository serves as an attempt at collecting and sorting these files into a single organized place while allowing the typical benefits of version control (such as having the latest version of each hack). As such there are tons of names attached to this repository. Every single hack here is credited either in the filename or commented inside the hack itself.
<hr>
Hacks currently come in three formats:

- **Hex Patches**: The simplest format, with only an offset and the bytes to apply. You can apply this manually using a hex editor, or automatically with [Booster's Lab](https://github.com/taedixon/boosters-lab) or [Brayconn's Patching Program](https://github.com/Brayconn/BPP).
- **XML (BL Hackinator or BPP)**: A custom format used by [Booster's Lab](https://github.com/taedixon/boosters-lab) and [Brayconn's Patching Program](https://github.com/Brayconn/BPP). Contains various tags and field types that allow for end-user configuration. This format is more complex to write but the most user friendly.
- **Doukutsu Assembler**: A custom format used by [Doukutsu Assembler](https://cdn.discordapp.com/attachments/312733438153326593/331278805781970945/Doukutsu_Assembler_1.31_EDI_defines.zip) by CarrotLord (this direct download contains an expanded "defines.txt" dictionary). This format involves written assembly which the assembler program compiles before applying the patch, allowing for easier revision and configuration of large-size hacks at the expense of often forcing end-users to actually read the hack to set local definitions. This format has seen less use over recent years, but for certain types of large expansive hacks it is arguably a better fit than the other two "hard" formats. [Here's a silly video](https://youtu.be/lPa3EF8Lvj4) for how to apply one of these hacks.
<hr>

To contribute to this repository, you may upload files while [creating a new issue](https://github.com/CaveStoryModdingCommunity/FreewareHacks/issues) (do this **ONLY** for brand new hacks, not for updating/fixing hacks that  already exist in the repository), or by forking the repository and issuing a pull request.

# How to Download and Use:
[Click here to download this repository as a .zip file](https://github.com/CaveStoryModdingCommunity/FreewareHacks/archive/refs/heads/main.zip) (there's nothing to compile/build, as it's a collection of patches for other programs).

[You can also download the unsorted-dump version](https://github.com/CaveStoryModdingCommunity/FreewareHacks/archive/refs/heads/unsorted-dump.zip), which includes additional hacks that have not been fully sorted, tested, merged into similar hacks already in the main repository or otherwise contain issues that need attention.

***It is essential to backup your executable before applying any hacks to your CS mods!*** Many hacks are not compatible with other hacks (such as those having to do with TSC or those that edit the same Weapon or NPC) and will **corrupt your mod** if both are applied. There is little indication of what hacks are compatible outside special programs such as [Brayconn's Patching Program](https://github.com/Brayconn/BPP). Practise observation and caution when patching your game.
