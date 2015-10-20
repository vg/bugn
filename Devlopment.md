# Table Of Contents #


# Development status #

There is no active developed version of bug.n – codename "aschebescher" aka "ashtray".

Possibly there will be a new version of bug.n for Windows **written in the AutoHotkey scripting language – codename "phoenix".**

# Older versions #

There are multiple versions of bug.n with different concepts and for different platforms, which are still available through the "download" directory. These include stable and development (pre-alpha) versions. Notedly there are the following stable versions:

## bug.n for Windows **version 3.5.1 ##**

This version, which is written in the AutoHotkey scripting language, is a clone of dwm 5.2, a dynamic window manager for the X window system. The features include the following:

  * managing windows in tiled (vertical and horizontal), grid, monocle and floating layout
  * dynamically applying layouts (on opening and closing windows)
  * changing the window in the master area
  * setting windows in floating state
  * excluding windows from tiling
  * changing the tray icon, if the layout is changed
  * grouping windows by multiple tags
  * displaying all available tags (the active tag in a different color), the layout, the active window title and system status information in a bar (speaker volume, battery status, cpu load, date and time)

## bug.n xvkbd for **n?ix /**BSD version 1.0 ##

bug.n xvkbd, which is written in Python with the help of wnck and ROX filer, makes tiling window management available on X window systems without keyboard, but mouse or pen input.

For this to work it needs an EWMH compliant window manager. With title bars and the click-to-focus model – in contrast to dwm 5.2 – it is possible to use a virtual keyboard like xvkbd, replacing the missing keyboard.
It creates an icon in a ROX panel indicating the current layout and providing a menu for accessing the window management functions, options and help. The features include the following:

  * predefined layouts: tiled (vertical and horizontal), grid, monocle and floating
  * resizable master area
  * changing the window in the master area
  * setting windows in floating state
  * auto-arranging windows when windows are opened or closed
  * customizing the working area
  * excluding windows from tiling
  * changing the applet icon, if the layout is changed

## bug.n ASDF version 1.0.1 (cross-platform) ##

bug.n ASDF, which is written in Java, is a cross-platform version for Windows **and**n?ix / **BSD. The features include the following:**

  * managing windows by manually applying them to patterns
  * the patterns are deck (one window visible), stack (all windows visible) and floating (only the position is adjusted)
  * exclusions of windows from tiling are not neccessary
  * hiding windows by applying the "nil" pattern
  * multi-monitor support
  * displaying the active monitor and pattern and system status information in a bar (battery status, date and time)