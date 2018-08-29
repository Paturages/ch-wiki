<!-- TITLE: Charting -->
<!-- SUBTITLE: This is all the theory that goes behind charting. -->

This tutorial is designed to help you become a better charter, even if you have zero experience. The tutorial will cover all the concepts that need to be known to become a success charter.

# What is a chart?
A chart, also called a map, is a sequence of notes for rhythm based games that correspond to the music or audio that it's charting. Charting is essential to all games that require specific gameplay to the played music.
# Fundamentals
## Notes
The very basic fundamentals include notes. Their uses and information are located [in the dictionary](/ch-dictionary#note-types).
## Chords
Chords are when two notes of different pitches are played together. Generally, only 2 and 3 note chords are used (the chord consists of two or three notes). 
### 2 Note Chords
For guitar, 2 note chords are used when a power chord is played, or an interval is played.

For other instruments, they’re used when two notes are played together.
### 3 Note Chords
For guitar, 3 note chords are used when a chord is played.

For other instruments, they’re used when three notes are played together.

3 Note Chords should have 0 or 1 spaces in between the notes. This means that GBO and GRO chords should not be used outside of extreme exceptions.
## Sustains
Sustains are when notes are held down for longer than the attack.
### Sustain Gap
Sustain Gap is where sustains are “trimmed” before the next start (there is a gap between the sustain and the next note). 
### Extended Sustains
Extended Sustains are sustains that extend past the start of new notes.
### Disjointed Chords
Disjointed Chords are chords where the sustains of the notes in the chord vary in length.
## Patterns
## Star Power
Star Power (SP) helps the player score more points by doubling the current multiplier. SP is obtained in phrases; each note of the phrase must be hit to obtain. A successful phrase raises the SP Meter by 1/4. If a sustain note is in a phrase, whammying will gradually increase the meter as well. To activate SP, the meter must be at least 1/2 full. A 1/2 filled bar will last for 4 measures of music. 

> If you've played GH for long enough you should kind of be able to tell where a starpower should be. As a general guideline, starpower phrases shouldn't be closer than 4 measures and should probably be at least eight measures apart. Thirty seconds should be about the longest amount of time between starpower phrases with fifteen seconds being the average distance between starpower phrases.
> 
> A loose guideline is that starpower phrases are often near the beginnings or ends of "sections" (eg right before or after a song is about to change up). There is usually an "omf" to the song where a starpower phrase ends
> 
> ExileLord
## "Do"s and "Don't"s
**Do:**

* Have accurate tempo mapping
* “Correct” note placement (i.e., higher notes are higher frets, chords are chords, etc.)
* Star Power, practice sections, appropriate leading silence
* Tap notes where applicable
* Relatively complete metadata, (i.e., nothing glaringly missing)
* Bearable audio, quality-wise

**Don’t:**

* Charting of vocals or drums*
* Abuse of extended sustains that don't make sense
* Use song offset
* Usage of 4 or 5-note chords*
* No abuse of GRO, GYO, or GBO chords*
## Tempo Mapping
Tempo Mapping is the process of matching the beat lines in a chart to varying tempo in the music. 
## Sections
Sections allow the player to practice certain portions of a chart. 
## Difficulties
Difficulties allow players of different skill levels to play at their level.

A good way to chart lower difficulties is to copy the expert to the hard and simplify. Then copy down again. This way, no difficulty should (ideally) be harder than the difficulty above it.
### Expert
Expert Difficulty is the hardest, and is not undercharted to make it easier to play. It uses all 5 frets + Opens to play.
### Hard
Hard Difficulty is easier to play than expert. Rhythms are simplified, and some sections are recharted to make it easier to play. Some harder to hear notes are removed, and articulations and special ornaments are removed. 3 note chords become 2 note chords, and some quick chords (of any kind) become single notes. Some extended sustains become non-sustains. It uses all 5 frets + Opens to play.
### Medium
Medium is the second easiest to play. Rhythms are even more simplified, and there are generally only 1/2 the notes from expert. Chords are simplified, and some quick chords (of any kind) become single notes. Some extended sustains become non-sustains. It uses only the first 4 frets to play.
### Easy
Easy is the easiest to play. Rhythms are even more simplified, and there are generally only 1/4 the notes from expert. Chords become single notes, and some extended sustains become non-sustains. It uses only the first 3 frets to play.
## Lyrics
Lyrics show in-game and are timed to the music, ideally timed to the syllable.
## Drums
### 4-Lane
### 5-Lane
## Techniques
### Looping
Looping is a technique to chart scales that are more than 5 notes (the 5 frets).

For example, in an 8-note scale, a common loop is `G R Y B R Y B O`.
# What goes with a chart?
Along with your chart (`notes.chart / notes.mid`) and audio (`song.mp3 / song.ogg`), you should also have a metadata (`song.ini`) and album art (`album.png / album. jpg`). 
## File Formats
Accepted chart formats:
* .chart
* .mid
Accepted audio formats:
* .ogg
* .mp3
Accepted album art formats:
* .png
* .jpg
## song.ini Metadata
The song.ini provides metadata for the song, including name and artist.

The first line of the file should be `[song]`. Each parameter has its own line. To set a parameter, put it in this format (in this example, the name is set):
`name = Soulless 4` (spaces optional)
#### Required Field
```
name
```
#### Suggested Fields
```
album
genre
year
charter
```
#### Instrument Difficulties
Difficulties are set on a range from 0 to 6.
> 0 - Very easy, almost definitely a sightread FC for any Expert players (ex. Closer, Monsoon, How You Remind Me)
> 1 - Still pretty easy, but might have a bit more variation throughout the song (Radio Song, Rooftops, Again)
> 2 - Relatively easy, there might be a solo or passage that most players will have difficulty with (School's Out, Dammit, Cherry Bomb)
> 3 - Bit more challenging, will keep most players on their toes, but manageable (Even Flow, The Kill, Aqualung)
> 4 - Consistently tricky throughout, easy to miss if you lose focus (Monsters, La Bamba, Bat Country)
> 5 - Would be in or close to the final tier for most GH/RB games (Cult of Personality, Overkill, Burn)
> 6 - DragonForce-levels of difficult or harder, would be un-FC'able for 99% of players (One, Satch Boogie, Black Widow of La Porte)
```
diff_guitar
diff_bass
diff_guitar_coop 
diff_rhythm 
diff_drums
diff_vocals
diff_keys 
diff_dance
diff_band
diff_guitarghl
diff_bassghl
diff_guitar_real
diff_bass_real 
diff_keys_real
diff_drums_real
diff_guitar_real_22
diff_bass_real_22
```
#### Additional Information
```
delay
playlist_track
preview_start_time
icon
album_track
video_start_time
five_lane_drums
```
#### Example
An example song.ini looks like:

```text
[song]
name=Never Look Back
artist=Andrew Huang
album=Love & Desolation
genre=Pop
year=2012
diff_band=-1
diff_guitar=2
diff_rhythm=4
diff_bass=0
diff_drums=-1
diff_keys=0
diff_guitarghl=-1
diff_bassghl=-1
preview_start_time=86016
icon=wyskoj
album_track=3
playlist_track=3
video_start_time=0
charter=wyskoj
delay=0
song_length=276462
```
## Album Art
Album art should be either a PNG or JPEG and named `album`. The picture will be rescaled to 1:1, so try to put in a square image to prevent squishing.
## How to Package
When you feel your chart is ready to be published, it is important to package it correctly. Following these steps ensures a good package.
1. Ensure the following files are in an appropriately named (the song name) folder: `notes.chart/mid`, `song.ogg/mp3`, `album.png/jpg`, and `song.ini`.
2. In your archiving software (7zip, WinRAR), archive **the folder and not just the files**. This is so that when people download your song, they don't have to make an extra step to put it in a folder. *The .7z format provides the highest level of compression and can only be made in 7Zip, although it can be extracted in WinRAR.*
