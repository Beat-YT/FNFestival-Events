# Fortnite Festival Text Events

This is a little documentation for the events in fortnite festival midis

## SECTION

Section is an optional track that only contains events that identifies the [structure of the song](https://www.masterclass.com/articles/songwriting-101-learn-common-song-structures)

- `[intro]`
- `[verse]`
- `[build]`
- `[chorus]`
- `[prechorus]`
- `[breakdown]`
- `[bridge]`
- `[drop]`
- `[solo_bass]`
- `[solo_voice]`
- `[solo drums]`


## EVENTS

Used to identify parts of the song
- `[music_start]` Define when the song should start
- `[music_end]` Define when the song should end
- `[preview]` Set the time that should be used in the song picker device

# ALL PARTS

Events that applies to a specific instrument
- `[idle]` Set to to idle
- `[idle_mellow]` Set to idle, but with mellow animation
- `[idle_realtime]` To be determined
- `[intense]` Set the player animation
- `[mellow]` Set the player animation
- `[play]` Not sure, my guess is that is resets to the default animations


## GUITAR

Events that only applies to the lead instrument

- `[guitar]` change the LEAD instrument to a guitar
- `[keytar]` change the LEAD instrument to a keyboard
- `[map StrumMap_Default]` To be determined. Used for the plastic guitar
- `[map HandMap_Default]` To be determined
- `[map HandMap_Chord_X]` (Replace X with the Chord) To be determined

# DRUMS

Events that only applies to the drums instrument
- `[mix X drumsY]` (change X and Y. e.g: [mix 3 drums0d])  Not sure, my guess is assign a key column to a drum instrument

