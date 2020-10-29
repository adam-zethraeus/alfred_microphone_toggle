# Alfred Microphone Toggle

An Alfred workflow which toggles the system microphone input.
This mutes your microphone in all apps.

The workflow:
  * Has a system hotkey trigger
  * Has an alfred keyword trigger
  * Posts the new mute/unmute state as a system notification

The workflow uses a compiled NSAppleScript executed from Alfred's main thread (and not a `/bin/osascript` call) to execute as fast as possible.

