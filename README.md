# winCapturesDeleted-Fix
Just a small bit of code I made to smooth out windows changing the gamebar captures directory to AppData/Local/Temp for some reason.

## It is reccomended you keep these files in this folder and set `capture.ahk` to run on startup:
#### 1. Select and copy `capture.ahk`.
#### 2. Press `Win + R` to open the Run dialogue.
#### 3. Enter `shell:startup` (or `shell:common startup` to apply to all profiles)
#### 4. Paste `capture.ahk` into the `Startup` folder.

# Two small things you will want to change:
### 1. Captures folder directory
You will want to change the `captures_folder` variable in `move_captures.py` to whatever your folder is.

### 2. Hotkey
You will probably also want to change the hotkey in `capture.ahk`(default: `Alt + S`) to whatever your screen capture hotkey is, assuming it's something besides the default.

You will do this by changing the value before the :: (see comments in script) to whatever your keybind, in accordance with autohotkey's key value rules. https://www.autohotkey.com/docs/Hotkeys.htm          <-- list of key prefixes
https://www.autohotkey.com/docs/KeyList.htm#general  <-- list of general keys
