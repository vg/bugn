# Table of contents #



# What is tiling window management? #

From Wikipedia, the free encyclopedia:

"In computing, a tiling window manager is a window manager with an organization of the screen into mutually non-overlapping frames, as opposed to the more popular approach of coordinate-based stacking of overlapping objects (windows) that tries to fully emulate the desktop metaphor."

# What is a shell replacement? #

From Wikipedia, the free encyclopedia:

"In Windows 95 and later versions of Microsoft Windows, the Windows shell is by default explorer.exe (in the Windows folder or one of its subfolders, System32) which displays the icons on the desktop, the taskbar, the Start menu and the file browser. By default, explorer.exe runs automatically when Windows starts. Mostly the shell simply launches other programs on request."

# What is an EWMH compliant window manager? #

From Wikipedia, the free encyclopedia:

"Extended Window Manager Hints, aka NetWM or Net WM, is an X Window System standard for window managers. It defines various interactions between window managers, utilities, and applications, all part of an entire desktop environment. It builds on the functionality of the Inter-Client Communication Conventions Manual (ICCCM)."

Therefor an EWMH compliant window manager is a window manager, that complies to the EWMH standard. You may find examples of EWMH compliant window managers on Wikipedia with the search string "Comparison of X window managers"; i. a. Openbox and those for the desktop environments GNOME, KDE and XFCE.

# What is tagging? #

From wmii.suckless.org/intro:

"The classical workspace model conceives the workspace as a(n exclusive) collection of clients, thus you can start clients on each workspace and move them from one workspace to another. The window manager can only show one workspace at time, so to reach your clients you have to switch between workspaces.

Additional operations that are performed in workspaces of classical window managers:

  * Hide/Show
  * Maximize/Minimize: give/retain all the screen to a client
  * Move client to ws: moves a client to a different ws
  * Sticky/Non Sticky: makes a client visible in all ws

Tagging is a more general concept that supersedes the classical workspace model.

Here is a brief overview of wmii’s tagging model:

  * A tag is an alphanumeric string which is associated with one or more clients.
  * A view is a set of clients matching a specific tag.

Tagging is defined by the dictionary as: attach a tag or label to something, in this particular case to clients. This way a client belongs to a set of classes.

This way a workspace is not a set of clients but a set of tags. This enables to:

  * have clients with one tag (so they only appear in one view exclusively).
  * have clients with multiple tags (so they appear in different views, sticky)."

# What does the name "bug.n" mean? #

bug.n means tiling window management. It is a play on words.
| tiling window management |
|:-------------------------|
| kachelndes Fenster-Management | ↵ translated into german |
| KFM                      | ↵ the acronym            |
| ka.ef.em                 | ↵ the letters vocalized in german |
| ka.ef.ern                |	↵ typo                   |
| kaefer.n                 | ↵ reordered              |
| bug.n                    | ↵ translated back into english |

Therefor the icon of bug.n also consists of the letters "K", "F" and "M".

# What do I need to run bug.n 3.5.1 for Windows **as an AutoHotkey script? #**

You need (1) the AutoHotkey source in the desired version, which is supplied as a .zip file in the download directory and (2) the AutoHokey package (version > 1.0.47.06) from autohotkey.com. If all is unpacked, run the file bugn.ahk with autohotkey.exe.

# What do I need to run bug.n xvkbd 1.0 for **n?x/**BSD? #

bug.n xvkbd for **n?x/**BSD is packaged as a ROX application and written in python utilizing libwnck. Therefor the following packages have to be installed on your system additionally to a X window system:

| package | tested version |
|:--------|:---------------|
| ROX filer |	2.7.1-1        |
| ROX Lib2 | 2.0.5          |
| python  | 2.5.2          |
| python-wnck (including the library for libwnck) | 1.18           |
| EWMH compliant window manager | Openbox 3.4.7.2 |

You than need to download and unpack the .tgz file supplied in the download directory, start a ROX panel and drag the bug.n application directory from ROX file to the ROX panel.