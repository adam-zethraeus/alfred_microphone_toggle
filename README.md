# Alfred Microphone Toggle

![microphone icon](https://github.com/adam-zethraeus/alfred_microphone_toggle/blob/mainline/readme_resources/icon.png?raw=true)

An Alfred workflow which toggles the system microphone input.
This mutes your microphone in all apps.

The workflow:
  * Has a system hotkey trigger
  * Has an alfred keyword trigger
  * Posts the new mute/unmute state as a system notification

![mute notification](https://github.com/adam-zethraeus/alfred_microphone_toggle/blob/mainline/readme_resources/notification_mute.png?raw=true)
![unmute notification](https://github.com/adam-zethraeus/alfred_microphone_toggle/blob/mainline/readme_resources/notification_unmute.png?raw=true)

The workflow uses a compiled NSAppleScript executed from Alfred's main thread (and not a `/bin/osascript` call) to execute as fast as possible.

![workflow screenshot](https://github.com/adam-zethraeus/alfred_microphone_toggle/blob/mainline/readme_resources/workflow_screenshot.png?raw=true)

