<p align="center">
  <img src="icon.png" width="128" height="128" alt="Sendit Commander icon">
</p>

<h1 align="center">Sendit Commander</h1>

<p align="center">
  <a href="https://github.com/AlucardBlack/sendit-commander-releases/releases/latest"><b>Download</b></a>
  &nbsp;·&nbsp; <a href="https://github.com/AlucardBlack/sendit-commander-releases/releases">All releases</a>
  &nbsp;·&nbsp; <a href="SECURITY.md">Security</a>
</p>

Are you tired of Finder and miss those days when you were super productive with a classic
two-pane commander? Well, here's the solution.

Sendit Commander is a two-pane file manager for macOS, Windows and Linux. I built it because I
kept pressing F5 in Finder and nothing happened. It does what you remember: two folders next to
each other, F5 copies, F6 moves, and you rarely touch the mouse. It also does a few things the
old ones never did, mostly because I shoot a lot of photos and got tired of opening Lightroom
just to throw away the blurry ones.

There is a free edition and a paid one. Free has no time limit and no account. It is the whole
file manager. The paid edition adds the extras listed further down.

## What it does

**The basics.** Two panes with tabs, history and a list of favourite folders. F2 renames, F3
views, F4 edits, F5 copies, F6 moves, F7 makes a folder, F8 deletes. You can change any key. If
you forget one, `Cmd/Ctrl+Shift+P` opens a list of every command and you type a few letters.

**Copy and move.** They run in a queue in the background, so you can keep working. You can
pause the queue, or tell it to finish the current file and stop. If the app quits in the middle,
it offers to carry on next time.

**Renaming.** Batch Rename shows the new names before it changes anything, and it has undo. If a
photo has a RAW file, a JPEG and an `.xmp` file, the three are renamed together.

**Archives.** `.zip`, `.tar`, `.tar.gz`, `.7z` and `.rar` open like folders. You can also change
what is inside a zip: add files, delete them, rename them, set a password. RAR and 7z can only be
read.

**Looking at files.** F3 opens pictures with zoom, pan and rotate, including a real 100% view.
RAW files open at once and get sharper as you zoom in. Text files open in a small editor with
syntax colours and find and replace. A folder can be shown as a detailed list, a compact list,
thumbnails, or a photo grid. On a Mac, Quick Look, Share and "Open with" work too.

**Finding files.** `Alt+F7` searches by name, by text inside the file, by size and by date. You
can combine them. There is also a quick filter for the folder you are in.

**Everything else.** Select by pattern, compare two folders, folder sizes, checksums, file
attributes, your own toolbar, your own columns, colours per file type, light and dark themes,
your own commands. You can save all your settings to one file and load it on another computer.
The app updates itself when you say so.

## Free and paid

| | Free | Full |
|---|:---:|:---:|
| Two panes, tabs, favourites, history | ✓ | ✓ |
| Copy, move, delete, rename, Batch Rename | ✓ | ✓ |
| Archives | ✓ | ✓ |
| Viewer, editor, checksums | ✓ | ✓ |
| Find files by name and content | ✓ | ✓ |
| Themes, toolbar, columns, keys, your own commands | ✓ | ✓ |
| Updates | ✓ | ✓ |
| Servers: SFTP, FTP, WebDAV, S3, Google Drive | | ✓ |
| Android phones over USB | | ✓ |
| Synchronize two folders | | ✓ |
| Duplicate finder | | ✓ |
| Terminal inside each pane | | ✓ |
| Compare two files side by side | | ✓ |
| Photography mode | | ✓ |
| Extra search: camera and lens filters, search inside archives, indexed search | | ✓ |
| Send to Telegram | | ✓ |

On the free edition you can still see the paid features in the menus, and you can set up your
servers. They just stop at the Connect button.

### Photography mode

This is the part I use most. After a shoot I point one pane at the memory card and go through
the pictures with the keyboard: `1` to `5` for stars, `P` to keep, `X` to reject. The ratings are
written in XMP, the same format Lightroom reads, so nothing is lost when I open the keepers
there later.

A RAW file and its JPEG count as one photo. Reject one and the other goes with it. You can filter
by rating, collect the picks from several folders into one list, import from a card with your own
folder names, and send the selection to another app with a hotkey. I use that for DaVinci Resolve.

### Buying the full edition

Open Settings → License. You will see a Machine ID. Send it with your purchase and you get a key
back. Paste the key in the same place and the paid features turn on. No restart.

A key works on one computer. If you get a new computer, ask for a new key. The app never
contacts a server to check the license. Updates are included for good.

## Installing

Get the installer from the
[releases page](https://github.com/AlucardBlack/sendit-commander-releases/releases/latest).

On a **Mac** (Apple Silicon), open the `.dmg` and drag the app to Applications. I have not paid
Apple for notarization yet, so the first launch is blocked. Try to open the app once, then go to
System Settings → Privacy & Security, scroll down, and click "Open Anyway" next to Sendit
Commander. You only do this once. After that the app updates itself without asking again.

On **Windows**, run the `.exe` or the `.msi`. The installer is not signed yet, so SmartScreen
will warn you. Click "More info", then "Run anyway".

On **Linux** there is an `.AppImage`, a `.deb` and an `.rpm`.

I work on a Mac, so that version gets the most testing. Windows and Linux work, but expect more
rough edges there. If something breaks, tell me.

Passwords for servers are kept in the system keychain, not in a settings file.

## About this page

The source code is in a private repository. This one holds the downloads and the file the app
reads to find updates. Every update is signed, and the app refuses a file that does not match.

All rights reserved. To report a security problem, see [SECURITY.md](SECURITY.md).
