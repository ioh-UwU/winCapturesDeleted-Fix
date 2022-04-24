# winCapturesDeleted-Fix
small bit of code I made to smooth out windows changing the gamebar captures directory to AppData/Local/Temp for some reason

Two small things you will want to change:
### 1. Captures folder directory
You will want to change the `captures_folder` variable in `move_captures.py` to whatever your folder is.

### 2. Hotkey
You will probably also want to change the hotkey in `capture.ahk` to whatever your screen capture hotkey is, assuming it's something besides the default.
