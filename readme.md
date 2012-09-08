# Windows NT Tweaks

A selection of defaults for when I'm using a Windows box. I think of it as my Dotfiles equivalent for things with the NT kernel and Explorer.

Designed for and tested on Windows 7.

## Features

### Machine-Level Tweaks

These tweaks operate on the system and will affect all users.

* Disables automatic reboot when a user is logged in
* Enables verbose startup/shutdown messages (e.g. "Shutting Down Windows Update service ...")
* Disables Flip 3D
* Disables "Use the Web service to find the correct program" prompt for unknown file types.
* Disables Aero Shake (Hide all other windows when shaking foreground window)

### User-Level Tweaks

These tweaks operate for the currently logged in user only.

*   Adjusts Alt+Tab switcher size for larger screens
*   Explorer defaults
    *   Disable hover delay on taskbar previews
    *   Show hidden files and all file extensions
    *   Run Explorer windows in separate process
    *   Disable Sharing Wizard
    *   Disable Aero Peek for desktop
    *   Large icons in taskbar
    *   Taskbar on grouping with no label setting
*   Start menu defaults
    *   Show Computer as menu
    *   Hide Network Connections
    *   Hide Program Access and Defaults
    *   Hide Printers
    *   Show Downloads as link
    *   Hide Music
    *   Show Network as link
    *   Show User as link
    *   Show Pictures as link
    *   Hide Run (You can use "search programs and files" for this anyway
    *   Show Videos as link
    *   Don't show Administrative Tools in the root
    *   Hide Games
    *   Hide Help

## Requirements

* Windows 7

Note that many of these tweaks will operate and take effect on Windows 2000 or later. Version-specific tweaks may be marked or conditionally enabled in a later version.

## Setup

1.  Clone repository using your favoured git tool for Windows
2.  Run each reg file from Explorer
3.  Restart your computer

## Todo

*   Create a bootstrapping script to run all this stuff automatically, and allow selection of user/system tweaks
*   Maybe add version detection to conditionally enable portions of the script