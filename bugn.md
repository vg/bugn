# What is bug.n? #

bug.n is a tiling window manager.


# What is tiling window management? #
→ Please refer to the "Q & A" file.

The benefit of tiling window management is, that managed windows are not overlapping and the screen space is used to the maximum.
bug.n is completely controlled by keyboard; therefor you do not have to move and resize windows manually by mouse, but by hotkeys, which is done more easily and precisely.

Tags: software / GPL / tiling window management

# Description #

bug.n is a tiling window manager for Microsoft Windows. With bug.n you can quickly move and resize single windows to specific positions and sizes, or group them and arrange all windows of the group on the screen using all available space.

It works as an add-on to the Windows window manager and asks it to move and resize windows using the Windows API; it is not a shell replacement. The features and UI are similar to the Snap feature of Windows 7, but are extended with the following:

  * Hiding Windows design elements (Windows task bar, window borders, window title bars)
  * Providing a small bar as a replacement (showing amongst others the current date, time and active window)
  * Grouping windows (providing group actions: arrange, maximize, miniize, hide, close)
  * Horizontal layouts

The UI is fully defined by the file Config.ahk in the bug.n source directory (which is not visible using the precompiled executable). Beside these descriptions of the bar by configuration variables, the bar contains (from left to right) the folowing elements:

  * Monitor (the active monitor is differently coloured)
  * Groups (the active group and the number of windows are differently coloured)
  * Active window title
  * Battery status
  * CPU load
  * Date
  * Time