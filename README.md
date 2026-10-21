# PCBView.io for desktop

A free PCB viewer for Windows, macOS and Linux. The same viewer as [pcbview.io](https://pcbview.io), and your files never leave your computer.

**[Download the latest release](https://github.com/woodruffrb/pcbview-releases/releases/latest)**

| | |
|---|---|
| Windows | `PCBView.io-Setup.exe` |
| macOS | `PCBView.io-arm64.dmg` (Apple silicon) or `PCBView.io-x64.dmg` (Intel) |
| Linux | `PCBView.io-linux.AppImage` (recommended: it updates itself) or `PCBView.io-linux.deb` |

Opens Altium, KiCad, Eagle, EasyEDA, PADS, ODB++, IPC-2581, Gerber and Excellon, with pick-and-place, BOM and IPC-D-356 files from the same job. Search as you type, click copper to trace a net, and see the board in 3D.

The viewer works with no network connection. The app checks this page for new versions and offers them; nothing about you or your files is sent.

On Windows and with the Linux AppImage, updates install from inside the app. On macOS, and with the Linux `.deb`, the app tells you when a new version is out and downloads it in your browser.

To run the AppImage, make it executable (`chmod +x PCBView.io-linux.AppImage`). Ubuntu 22.04 and later also need FUSE 2: `sudo apt install libfuse2t64` (or `libfuse2` on 22.04).

This repo holds the installers only. Copyright 2026 Derivative Engineering LLC. All rights reserved.
