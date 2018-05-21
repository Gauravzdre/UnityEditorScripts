# Unity Editor Scripts
Collection of simple Unity editor scripts written to improve workflow and learn C# and Unity editor scripting at the same time.

## Editor Scripts
These scripts work when they are located in an Editor folder in a Unity project.

### Capture
For capturing screenshots.
Menu item is located under Tools menu.

![Capture Menu](https://github.com/korintic/UnityEditorScripts/blob/master/Images/CaptureMenu.png "Capture.cs and CaptureWithHotkey.cs")

Capture Options menu item is for changing preferences and taking screencaptures.
Capture is for taking screencaptures with a hotkey using the current preferences set.

![Capture Options](https://github.com/korintic/UnityEditorScripts/blob/master/Images/CaptureOptions.png "Capture.cs")

**Hotkey** Capture Options Ctrl+Shift+W
**Hotkey** Capture Ctrl+W

TO DO:
- [ ] See if the code can be simplified/ cleaned up
- [ ] Reorganize where adding the file extension happens 
- [ ] Saving Editorprefs seemed to not work right all the time. Check where getting and setting them makes sense.
- [x] Make a version that captures screenshots with a hotkey based on the preferences set
- [ ] Add option to capture from SceneView

### ToggleSelection
For toggling object selection between none and all.
If something is selected deselects it and if nothing is selected selects everything.
Menu item is located under the Edit menu.

**Hotkey** Ctrl+Shift+A

### SceneViewParent
For parenting objects while working in the SceneView.
Parents selected objects to the active object when SceneView is the active view.

**Hotkey** Ctrl+F
