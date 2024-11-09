# MIDI-Transport2Keys



There is a newer, more efficient AutoHotKey-v2 version of this app, focused solely on input-audio-device-muting/umuting here:

[MIDI-Transport-to-Mute](https://github.com/AtmanActive/MIDI-Transport-to-Mute).





Windows MIDI Mackie Universal Control transport Stop&amp;Play events translated to keypresses.

This program connects to a windows MIDI port and listens for Mackie Universal Control MIDI transport messages STOP and PLAY. 

When Mackie PLAY is received, a keypress F14 is issued, and, when Mackie STOP is received, a keypress F16 is issued. 

This is useful to have [Mumble](https://www.mumble.info) mute or deafen self automatically depending on [DAW](https://reaper.fm) transport state.

Built with [AutoHotKey](https://www.autohotkey.com/) with the little help of [AutoHotkey-Midi](https://github.com/dannywarren/AutoHotkey-Midi)

Compiled EXE available in releases.

version 1.2 now supports [controlling a windows audio device](https://www.nirsoft.net/utils/sound_volume_view.html) in addition to sending keypresses.

In order to use this feature: run [SoundVolumeView](https://www.nirsoft.net/utils/sound_volume_view.html) on your computer and find the audio device you want to control. Now right-click on the device and choose `Copy item ID`, then paste that ID into `MIDI-Transport2Keys.ini` section `[Audio]`, parameter `audio_device_id`.

