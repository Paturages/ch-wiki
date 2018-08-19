<!-- TITLE: FAQ -->
<!-- SUBTITLE: Frequently Asked Questions -->

# General FAQs
**Q: Why does nothing work in the main menu?**
A: You have to press START/ENTER to join and select a profile. If it's still not responding, press space to remap your controls in both GAMEPLAY and UI, make sure to check the blue and orange frets in UI.

**Q: Where do I get songs for Clone Hero?**
A: [This spreadsheet](https://docs.google.com/spreadsheets/d/13B823ukxdVMocowo1s5XnT3tzciOfruhUVePENKc01o/edit#gid=0) has thousands, you can also check the Charters and Setlist pages on this wiki.

**Q: How do I do Hyperspeed?**
A: Press start to open your profile settings. There's a lot of useful things in there, but Hyperspeed specifically is Note Speed. Equivalent to Hyperspeed 5 would be around 12 and Hyperspeed 4 would be around 10. Plumato has made [a tutorial](https://www.youtube.com/watch?v=Av3K41O1J1A).

**Q: Will SGH/TGH support be a thing?**
A: Not currently. SGH files are basically just containers for the PAK files that GH3 uses, and those files are encrypted.

**Q: How do I use the streamer cutouts?**
A: Download [PoisonedPanther’s cutouts](https://drive.google.com/drive/folders/0B8w3GYd7ZYz6MFN6Tk0td1hIYzQ?usp=sharing) and follow one of the following tutorials made by Acai: [for the underlay](https://www.youtube.com/watch?v=P9w5TiaaWKg), and [for the masks](https://www.youtube.com/watch?v=DcM7auwuphI).

**Q: What resolution are backgrounds and highways?**
A: Backgrounds are whatever resolution you are playing in and highways will work best at a 512x1024 resolution, but Unity will scale both of them if needed.

**Q: How can I access the Discord server?**
A: Here is a [Discord link](https://discord.me/clonehero).

**Q: How can I keep up to date with Clone Hero outside of Discord?**
A: This wiki will be updated alongside the game but we also have, and suggest following, our [official Twitter account](https://twitter.com/CloneHero).

# "Something's Wrong" FAQs
**Q: I imported a GH3 non-SGH custom, why isn't it showing up?**
A: You need to make sure that the chart is named "notes.chart" and that the audio is named "song.ogg" or "song.mp3". You can also use multiple audio stems with a GH3 custom, just name them whatever that instrument is like "guitar.mp3" or "vocals.ogg".

**Q: I've got Phase Shift songs that aren't showing up, what's wrong with them?**
**This does not apply to v21.6**
A: Some Phase Shift note charts are badly formatted, thus Clone Hero can't read them properly. There's a tool Srylain made called [Midifix](https://goo.gl/xFt3ab) that can try to fix them, but it is only able to fix midi files, not .chart files, and sometimes it can't fix some. Just download it, extract all the files, and then drag and drop drop your Songs folder ONTO the MIDIFix.exe.

**Q: I used Midifix but my badsongs.txt still says the midi's are broken.**
A: The only other solution is to download [Editor on Fire](http://ignition.customsforge.com/eof), import the midi file (F6) and then re-save the song. I don't really know why this helps or fixes the files, but it does. Do make sure after you fixed it, to go into the folder, and delete the extra midi files added to the folder that aren't just "notes.mid". The saving process will also add a few extra files, but all you really need is notes.chart, the song/guitar.ogg, song.ini file and album.png.

**Q: Why isn’t my GH:L guitar connecting/Why can’t I strum and hold down notes at the same time?**
A: In order to use the Guitar Hero: Live guitar, you MUST have:
* A 360 GH:L dongle.
* A GH:L guitar. All of the guitars will connect to any dongle except the IOS version of both the guitar and dongle.
* Windows 10, or Linux. (In order to use it on Win 7 you need Win 10 drivers, which can blue screen your computer)

**Q: Why can’t I press certain keys when using a keyboard/ some keys can't be held at the same time?**
A: The reason you can't press more than a few keys and have them register in-game is called "Keyboard Ghosting." The only fixes are either rebinding keys in hopes you keyboard will register them, or buying an anti-ghosting keyboard. Learn more from [this video](https://youtu.be/kOkV9BalNcw).

**Q: Why can't I assign my controller to Player 2/3/4 when Player 1 is using a keyboard?**
A: The first controller that's picked up by the game will always be assigned to the Player that also has access to the keyboard. In the controls screen, remove the controller from Player 1 and then assign it to another one of the players that doesn't have a controller assigned.

**Q: My song has incorrect metadata? How do I create a song.ini?**
A: First, see if your song already has a song.ini. If so, modify it. Alternatively, [create a new one](/charting#song-ini-metadata).

**Q: I have a 144Hz monitor, and my game is stuttering. Help?**
A: Try disabling Vsync, turning down the refresh rate of your monitor to 120 or so, and then set the game's framerate to whatever you set your monitor's refresh rate to. That should help.

# Extremely Frequently Asked Questions
**Q: Will online multiplayer be a thing?**
A: It is planned, but it's a huge undertaking. Because of that, whenever it happens it might take quite a while.

**Q: Why doesn’t CH save my scores?**
A: [Update to v21.6](http://clonehero.net/download).

**Q: Will custom texture support be added into Clone Hero?**
A: They might be looked into in the future.

**Q: How do I get a mod to work? (or) My game doesn’t work with mods installed, please help.**
A: We can’t support or assist anyone who uses mods for the game. We don’t know what those mods do to the game files and can cause issues with the game. We don’t hate modders, but we cannot assist you if you have mods installed.