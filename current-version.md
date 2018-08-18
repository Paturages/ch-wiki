<!-- TITLE: Current Version -->
<!-- SUBTITLE: Changes in v.21.6 -->

* Fixed issue where starpower could be awarded multiple times on phrases that ended with extended sustains.
* Fixed issue where starpower could be awarded before the end of a starpower phrase on phrases that ended with extended sustains.
* Fixed issue where with starpower in disjoint chords, where missing a note within last note in a starpower phrase yet starpower gems would still show.
* Fixed issue where the game would display "New High Score" in scenarios where the new score was not actually better.
* Fixed issue where the game would save the highest speed a song was played at even if the score achieved at that playspeed wasn't the best.
* Fixed issue where songs would start at wildly incorrect offsets in certain culture configurations such as Denmark.
* Potentially fixed the issue where certain songs (notably songs exported from Guitar Hero III) played at the wrong speed in certain culture configurations.
* Fixed a midi forcing bug on songs with force notes that are the same length as the note they are forcing.
* Fixed a midi forcing bug on songs with 0 tick length force notes.
* Fixed rare issue where certain midi charts could error while loading
* Fixed songs with empty lyric events being marked as a bad song
* Fixed 6-fret practice mode lefty flip.
* Update 6-fret extended sustain logic to be in line with the 5-fret extended sustain logic
* Fix disjoint chords not working in several scenarios in 6-fret mode
* Fixed crash with custom backgrounds which caused a black screen on song selection.
* Fixed lower difficulty scores overwriting higher difficulties.
* Fixed issue where charter icon fallback did not work in the results screen.
* Updated the 6-fret open note hopo texture to match the new hopo textures.
* Fixed bug where deleting a profile would corrupt all player profiles.
* Fixed solos not giving correct bonus with disjoint chords.
* Updated unity to 2018.1.8f1
* Changed note tails so held sustains will always be the correct length relative to the un-hit version.
* Fixed bug where 6-fret ui icons would not work when the first player had dropped out.
* Cleaned up code around sound effects playback.
* Added more charter icons.
* Added song fail sound effect.