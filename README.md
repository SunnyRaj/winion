# Winion
An AutoHotKey script for Windows that lets a user change virtual desktops using keyboard shortcuts inspired by [Notion / Ion3](http://notion.sourceforge.net/) and [Vim](http://vimsheet.com/images/hjkl.png).

## Overview
This is forked from [pmb6tz](https://github.com/pmb6tz/windows-desktop-switcher), but with modified mappings to match Notion.

This script creates 'better' hotkeys for switching virtual desktops in windows 10. I built this to better mirror
the mapping Notion / Ion3 provides.

## Installation
Install AutoHotKey, then run the desktop_switcher.ahk script (open with AutoHotKey if prompted). I would recommend putting it in your startup folder and it'll be invoked on login.

## Hotkeys
### Virtual desktops
        <Alt> + <Num>           - Switches to virtual desktop "num"
        <Alt> + ,               - Switch to virtual desktop on left
        <Alt> + .               - Switch to virtual desktop on right
        <Alt> + c               - Create a new virtual desktop
        <Alt> + x               - Delete the current virtual desktop

### Window layout

![](An AutoHotKey script for Windows that lets a user change virtual desktops using keyboard shortcuts inspired by [Notion / Ion3](http://notion.sourceforge.net/) and [Vim](http://vimsheet.com/images/hjkl.png).

        <Alt> + h               - Send window left.
        <Alt> + j               - Send window down.
        <Alt> + k               - Send window up.
        <Alt> + l               - Send window right.

## Todo
- Resize tiles

## Other
To see debug messages, download [SysInternals DebugView](https://technet.microsoft.com/en-us/sysinternals/debugview).
