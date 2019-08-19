# Quest for Glory III: Wages of War - Unofficial Update 1.3A
## Author: AshLancer
## E-mail: raziel7fallen@gmail.com
## [GitHub Link](https://github.com/AshLancer/QFG3-Fan-Patch)


### Introduction:

Welcome to the very first QFG3 fan patch! 26 years ago, Sierra and the Coles released the third entry in the Quest For Glory series to near-universal acclaim in 1992. However, anyone who's played this game can tell you that it had some nasty, obnoxious bugs which sent many users crashing to their desktops and hampered replayability for decades. I've been playing this game on and off over the last 20 years, constantly staring at that 497/500 puzzle point score on my Paladin's status screen and remaining frustrated at an inability to bring closure to his journey. Now at last, I'm very proud to release this monumental personal achievement to the community in an attempt to give back to one of the greatest RPG series that I've ever had the honor of playing as a kid.

Quest for Glory 3: Wages of War is probably the least discussed game in the series. It's riddled with design flaws, lack of content, inconsistencies, glitches, crashes, and script errors. Due to poor management and being that it was never planned as an entry, it didn't get enough of a budget attached and was rushed out along with roughly 6 months of development time and playtesting still incomplete. Yet despite all of its flaws, a lot of fans still fondly remember QFG3 for its originality and unique identity. It was one of the only RPGs at the time to feature an African-styled savanna and jungle setting. The characters are still as well-written and endearing as any of the other games in the series. The story, although linear for the most part, delivers a timeless message that continues to hold weight even in today's world. And a lot of the background artwork still presents itself as one of the finest and most detailed examples of VGA graphics from early 90's era PC gaming.

This patch is the culmination of the last 6 months I've spent playing, testing, learning, and recoding the scripts of QFG3 in an effort to polish what I and many others often consider to be the buggiest game in the series. It's also an attempt to increase awareness and to encourage more people, both old and new to the series, to play this game!


### Requirements:

This patch is for updating QFG3 from any previous version up to 1.3A (the A stands for my name!). If you are running this patch and your version doesn't read as the correct number in the game's About section, then either you haven't installed all of the files, or your copy of the zip is a fake. You can check the About section by bringing up the options menu and clicking on the Sierra mountain logo.

You'll need a copy of QFG3 installed on your device from either a 3.5" floppy, CD-ROM, Steam, or GoG. You do NOT need to install the NewRisingSun speed fixes. They are included in my patch. You will also most likely need a DOS emulator to run the game, depending on your system. The best two currently available are DosBox and ScummVM. This patch is fully compatible with either emulator, although ScummVM users please be aware of known issues listed below.

It's HIGHLY recommended that you start a new game in order to take full advantage of this patch. Depending on where you saved before installing, you may encounter glitches, or you may not be able to load your save at all.

This patch is currently only compatible with the ENGLISH version of QFG3. Sincerest apologies to all foreign language users. I hope to release an international version soon!

You can always find the latest version hosted on my GitHub page. Link at the top of this readme.


### Installation:

If you wish to create a backup before installing, please copy all numbered .scr, .hep, and .msg files in your QFG3 folder to a new directory.

Simply extract the contents of the zip into the same folder where you have QFG3 installed (ex. C:/Sierra/Quest for Glory Collection Series/Quest for Glory 3/) and overwrite all files when prompted. Enjoy!

To uninstall, just delete all of my patch files and restore the backup.


### New Features:

