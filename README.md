# Fortnite Festival Text Events

This is a brief documentation of the events in Fortnite Festival midis.

## EVENTS

Used to identify parts of the song:

- `[music_start]`: Defines when the song should start.
- `[music_end]`: Defines when the song should end.
- `[preview]`: Unused tag, related to preview

## ALL PARTS

Events that apply to a specific instrument:

- `[idle]`: Sets the instrument to idle.
- `[idle_mellow]`: Sets the instrument to idle with a mellow animation.
- `[idle_realtime]`: To be determined.
- `[intense]`: Sets the player animation to intense.
- `[mellow]`: Sets the player animation to mellow.
- `[play]`: Uncertain, but presumably resets to default animations.

## GUITAR

Events that only apply to the lead instrument:

- `[guitar]`: Changes the lead instrument to a guitar.
- `[keytar]`: Changes the lead instrument to a keyboard.
- `[map StrumMap_Default]`: To be determined. Used for the plastic guitar.
- `[map HandMap_Default]`: To be determined.
- `[map HandMap_Chord_X]`: Replace X with the chord; To be determined.

## DRUMS

Events that only apply to the drums instrument:

- `[mix X drumsY]`: Change X and Y, e.g., `[mix 3 drums0d]`; Uncertain, but presumably assigns a key column to a drum instrument.


## SECTION

The section is an optional track that contains events identifying the [structure of the song](https://www.masterclass.com/articles/songwriting-101-learn-common-song-structures).
It looks like this is not yet used by the game as of now.

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
- `[solo_drums]`
