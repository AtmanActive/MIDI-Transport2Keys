# MIDI-Transport2Keys

Windows MIDI Mackie Universal Control transport Stop&amp;Play events translated to keypresses.

This program connects to a MIDI port and listens for Mackie Universal Control MIDI transport messages STOP and PLAY. When Mackie PLAY is received, a keypress F14 is issued, and, when Mackie STOP is received, a keypress F16 is issued. This is useful to have Mumble mute or deafen self automatically depending on DAW transport state.

Built with [AutoHotKey](https://www.autohotkey.com/) with the little help of [AutoHotkey-Midi](https://github.com/dannywarren/AutoHotkey-Midi)

Compiled EXE available in releases.

