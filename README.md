# Winion
An AutoHotKey script for Windows that lets a user change virtual desktops using keyboard shortcuts similar to [Notion / Ion3](http://notion.sourceforge.net/).

## Overview
This is forked from [pmb6tz](https://github.com/pmb6tz/windows-desktop-switcher), but with modified mappings to match Notion.

This script creates 'better' hotkeys for switching virtual desktops in windows 10. I built this to better mirror
the mapping Notion / Ion3 provides.

## Installation
Install AutoHotKey, then run the desktop_switcher.ahk script (open with AutoHotKey if prompted). I would recommend putting it in your startup folder and it'll be invoked on login.

## Hotkeys
        <Alt> + <Num>           - Switches to virtual desktop "num"
        <Alt> + ,               - Switch to virtual desktop on left
        <Alt> + .               - Switch to virtual desktop on right
        <Alt> + C               - Create a new virtual desktop
        <Alt> + D               - Delete the current virtual desktop

## Todo
- Fullscreen shortcut, application specific: Alt + Return
- Split screen, resize tiles
- [More shortcuts of Notion](http://notion.sourceforge.net/notionkeys.html)

## Other
To see debug messages, download [SysInternals DebugView](https://technet.microsoft.com/en-us/sysinternals/debugview).
