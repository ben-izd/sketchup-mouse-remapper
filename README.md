# sketchup-mouse-remapper
Remap Sketchup default keys for orbit &amp; pan with middle mouse button.

This solution works on **only windows** and **only in Sketchup**.

|  Action  |  Before (sketchup default)  | After running script |
| ------------- | ------------- | ------------- |
|  Orbit  |  middle mouse  |  alt + middle mouse  |
|  Pan  |  shift + middle mouse  |  middle mouse  |

if you don't want to change the keystrokes or script, just download "3ds_max_keystrokes.exe" file and run it on your windows.  
After running script (whether .exe or .ahk version) an "H" icon will be added to your taskbar:

![Taskbar after running script](https://img.imageupload.net/2020/09/19/2020-09-19_14-43-07.jpg)

For pausing/existing the script, just right click on "H" icon in taskbar and choose "Pause Script"/"Exit":  
If you exit the script, you should re-run the file for activating remmaping.

![Script Options](https://img.imageupload.net/2020/09/19/2020-09-19_14-42-23.jpg)

If you want to change, develope or access to script code download "Sketch_mouse_remapper.ahk".
You'll need [autohotkey](https://www.autohotkey.com/) for running the script.

## For advance users:
For changing the script, first open the script file (".ahk" version) in a text editor:
- If you want to make this keystroke available everywhere not just in sketchup, remove the first line "*if WinExist("ahk_exe SketchUp.exe")*".

- if you want to change the keystroke for orbiting, change last line "!" to your taste accroding to the symbols table.

### symbols table:
|  Symbol  |  keystroke  |
| ------------- | ------------- |
|  ^  |  Control (ctrl)  |
|  +  |  Shift |
|  !  |  Alt  |

For more information check [autohotkey documentation](https://www.autohotkey.com/docs/AutoHotkey.htm).
