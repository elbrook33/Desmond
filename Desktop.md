Desmond - instructions manual
=============================

Mouse clicks
------------
* Left-click: opens an app or previews a document.
* Shift-click: selects up to four apps to show side-by-side (for two or three) or in a grid (for four).
* Shift-click: selects up to two folders to show one below the other.

Keyboard shortcuts
------------------
* Meta: show/hide the app and document browser.
* Meta-A: switch to Apps.
* Meta-D: switch to Documents.
* Meta-number: switch workspace (0 through 9).
* Meta-tab, Meta-shift-tab: switch between open windows.


Tree
====

* Apps -> *.desktop, folders (bin/lib/share -> usr/local or execs/...), open windows
* Documents -> Downloads/Pictures/Videos...
* Drives -> Thumb drive 1/...
* Sandboxes -> User -> App1/App2/... -> .cache/.config/.local/...
* Software -> User -> Local/Ubuntu/... -> bin/include/...
* System -> Booting/Configuration/Controls/Data/Tools
* Trash -> User 1/...


An idea for a desktop
=====================

V. similar to "Desmond" idea from a year ago. Starts from the left, a file browser; then an app list; then an app panel.

Differences from that version:
* Top-level items are icons.
* Animations (slide in from right) and shadows.
* No right panel (task switching entirely from app list).
* Shades of beige/goldenrod instead of grays.
* Sandboxing.

```
+------+-----------------+-------------------------------+
| .--. | Running         |                               |
| |--| | =======         |                               |
| '--' |*Dashboard       |                               |
| Apps | Scribus         |                               |
|      | System Settings |                               |
| .--. |                 |                               |
| |  | | Favourites      |                               |
| '--' | ==========      |                               |
| Docs | Firefox         |                               |
|      | Thunderbird     |                               |
| .--. |                 |                               |
| |  | | All             |                               |
| '--' | ===             |                               |
| Drvs | Dashboard       |                               |
|      | Firefox         |                               |
| .--. | Gimp            |                               |
| |  | | Scribus         |                               |
| '--' | System Settings |                               |
| Sand | Thunderbird     |                               |
|      | VLC             |                               |
| .--. |                 |                               |
| |  | |                 |                               |
| '--' |                 |                               |
| Soft |                 |                               |
|      |                 |                               |
| .--. |                 |                               |
| |  | |                 |                               |
| '--' |                 |                               |
| Syst |                 |                               |
|      |                 |                               |
| .--. |                 |                               |
| |  | |                 |                               |
| '--' |                 |                               |
| Trsh |                 |                               |
+------+-----------------+-------------------------------+

                         ^
                         |
                Drag here to resize
```

Series
------
* Brubeck/DocStacks      (API - SimpleDict/Text/Code/Task/App)
* Davis/CodeStacks       (IDE)
* Desmond/WindowStacks   (UI)
* Ellington/SystemStacks (OS)

