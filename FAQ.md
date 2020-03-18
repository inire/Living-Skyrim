# Living Skyrim FAQ & Troubleshooting
Additions will be made to this FAQ as needed.

**What do/don’t you support?**
All unmodified Wabbajack installs of Living Skyrim are supported. Pirated copies of Skyrim are illegal and not supported. Any modlist that changes Living Skyrim by adding/removing mods is not supported. Manually installed reproductions of Living Skyrim are not supported (though kudos will be given if you figure it out for yourself.). Re-shade and alternate ENBs are not supported. Mods from LE/Oldrim are not supported and will never be included in Living Skyrim. Converting old saves to Living Skyrim is not supported, only new saves created after Living Skyrim is installed are supported.

**The installer isn’t working, what can I do?**
The short answer: wait for an update. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Living Skyrim is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

**How often does Living Skyrim update?**
There’s no set schedule for Living Skyrim updates. If a mod updates and the list requires a revision, I’ll try to get to it as quickly as possible, but I make no promises. Sometimes troubleshooting updates and rebuilding the list can take days. Anytime there is an update, it will be clearly communicated on the Wabbajack Discord server. That being said, as long as nothing else changes, you should be safe to continue playing an existing installation unless there is an update to Skyrim itself. Remember: the point of all modlists is to play the game. If you’re spending more time updating your list than playing, you’re doing it wrong.

**I found a bug! How do I report it?**
Check the [Bug Tracker Trello](https://trello.com/b/myVMRRQU/living-skyrim-bug-tracker). If it’s not already on there, contact ForgottenGlory directly. Be as specific as possible, including screenshots if possible. If it is related to a specific mod, include the name of the mod and the exact steps to reproduce the issue. The best thing you can send for things like incorrect numbers/values or dark face NPCS (if there are any)  is a screenshot of the thing in question selected with the console including the ID of the object/character.

Vague reports such as “my game randomly CTDs” will be ignored if they do not include more details.

**Can I play this list on a 75/100/144hz screen?**
Yes. The SKSE64 Havok Fix is included.

**Is [mod name] included in this list?**
Probably not. Check the [LS spreadsheet](https://docs.google.com/spreadsheets/d/1sKG690CbutxCFhDLfTH7C6yYCz0dOkZkuKfYAqRBRVU/edit?usp=sharing) to be certain. Feel free to suggest it if you think it fits with Living Skyrim.

**The modlist updated! Do I have to update and start a new save?**
If your game is working, you’re not required to update. It’s always recommended though, as updates likely fix bugs, update mods, or add new mods or remove unsatisfactory ones.

As for starting a new save, it depends on the version. In general, anything that is an x.x.# update won’t break your save, and is usually just for when a mod updates and the list needs to be recompiled to make it work again. Anything that is an x.#.0 update adds or removes mods, which likely will break your save (unless otherwise specified). Any full version number changes, #.0.0, are major overhauls/rebuilds of the list and are guaranteed to break your save.

**Can my computer run this list? [insert specs]**
I don’t know. The System Specifications are an exact list with details of the computer this list was compiled and tested on. If your build is better than or equal to that, yes. If not, maybe, but expect to have poor performance especially in heavily occupied areas like Whiterun.

**Can I use an ENB other than Re-Engaged?**
Sure, if it’s compatible with Obsidian Weathers. Support is not provided for any ENB other than Re-Engaged, though.

**Some Alternate Starts are impossible/OP!**
Unlikely. Fighting everything isn’t an option in this list, OBIS, Populated Skyrim, and the combat mods make sure of that. Running away is required sometimes. On the flip side, you’ll quickly run into enemies that are stronger than you even with the “OP” starts. Sometimes you’ll need to clear part of a dungeon and then come back to it later when you’re stronger. The Take Notes mod is very helpful for remembering places you need to revisit. If you’re struggling to level up, Missives and just exploring is your friend. Hunting wildlife is also viable. Most of the first few quests of the major factions/guilds are possible early on, but the main quest will likely need to wait until you’ve established yourself somewhat.

**Can I stream/Let’s Play this modlist?**
Absolutely.

**Can this list be made NeverNude/without physics?**
Yes. Re-install CBBE and select one of the NeverNude options and the CBBE RaceMenu Morphs. You will also need to regenerate the BodySlide files using the NeverNude body. Bijin NPCs will still be nude, but it is extremely unlikely that it will be visible unless you strip them on purpose or they die and are stripped, which is also extremely unlikely. You can replace the Bijin mods with the NeverNude CBBE version of the Bijin mods if you’re concerned about this possibility.

Physics is a bit trickier, I am looking into how exactly this should be done but in general, you would need to regenerate BodySlide information without physics and turn off CBP Physics. This may require that the Bashed/Smash Patches be rebuilt, but I haven’t tested yet. If anyone has success in doing these two things, please feel free to let me know.

**Why is FNIS Spells disabled? Can I turn it on?**
This causes issues with Classic Classes & Birthsigns and the Alternate Start mod. CC&B doesn’t start until you equip a weapon, and FNIS Spells automatically equips spells, which count as weapons. Really, FNIS Spells is more or less only useful for screenshots, so it’s still included if that’s what you’re interested in, but otherwise, it needs to be left off for CC&B to work properly. If you’re just screenshot hunting and not doing anything else, it can be enabled. It isn’t recommended to use for an actual playthrough. You will need to re-run FNIS if you turn FNIS Spells on.

How do I use Classic Classes & Birthsigns? Nothing happened during character creation.
CC&B, to work with alternate start mods like Live Another Life, has been modified slightly so that it doesn’t start until you equip a weapon/spell. At that time, you’ll be prompted to give your character a class and pick a birthsign.

**My equipment animations are broken/weird!**
First, check to make sure you’ve followed the MCM instructions for XPMSE. This should fix any weirdness (sword on hip but being drawn from back, for example.). If you’ve just equipped a new weapon/shield, the animation to draw it may be weird for a few seconds but it will eventually fix itself. XPMSE and AllGUD need a few seconds to register the new weapon configuration and should fix themselves. This is not a bug, just be patient and the mods will figure it out eventually.

**Re-Engaged ENB doesn’t work with Predator Vision!**
It does. Follow the instructions in Re-Engaged’s description titled “Night Eye Fix Adjustment”. A video and image guide are provided to correct this. If it still doesn’t work, report it to ForgottenGlory. Alternatively, Predator Vision has been confirmed to work on the Silent Horizons ENB. Alternatively alternatively, try the fix here: [Click Me!](https://cdn.discordapp.com/attachments/623292774229213185/680784020669333650/image0.png)

**Master of Disguise asks me to update every time I load the game.**
Yep, it’s really annoying. You can turn it off in the MCM for Master of Disguise in the Advanced Menu. Turn off the Factions Update Auto Run.

**My game freezes when saving.**
Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. 

**Can I use a controller/gamepad?**
Yes, Gamepad++ is included by default.

**Can I use this list on an ultrawide monitor?**
At a minimum you’ll need to add the [Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778), but yes. Just make sure you select the right version.

**I can’t move!**
Gamepad++ only needs to be enabled in MO2 if you are going to be playing the game using a controller. Otherwise, you should disable it in the left pane of MO2. You will not be able to move using mouse/keyboard unless you disable Gamepad++.