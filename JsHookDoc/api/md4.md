# media

Used for playing music.

## media.create(data)

Create a media instance.

**Parameters**:

`data`: string - URL address or file base64 value.

**Returns**: object - Media instance.

Calling this function automatically starts playback; no need to call `start`.

## [instance].start()

Start playing the media.

## [instance].pause()

Pause the media playback.

## [instance].stop()

Stop the media playback.

## [instance].loop(state)

Set whether the media should loop.

**Parameters**:

`state`: boolean - Whether to loop playback. Defaults to `false` (play once).

## media.closeAll()

Close all media instances.