- Every class can now reach 500 puzzle points, and Fighters who transition to Paladin via the ceremony can reach 550!
- You can now train Pick Locks on the chest in your room and hut.
- Every class that has skill in Pick Locks will now start with the Thief's Toolkit.
- Thieves and imported characters with points in thieving skills will now start with the Guild Card.
- You can now train Climbing on Manu's tree.
- Fighters and Paladins can now train Zap outside of combat.
- You can now train Open and Detect Magic on the Savannah or Jungle screens (where it won't cause you to lose honor). You can also train any spell in Kreesha's magic shop if you want.
- It's now easier to fail the requirements for becomming a Paladin and remain a Fighter for those who choose to do so.
- You can now modify your Honor stat with Uhura at the Simbani Village after the peace conference.
- You can now leave the Monkey Village before crossing the waterfall and go have random encounters. Manu will be waiting patiently for you to come back!
- The rooms with Reeshaka and the endgame have been enhanced. I'd prefer to keep these a secret... :3
- New ways to die! (see below)
- Wizards and Thieves will no longer have the opportunity to rescue the baby meerbat.
- The log will no longer spawn during the ring of thorns challenge if the player can get the ring.
- You must now learn about the Lost City from Manu before you can convince him to take you there.
- Fighters and Paladins will now gain points for creating a vine rope, rather than from using it to cross.
- Wizards must now tell Manu about the Levitate spell before they can ask for cooperation.
- Paladins are no longer forced to export with the Magic skill if they don't want it.


### Patch Highlights:

- Fixed the game writing overflow errors to your .sav file when exporting your character.
- Fixed the infamous crash when Yesufu throws a spear at the twisted tree challenge during the initiation.
- Fixed the crash when the Guardian of the World Tree gets angry at you (CAUSED by NRS's fix btw =w=).
- Fixed the dead end encounter where the Awful Waffle Walker never spawns in the Jungle while you're starving.
- Fixed dead ends caused by encountering Johari again after already reaching the Leopardman Village.
- Fixed dead ends caused by imported Heroes changing their class, but never being granted points in their new class-specific skills.
- Fixed the dead end caused by eating the Venomous Vine Fruit.
- Fixed the music disappearing when releasing Johari from her cage.
- Fixed the annoying music loop glitch when you beat Yesufu at the spear throwing contest.
- Fixed the music not looping when you meet with the Leopardman Chief.
- Fixed the annoying pathing glitch at the top of the World Tree where clicking on the Guardian cave or the exit would send the Hero back inside.
- Fixed script errors where you couldn't talk to Uhura in your hut, and where she'd stop talking after asking about "Woo".
- Fixed a script error where Fighters and Paladins couldn't tell Rakeesh about the Initiation and missed out on 3 points.
- Fixed bugs and annoying sound loops during the Shaman duel.
- Fixed bugs and missing sounds when stealing the Drum of Magic and the Spear of Death.
- Fixed spellcasting issues for every single room in the game.
- Fixed multiple problems in the endgame scripts for each class.
- Fixed several lockups caused by faulty scripting.
- Fixed several faulty triggers.
- Fixed several incorrect sprites, offsets, animation cycles, and animation speeds.
- Fixed various background objects being deleted or hidden, not being defined, or not getting initialized at all.
- Fixed various sounds disappearing, endless sound loops, and missing sounds.
- Fixed missing messages, incorrect messages, missing dialogue, errors in dialogue trees, and a few typos.
- Fixed a couple of exploits when importing during character creation.
- Restored a cut event where you could meet and console Uhura at the Simbani Village after the peace conference.
- Restored a cut event where you could sleep at the Monkey Village.
- Restored several deaths and missing or unused death messages, specifically:

  * Steal from the Drummer too many times and get arrested
  * Anger the Guardian of the World Tree until it throws you out
  * Get killed by an Apeman on one of the Lost City screens
  * Get killed by the Demon in the Lost City
  * **Wizard** Cast Summon Staff and then Trigger to blow yourself up
  * **Thief** Wait for the leopard to finish eating and then let him jump up and kill you
  * **Thief** Cross the rope at the waterfall with low agility on Medium or High difficulty
  * Starve to death (new animation!)

- Restored the proper icon for Soulforge in your inventory.
- Restored the Guild Card item.
- Restored several unused sprites and animations.
- Restored several funny messages for clicking certain items on yourself.
- Restored a LOT of unused text.
- And over 200 other bug fixes and restorations!


**Note: A complete list of changes (for NERDS) has been included in the accompanying readme.*


### Known Issues:

There's an annoying glitch where sometimes the player stops having their date/time box pop up on the overworld map after the peace conference. I've been unable to track down the cause of this, but I created a workaround (coincidentally!). Just sleep at the Monkey Village and it should be fixed the next day.

Be very careful when setting the game's Speed to maximum on higher CPU cycles. The Hero can run so fast that he sometimes ends up reaching targets before the engine can execute scripts. This may result in glitches, lockups, or even crashes. Save often!

Sometimes the game just crashes or freezes randomly after playing too long, when in the encounter screen, entering a battle, or playing Awari. I honestly have no idea what's going on.  O _ O  Save often!!

ScummVM uses a completely different interpreter from the original SCI, and as a result it may introduce new bugs that are totally unrelated to my patch. Currently, it has an obnoxious glitch where the night cycle appears as day. No idea what is going on with this or if I somehow broke it again, because it was supposedly fixed in their last build. Contact the ScummVM developers for help.


### FAQ (may contain spoilers!):

**Q** - Where are the missing points for each class?

**A** -
* **Fighter/Paladin**<br/>
	Tell Kreesha about initiation - 3<br/>
  Win initiation contest - 10

* **Wizard**<br/>
	Stop Harami with magic - 7

* **Thief**<br/>
	Stop Harami with dagger or fruit - 5


**Q** - I can't seem to find Khatib the Survivor at the inn for those last few points.

**A** - Getting Khatib to spawn can be a bit of a nuisance. The only requirement seems to be that you must have eaten at the inn at least ONCE (indicated by the topic "Restaurant" disappearing from Janna's dialogue tree). You'll also need to enter the inn at a specific time of night. I've included a screenshot of the moon in the zip to help people who are having trouble. If you're successful, you'll see two empty seats at the middle table when you enter. Also, keep in mind that Khatib will NOT spawn on the same night that you've had your first meal there.

I've found the best way to do this is to run around the savanna just outside of Tarna until it starts to get dark. Keep moving until the screen gets completely dark and then immediately enter the city. Try and visit the inn now. If the two seats still aren't open, exit the inn, rest for an hour, and enter again. You should trigger the encounter.


**Q** - I've done everything but the Leopardman Prisoner just won't show up!

**A** -
* **Fighter/Paladin** Keep practicing throwing spears at the target until Uhura shows up, then challenge her.
* **Wizard** Talk to the Guardian to find the Blue Orchid and complete the quest for creating your staff.
* **Thief** Reach the far eastern screen with the big waterfall.


**Q** - Help! The guard won't let me back in to see the Laibon or the Laibon won't take my dinosaur horn and I can't continue. I thought you fixed everything!!!

**A** - The triggers for the Laibon starting the initiation are still a bit wonky. Here is a method that always works for me:

	Leave the Laibon's hut
	Open the inventory/chest and drop ALL dinosaur horns
	Go back inside and ask the Laibon about every topic
	Click the Mouth on yourself and talk about every topic
	Leave and go get another horn from a dinosaur
	Go back to the Laibon and try giving it to him again


**Q** - I'm doing the ring of thorns challenge and the log is gone!

**A** - Check your inventory. The answer's in plain sight. ;p


**Q** - How do I fail the Paladin ceremony and stay as a Fighter?

**A** - The best way to do this without losing points is to enter the cave in the side of the giant tree and throw some daggers/rocks/spells at the Guardian until he spins you around (also an animation fix by me). This should disqualify you later. Paladins are supposed to be paragons of justice, virtue, and all-around goodness, and attacking one of Mother Nature's most sacred creatures isn't exactly upholding that image.


**Q** - What are the exact new requirements for becomming a Paladin in QFG3?

**A** - You need to be a Fighter and have at least 150 Honor to qualify for the Paladin ceremony. You also need to have NOT done one of the following dishonorable acts:

* Taking any action other than RUNNING after Harami during the chase
* Leaving the bazaar at night without helping Harami
* Attempting to steal from the drummer
* Refusing to swear the oath at the Hall of Judgement
* Letting the baby meerbat die
* Killing the baby meerbat yourself
* Not helping Yesufu during the Initiation
* Attacking the Guardian at the Heart of the World Tree
* Abandoning Manu in the cage in the jungle

If you've satisfied all the requirements, you'll be treated to a cutscene just before the peace conference starts and Rakeesh will even give you his sword, Soulforge. Congrats!!! ^w^


**Q** - I'm a Fighter who became a Paladin, but my Honor is maxed out and I can't gain any more Paladin Points.

**A** - This is a design flaw in the original game. I created a workaround (also coincidentally!) when restoring the post-conference event. If you haven't crossed the waterfall, you can actually go back to the Simbani Village and meet Uhura in a one-time event. Once there, keep repeatedly trying to enter the village and your Honor will gradually be lowered. Then talk to Uhura and keep consoling her to raise it again. This should grant all the Paladin abilities you've rightfully earned. Once you leave, you are forever banned from the Simbani Village.


**Q** - You broke the final battle!!!! Why do I keep dying??

**A** - Read the message carefully. The answer's in plain sight ;p


**Q** - How can I export my Paladin without learning Magic?

**A** - I've written an algorithm that will intelligently detect whether or not you intended to learn magic. If your Paladin successfully completes the game without learning any spells (other than Heal), their magic stat will be stripped upon exporting. Since no new spells can be acquired after the peace conference, a Fighter who becomes a Paladin in this game and still wants to have magic will need to relearn the skill in QFG4 or 5.


**Q** - Are you planning on making patches for the other games in the series?

**A** - Absolutely! I'm currently working on a QFG4 patch as we speak. Expect it ~~before the year ends...~~ *by Halloween 2019!* :3


### Legal:

These files (and this readme) are the sole product of yours truely: Alex Abrahamian, a.k.a. AshLancer, or raziel7fallen. I claim all ownership over my contents and changes to the game and reserve all rights in controlling how this patch is distributed and reused. Downloading and installing this patch means agreeing to the conditions as written below.

This patch is a non-profit 3rd party modification and is distributed as freeware, although donations are welcome. Neither myself nor this patch are legally affiliated with Sierra, Activision, or the Coles and I do not claim to respresent their interests or positions in any way, whatsoever.

The contents of this patch are provided "as-is". Although I've done my very best to playtest and ensure that this patch's quality meets all the goals and standards set for it, I am not liable, nor do I claim any responsibility for any damage resulting to the user's character, save file, software, or device that may occur from installing or running this patch.

You MAY redistribute this patch freely, install it as many times as you want, and advertise it so long as you give all credit to the author.

You may NOT claim this patch as your own, charge money for it, modify any of its contents (including this readme), or reuse its contents without my express permission. Any infringement is subject to full legal action and statutory damages as defined for Fair Use under section 107 of the US Copyright Act of 1976.

Quest for Glory III: The Wages of War is US Copyright 1992 by Sierra On-Line, Inc. and is designed by Lori Ann Cole and Corey Cole. SIERRA with mountain design is © 2018 by Activision Publishing, Inc. All rights reserved. I do not claim ownership over any of their code, files, software, or properties except for my own changes which I have created for personal, educational, and recreational use.


### Contact:

Questions, concerns, suggestions, donations, praises, condemnation, and more! Please direct them towards my email address at raziel7fallen@gmail.com.

Be sure to include "QFG3 Patch" in the subject somewhere so I can have an idea of what you're asking about, otherwise your email may be regarded as spam and trashed. English is my primary language, although I'm learning Spanish and Japanese. I'll typically respond within 1-2 business days unless something comes up. If it's a question that can be answered from the FAQ section, I'll refer you to that. If it's an urgent matter involving a bug (like the game has been rendered unplayable), I'll most likely investigate and release a hotfix promptly!

You can also contact me via PMs on the facebook groups, or search for AshLancer or raziel7fallen on the QFMG and SHP boards. If I'm online, I'll try to answer you ASAP.


### Credits:

SCI Companion 3.0
without which, NONE of this would've been possible.

NewRisingSun
who developed the initial speed fixes that allowed us to keep playing these games on modern systems. You rock, dude!!

Sierra Help Pages
for their extraordinary effort in continuing to maintain support for these titles.

Google, various Let's Plays and speedruns on Youtube, and the forums and communities at Quest for More Glory, SHP, ScummVM, GoG, and Steam. For feeding me plenty of bug reports, research material, and rumors to go on.

Quest for Glory Omnipedia
providing a dump of the transcripts and additional background info.

Sierra Chest
for letting me get a look at the official manual and hintbook.

CyricZ
for his AWESOME walkthroughs and point lists that thoroughly cover every game in the series.

QFG Speedrunning group on Discord
providing additional glitch and bug reports, teaching me shortcuts, and just being all around good chums!

All of the fan groups on Facebook: Quest for More Glory, Quest for Glory Fans, and Sierra Gamers. For keeping the brand and this amazing legacy alive!


**_SPECIAL THANKS TO:_**

Cyber Crimson,
keeping me going those times when I got disheartened

My two younger brothers

2 cats and a bird

Sierra On-Line
Ken and Roberta Williams
for making some of the greatest PC games on the planet!

Lori Ann Cole and Corey Cole
for creating such an incredible series. You guys defined my childhood RPGamer! ^_^

Lastly,
dedicated to the players
...this patch was for all of us.


### Version Updates:

8/18/2019 - Version 1.3.1A - Fixed the *Salim forgets Dispel Potion ingredients* bug. Removed it from the FAQ.

4/06/2019 - Version 1.3A - The spellcasting update! Fixed spell scripts for every single room in the game. Repaired keyboard controls and restored missing points for the initiation challenge. Additional bugfixes and enhancements. Minor spelling corrections.

10/01/2018 - Included a script from the Collection CD for people who were having problems getting the dispel potions from Salim. Minor updates to the readme.

8/22/2018 - Version 1.2A - Initial release.
