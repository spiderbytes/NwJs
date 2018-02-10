# NwJs

Several SpiderBasic-Modules for NW.js (https://nwjs.io/)

### NwJsWin

The NwJsWin-Module contains a set of commands to interact with the NwJs-Window:

(For further informations visit: <a href="http://docs.nwjs.io/en/latest/References/Window/" target="_blank">http://docs.nwjs.io/en/latest/References/Window/</a>)

`SetX(X.i, Window = #PB_Ignore)`

Sets the x-Position of the current window.

`GetX(Window = #PB_Ignore)`

Gets the x-Position of the current window.

`SetY(Y.i, Window = #PB_Ignore)`

Sets the y-Position of the current window.

`GetY(Window = #PB_Ignore)`

Gets the y-Position of the current window.

`SetWidth(Width.i, Window = #PB_Ignore)`

Sets the width of the current window.

`GetWidth(Window = #PB_Ignore)`

Gets the width of the current window.

`SetHeight(Height.i, Window = #PB_Ignore)`

Sets the height of the current window.

`GetHeight(Window = #PB_Ignore)`

Gets the height of the current window.

`MoveTo(X.i, Y.i, Window = #PB_Ignore)`

Moves a windows left and top edge to the specified coordinates.

`MoveBy(X.i, Y.i, Window = #PB_Ignore)`

Moves a window a specified number of pixels relative to its current coordinates.

`ResizeTo(Width.i, Height.i, Window = #PB_Ignore)`

Resizes a window to the specified width and height.

`ResizeBy(Width.i, Height.i, Window = #PB_Ignore)`

Resizes a window by the specified amount.

`SetTitle(Title.s, Window = #PB_Ignore)`

Sets the window title.

`GetTitle(Window = #PB_Ignore)`

Gets the window title.

`Focus(Window = #PB_Ignore)`

Sets the focus on the window.

`Blur(Window = #PB_Ignore)`

Moves focus away.

`Show(IsShow = #True, Window = #PB_Ignore)`

Shows the window

`Hide(Window = #PB_Ignore)`

Hides the window

`Close(Force = #False, Window = #PB_Ignore)`

Closes the window.

`Reload(Window = #PB_Ignore)`

Reloads the current window.

`ReloadIgnoringCache(Window = #PB_Ignore)`

Like `Reload()`, but don't use caches (aka "shift-reload").

`Maximize(Window = #PB_Ignore)`

Maximize the window on GTK and Windows, and zoom the window on Mac OS X.

`Unmaximize(Window = #PB_Ignore)`

Unmaximize the window, i.e. the reverse of `Maximize()`.

`Minimize(Window = #PB_Ignore)`

Minimize the window to task bar on Windows, iconify the window on GTK, and miniaturize the window on Mac OS X.

`RestoreWin(Window = #PB_Ignore)`

Restore window to previous state after the window is minimized, i.e. the reverse of `Minimize()`.

`EnterFullscreen(Window = #PB_Ignore)`

Make the window fullscreen.

`LeaveFullscreen(Window = #PB_Ignore)`

Leave the fullscreen mode.

`ToggleFullscreen(Window = #PB_Ignore)`

Toggle the fullscreen mode.

`EnterKioskMode(Window = #PB_Ignore)`

Enter the Kiosk mode. In Kiosk mode, the app will be fullscreen and try to prevent users from leaving the app, so you should remember to provide a way in app to leave Kiosk mode. This mode is mainly used for presentation on public displays.

`LeaveKioskMode(Window = #PB_Ignore)`

Leave the Kiosk mode.

`ToggleKioskMode(Window = #PB_Ignore)`

Toggle the kiosk mode.

`GetPrinters(Callback, Window = #PB_Ignore)`

Enumerate the printers in the system. The callback function will receive an array of JSON objects for the printer information. The device name of the JSON object can be used as parameter in `Print()`.

`Print(Options = #PB_Ignore, Window = #PB_Ignore)` 

Print the web contents in the window with or without the need for users interaction. 

`SetMaximumSize(Width.i, Height.i, Window = #PB_Ignore)`

Set windows maximum size.

`SetMinimumSize(Width.i, Height.i, Window = #PB_Ignore)`

Set windows minimum size.

`SetResizable(Resizable, Window = #PB_Ignore)`

Set whether window is resizable.

`SetAlwaysOnTop(Top, Window = #PB_Ignore)`

Sets the widget to be on top of all other windows in the window system.

`ShowDevTools()`

Open the devtools to inspect the window. Note, that this feature is only available with the nwjs-SDK.

`CloseDevTools()`

Close the devtools window.


### NwJsFs

The NwJsFs-Module contains a set of commands to access the filesystem:

[ToDo]

### NwJsOs

The NwJsOs-Module contains a set of commands to get OS-Informations:

[ToDo]

### NwJsRequester

The NwJsRequester-Module contains a set of commands to call Requester:

[ToDo]

### NwJsClipboard

The NwJsClipboard-Module contains a set of commands to access the clipboard:

[ToDo]

## License

[MIT](https://github.com/spiderbytes/NwJs/blob/master/LICENSE)
