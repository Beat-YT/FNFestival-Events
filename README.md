# Fortnite Festival Text Events

This is a brief documentation of the events in Fortnite Festival midis.

## EVENTS

The events track must start with the text event `EVENTS`

Used to identify parts of the song:

- `[music_start]`: Defines when the song should start (quietens crowd).
- `[music_end]`: Defines when the song should end (starts crowd cheering).
- `[preview]`: Defines when the song preview starts (unused by client).
- `[end]`: Defines when the song ends and the score screen should appear.

## ALL PARTS

A part track must start with the text event `PART X` (with X being the name of the instrument)

Events that apply to a specific instrument:

- `[idle_realtime]`: Sets the player animation to idle (not in sync with the beat).
- `[idle_mellow]`: Sets the player animation to a slow idle.
- `[idle_intense]`: Sets the player animation to an intense idle.
- `[idle]`: Sets the player animation to idle.
- `[mellow]`: Sets the player animation to a slow, mellow performing animation.
- `[play]`: Sets the player animation to the standard performing animation.
- `[intense]`: Sets the player animation to an intense performing animation.
- `[pickup]`: To be determined.

## GUITAR

The lead part must starts with the text event `PART GUITAR`

Events that only apply to the lead instrument:

- `[guitar]`: Changes the lead instrument to a guitar.
- `[keytar]`: Changes the lead instrument to a keytar.
- `[map StrumMap_Default]`: Changes how the left hand animates to play notes.
- `[map HandMap_Default]`: Changes how the right hand animates to play notes.
- `[map HandMap_Chord_X]`: Moves the right hand to play the X chord.

## DRUMS

The drums part must starts with the text event `PART DRUMS`

Events that only apply to the drums instrument:

- `[mix X drumsY]`: Change X and Y, e.g., `[mix 3 drums0d]`; Uncertain, but presumably assigns a lane to a drum instrument (for animating/audio muting).

## VOCALS

The vocals part must starts with the text event `PART VOCALS`

Events that only apply to the vocals instrument:

- `[keytar]`: Changes the vocals instrument to a keytar.

## SECTION

The section track must starts with the text event `SECTION`

The section is an optional track that contains events identifying the [structure of the song](https://www.masterclass.com/articles/songwriting-101-learn-common-song-structures).
The game currently uses some of these to direct where the camera will focus during the performance, to change the colour of the stage, and to trigger different visual effects (bubbles, fire, sparks, etc).

- `[intro]`
- `[verse]`
- `[build]`
- `[chorus]`
- `[prechorus]`
- `[breakdown]`
- `[bridge]`
- `[drop]`
- `[solo_guitar]`
- `[solo_drums]`
- `[solo_voice]`
- `[solo_bass]`
- `[outro]`
