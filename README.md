# rad-mac-to-windows

You switched from Mac to Windows. Some things feel worse. This list fixes that.

Organized by what you miss, not by software category. Every app here was picked because it solves a specific "I had this on Mac" problem.

Want to add something? See [Contributing](#contributing).

## Contents

- [Window Management](#window-management)
- [Spotlight / App Launcher](#spotlight--app-launcher)
- [Quick Look (spacebar preview)](#quick-look-spacebar-preview)
- [Hot Corners](#hot-corners)
- [Focus / Do Not Disturb](#focus--do-not-disturb)
- [Stage Manager / Window Dimming](#stage-manager--window-dimming)
- [Clipboard Manager](#clipboard-manager)
- [Screenshot Tool](#screenshot-tool)
- [Terminal](#terminal)
- [Package Manager (Homebrew)](#package-manager-homebrew)
- [Time Machine (Backups)](#time-machine-backups)
- [Finder](#finder)
- [Preview (PDF/Image Viewer)](#preview-pdfimage-viewer)
- [AirDrop](#airdrop)
- [Keychain (Password Manager)](#keychain-password-manager)
- [Menu Bar Apps](#menu-bar-apps)
- [Text Expansion](#text-expansion)
- [Calendar Alerts](#calendar-alerts)
- [Audio Control (per-app volume)](#audio-control-per-app-volume)
- [System Tweaks & Missing Features](#system-tweaks--missing-features)
- [Trackpad Gestures](#trackpad-gestures)
- [Font Rendering](#font-rendering)
- [Productivity Suites](#productivity-suites)

## Window Management

macOS has Split View and (since Sequoia) window tiling. Windows has Snap, but power users want more.

- [FancyZones (PowerToys)](https://github.com/microsoft/PowerToys) - Custom window layouts with drag-to-zone. Closest to Rectangle/Magnet on Mac. `MIT`
- [GlazeWM](https://github.com/glzr-io/glazewm) - Tiling window manager inspired by i3. If you used Amethyst or yabai on Mac, this is the one. `GPL-3.0`
- [Workspacer](https://github.com/workspacer/workspacer) - Tiling window manager driven by C# scripting. `MIT`
- [bug.n](https://github.com/fuhsjr00/bug.n) - Tiling window manager written in AutoHotkey. Lightweight. `GPL-3.0`

## Spotlight / App Launcher

Spotlight search is one of the hardest things to replace. Windows Search is not it.

- [Flow Launcher](https://github.com/Flow-Launcher/Flow.Launcher) - Plugin-based launcher with file search, calculator, web search. Closest to Alfred. `MIT`
- [PowerToys Run](https://github.com/microsoft/PowerToys) - Microsoft's launcher. Fast, extensible with plugins. Ships with PowerToys. `MIT`
- [Wox](https://github.com/Wox-launcher/Wox) - Launcher with plugin support. Original inspiration for Flow Launcher. `MIT`
- [Keypirinha](https://keypirinha.com/) - Fast keystroke launcher. Portable, no install needed.
- [ueli](https://github.com/oliverschwendener/ueli) - Keystroke launcher with calculator, file search, web search, and workflows. `MIT`

## Quick Look (spacebar preview)

Press spacebar in Finder to preview any file. Windows doesn't have this built in.

- [QuickLook](https://github.com/QL-Win/QuickLook) - Spacebar preview for Windows Explorer. Supports images, PDFs, text, Office docs. `GPL-3.0`
- [Seer](http://1218.io/) - File previewer triggered by spacebar. Supports 100+ formats.

## Hot Corners

macOS lets you trigger actions by moving your cursor to screen corners.

- [WinXCorners](https://github.com/vhanla/winxcorners) - Hot corners for Windows. Trigger Task View, Show Desktop, Start Screen. `MIT`
- [Hot Corners WX](https://github.com/mgth/HotCornerWx) - Lightweight hot corners implementation.

## Focus / Do Not Disturb

macOS Focus modes filter notifications by context. Windows has Focus Assist, but it's basic.

- [Windows Focus Assist](https://support.microsoft.com/en-us/windows/turn-focus-assist-on-or-off-in-windows-5492a638-b5a3-1bcc-8bd8-1568fead3956) - Built-in. Priority only or alarms only. Does the job for most people.
- [PowerToys Awake](https://github.com/microsoft/PowerToys) - Keep your screen on without touching power settings. `MIT`

## Stage Manager / Window Dimming

Stage Manager on macOS dims inactive windows and organizes them on the side. On Windows:

- [PeakFlow (FocusDim)](https://github.com/inchwormz/peakflow-electron) - Dims everything except your active window. Closest thing to Stage Manager's focus behavior on Windows. `GPL-3.0`
- [HazeOver](https://hazeover.com/) - The original Mac app for dimming background windows. Mac only, listed here so you know what FocusDim replaces.

## Clipboard Manager

macOS doesn't ship with one either, but Paste and Maccy are popular. Windows has Win+V, but it's limited.

- [Ditto](https://ditto-cp.sourceforge.io/) - Clipboard manager with search, network sync, and paste groups.
- [PeakFlow (QuickBoard)](https://github.com/inchwormz/peakflow-electron) - Clipboard manager with search, auto-paste on select, and always-on-top panel. `GPL-3.0`
- [CopyQ](https://github.com/hluk/CopyQ) - Clipboard manager with scripting and advanced editing. `GPL-3.0`
- [1Clipboard](https://1clipboard.io/) - Cloud-synced clipboard manager using Google Drive.

## Screenshot Tool

macOS Cmd+Shift+4 is fast. Windows Snipping Tool has caught up, but power users want more.

- [ShareX](https://github.com/ShareX/ShareX) - Screenshots, screen recording, annotation, OCR, auto-upload. Does everything. `GPL-3.0`
- [Greenshot](https://github.com/greenshot/greenshot) - Lightweight screenshot tool with editor and quick export. `GPL-3.0`
- [Flameshot](https://github.com/flameshot-org/flameshot) - Cross-platform screenshot tool with annotation. `GPL-3.0`

## Terminal

Terminal.app and iTerm2 set a high bar. Windows catches up with these:

- [Windows Terminal](https://github.com/microsoft/terminal) - Microsoft's modern terminal. Tabs, panes, GPU-rendered text. `MIT`
- [WezTerm](https://github.com/wez/wezterm) - GPU-accelerated terminal with multiplexer and Lua scripting. `MIT`
- [Alacritty](https://github.com/alacritty/alacritty) - GPU-accelerated, minimal terminal. `Apache-2.0`
- [Oh My Posh](https://github.com/JanDeDobbeleer/oh-my-posh) - Prompt themes for PowerShell/bash/zsh. Oh My Zsh equivalent. `MIT`
- [Starship](https://github.com/starship/starship) - Fast, customizable prompt. Works with any shell. `ISC`

## Package Manager (Homebrew)

`brew install` is muscle memory. Windows equivalents:

- [WinGet](https://github.com/microsoft/winget-cli) - Microsoft's official package manager. `winget install firefox`. `MIT`
- [Scoop](https://github.com/ScoopInstaller/Scoop) - Command-line installer. No admin rights, no UAC. Closest to Homebrew's philosophy. `Unlicense`
- [Chocolatey](https://github.com/chocolatey/choco) - Oldest Windows package manager. Largest repository. `Apache-2.0`
- [UniGetUI](https://github.com/marticliment/UniGetUI) - GUI that wraps WinGet, Scoop, and Chocolatey in one interface. `MIT`

## Time Machine (Backups)

Time Machine just works. Windows backup options:

- [Syncthing](https://github.com/syncthing/syncthing) - Continuous file sync between devices. No cloud. `MPL-2.0`
- [Duplicati](https://github.com/duplicati/duplicati) - Encrypted backups to cloud storage. Schedule and forget. `LGPL-2.1`
- [restic](https://github.com/restic/restic) - Fast, encrypted, deduplicated backups. `BSD-2-Clause`
- [Veeam Agent for Windows](https://www.veeam.com/windows-endpoint-server-backup-free.html) - Full system image backups. Free tier available.
- [File History](https://support.microsoft.com/en-us/windows/file-history-in-windows-5de0e203-ebae-05ab-db85-d5aa0a199255) - Built-in. Closest to Time Machine in concept, but less reliable.

## Finder

Finder has column view, Quick Look, tags, and smart folders. Windows Explorer is ... basic.

- [Files](https://github.com/files-community/Files) - Modern file manager with tabs, column view, and cloud integration. `MIT`
- [Double Commander](https://github.com/doublecmd/doublecmd) - Dual-pane file manager. `GPL-2.0`
- [Everything](https://www.voidtools.com/) - Instant file search. Indexes your entire drive in seconds. Nothing on macOS is this fast.
- [Directory Opus](https://www.gpsoft.com.au/) - Most feature-complete file manager on Windows. Paid, but worth it for power users.

## Preview (PDF/Image Viewer)

macOS Preview handles PDFs, images, and basic annotation. Windows needs:

- [Sumatra PDF](https://www.sumatrapdfreader.org/free-pdf-reader) - Fast, lightweight PDF/EPUB/MOBI reader.
- [Okular](https://github.com/KDE/okular) - Document viewer with annotation support. PDF, EPUB, and more. `GPL-2.0`
- [ImageGlass](https://github.com/d2phap/ImageGlass) - Lightweight image viewer with modern UI. `GPL-3.0`
- [NomacS](https://github.com/nomacs/nomacs) - Fast image viewer with basic editing. `GPL-3.0`

## AirDrop

AirDrop between Apple devices is magic. Cross-platform alternatives:

- [LocalSend](https://github.com/localsend/localsend) - Open-source AirDrop alternative. Works across Windows, Mac, Linux, iOS, Android. `MIT`
- [Snapdrop](https://github.com/RobinLinus/snapdrop) - Browser-based file sharing on the same network. `GPL-3.0`
- [KDE Connect](https://github.com/KDE/kdeconnect-kde) - Phone-to-PC integration. File sharing, clipboard sync, notification mirroring. `GPL-2.0`

## Keychain (Password Manager)

macOS Keychain is integrated into the OS. Windows doesn't have an equivalent.

- [KeePassXC](https://github.com/keepassxreboot/keepassxc) - Local password database. No cloud, no accounts. `GPL-2.0`
- [Bitwarden](https://github.com/bitwarden/clients) - Password manager with cloud sync and browser extensions. `GPL-3.0`

## Menu Bar Apps

macOS menu bar is a whole ecosystem. Windows system tray is close but less visible.

- [TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor) - Network speed, CPU, and memory in the taskbar. `GPL-3.0`
- [EarTrumpet](https://github.com/File-New-Project/EarTrumpet) - Per-app volume control from the system tray. `MIT`
- [TranslucentTB](https://github.com/TranslucentTB/TranslucentTB) - Transparent/translucent taskbar. `GPL-3.0`

## Text Expansion

macOS has built-in text replacement. On Windows:

- [Espanso](https://github.com/espanso/espanso) - Cross-platform text expander. Config-file driven, supports shell commands. `GPL-3.0`
- [AutoHotkey](https://github.com/AutoHotkey/AutoHotkey) - Full scripting language. Text expansion is just one thing it does. `GPL-2.0`

## Calendar Alerts

macOS calendar notifications appear as banners. Windows notifications are easy to miss, especially in meetings.

- [PeakFlow (ScreenSlap)](https://github.com/inchwormz/peakflow-electron) - Full-screen meeting alert with countdown and one-click join. Google Calendar integration. `GPL-3.0`

## Audio Control (per-app volume)

macOS doesn't ship with per-app volume either, but Windows makes it harder to find than it should be.

- [EarTrumpet](https://github.com/File-New-Project/EarTrumpet) - Per-app volume control from the system tray. Clean UI. `MIT`
- [PeakFlow (SoundSplit)](https://github.com/inchwormz/peakflow-electron) - Per-app volume mixer with VU meters and WASAPI control. `GPL-3.0`

## System Tweaks & Missing Features

Things macOS handles that Windows needs third-party tools for.

- [PowerToys](https://github.com/microsoft/PowerToys) - FancyZones, Color Picker, File Explorer add-ons, Always on Top, Text Extractor, Paste as Plain Text, and more. Install this first. `MIT`
- [Winaero Tweaker](https://winaero.com/winaero-tweaker/) - Hidden Windows settings. Context menus, appearance, behavior.
- [O&O ShutUp10++](https://www.oo-software.com/en/shutup10) - Disable Windows telemetry, Cortana, ads, and other annoyances.
- [Chris Titus WinUtil](https://github.com/ChrisTitusTech/winutil) - Debloat Windows, install apps in bulk, apply performance tweaks. `MIT`

## Trackpad Gestures

Mac trackpad gestures are best-in-class. Windows precision trackpads are close, and these help:

- [GestureSign](https://github.com/TransposonY/GestureSign) - Custom touchpad and touchscreen gestures. `MIT`
- [Windows built-in gestures](https://support.microsoft.com/en-us/windows/touchpad-gestures-for-windows-a9d28305-4818-a5df-4e2b-e5590f850571) - Three-finger swipe for Task View, four-finger for desktops. Works with precision trackpads.

## Font Rendering

macOS font rendering is smoother. Windows uses ClearType, which looks sharper but thinner.

- [MacType](https://github.com/nicoth-in/mactype) - Replaces Windows font rendering with Mac-style subpixel rendering. Controversial but some people swear by it. `GPL-2.0`
- [BetterClearType](https://github.com/nicoth-in/bettercleartype) - ClearType tuner with more options than the built-in wizard.

**Honest take:** You get used to Windows font rendering after a week. MacType can cause compatibility issues with some apps. Try adjusting ClearType settings first.

## Productivity Suites

If you used multiple Mac utilities (Magnet + Paste + Dato + HazeOver), these bundle several tools:

- [PeakFlow](https://github.com/inchwormz/peakflow-electron) - Seven tools from the system tray. Focus dimmer (HazeOver), clipboard manager (Paste), Pomodoro timer with webcam tracking, per-app volume mixer, meeting alerts, mic/cam check. Free and open source. `GPL-3.0`
- [PowerToys](https://github.com/microsoft/PowerToys) - Microsoft's power user toolkit. Window management (Magnet), launcher (Spotlight), color picker, text extractor, and more. `MIT`

---

## Contributing

Switched from Mac to Windows and found something that helped? Open a PR.

**Rules:**

1. One app per pull request.
2. Put it under the Mac feature it replaces, not a generic category.
3. Use the format: `[Name](link) - Description. \`License\``
4. One sentence. Say what it does, not why it's amazing.
5. Alphabetical order within each section.
6. No abandoned projects. Last commit within 2 years.
7. If Windows has a good built-in solution, mention that too.

**Adding a new "I miss..." section?** Open an issue first so we can discuss where it fits.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is public domain. Use it however you want.
