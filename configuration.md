## TODO

- [ ] Find a way to backup or synchronize all these settings
- [ ] Be set for life
- [ ] Use PowerShell

## Firefox

- [x] Set `browser.urlbar.dnsResolveSingleWordsAfterSearch = 0` in `about:config`
- [x] Don't save passwords
- [x] Ask were to save files
- [x] Always show bookmarks toolbar
- [x] Install add-ons
  - [x] [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin)
  - [x] [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
  - [x] [Reddit Enhancement Suite](https://addons.mozilla.org/en-US/firefox/addon/reddit-enhancement-suite/)
  - [x] [SauceNAO](https://addons.mozilla.org/en-US/firefox/addon/image-search-options/)

## Windows 10

- [x] Dark theme
- [x] Colored accents
- [x] Taskbar on top
- [x] Pin Home folder and Recycle Bin to "Quick access"
- [x] Disable "Enhance pointer precision" in "Mouse Properties"
- [x] Set "Configure Automatic Updates" to "Notify for download and auto install"  
*Edit group policy > Computer configuration > Administrative Templates > Windows Components > Windows Update*

## pip

```bash
pip install --user --upgrade youtube_dl
pip install --user --upgrade streamlink
```

Next, add `C:\Users\Anon\AppData\Roaming\Python\Python39\Scripts` to PATH

## MSYS2

```bash
# Installation
pacman -Syu
pacman -Su
pacman -S --needed base-devel mingw-w64-x86_64-toolchain

# My packages
pacman -S mingw-w64-x86_64-mpv
pacman -S mingw-w64-x86_64-emacs
pacman -S mingw-w64-x86_64-qemu
```

Add `C:\msys64\mingw64\bin` to System PATH

## Git for Windows

- [x] Tick minimal PATH option in installer

## PowerShell

- [x] Install [ColorTool](https://github.com/microsoft/terminal/tree/main/src/tools/ColorTool)
- [x] Download [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

## VS Code

Don't forget to add this later

## More

That's it for now
