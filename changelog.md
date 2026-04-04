## v0.0.45

- webui: a few improvements
- add: BRENE logs
- release: v0.0.45

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.44...v0.0.45

## v0.0.44

- webui: improve smoothness using async functions
- webui: improve Chinese WebUI, thanks to Su XiaoMing @Saturday777G (Telegram user)
- update: config.sh
- webui: a few improvements
- improve: module status
- add: a symlink (ksu_susfs) to the susfs binary for compatibility
- release: v0.0.44

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.43...v0.0.44

## v0.0.43

- improve: move resetprop [-c|--compact] to boot-completed.sh
- remove: old code (Hexpatch)
- improve: sync with upstream (ksu_module_susfs)
- webui: add repository links for BRENE and SuSFS titles
- improve: use [ -e ] instead of [ -d ] [ -f ] and use "source" instead of "."
- release: v0.0.43

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.42...v0.0.43

## v0.0.42

- improve: symlink creation
- improve: support resetprop [-c|--compact] (Compact property area memory)
- webui: improve descriptions
- remove: "Rooted Apps Folders Hiding" and "Custom Recovery Folders Hiding" toggles
- add: hot install support
- improve: symlink creation again
- improve: sync with upstream (ksu_module_susfs)
- improve: update susfs binary
- release: v0.0.42

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.41...v0.0.42

## v0.0.41

- webui: improve some descriptions
- improve: Uname Spoofing
- improve: move SuSFS logs toggle logic to post-fs-data mode (post-fs-data.sh)
- release: v0.0.41

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.40...v0.0.41

## v0.0.40

- remove: duplicate code
- add: a symlink to the susfs binary for development
- add: a new toggle "Non-standard /sdcard Paths Hiding"
- add: a new toggle "Non-standard /sdcard/Android Paths Hiding"
- webui: a few improvements; disable Simplified Chinese WebUI (It is outdated)
- release: v0.0.40

## v0.0.39

- improve: Uname Spoofing, use the build date to spoof better
- improve: sync with upstream (ksu_module_susfs)
- release: v0.0.39

## v0.0.38

- breaking: minimal supported kernel is 32336 (update customize.sh)
- improve: update susfs binary
- improve: remove old SuSFS code
- release: v0.0.38

## v0.0.37

- update: disable "Hide /sdcard/Android/data Items" toggle by default in config.sh
- webui: add a new section "Custom ROM"
- webui: add a new section "Heavy Hiding Features"
- improve: use add_sus_path for "Hide /sdcard/Android/data Items" toggle
- Revert "fix: always enable kernel umount feature at boot"
- revert: "webui: disable kernel umount" manually
- disable: all toggles in config.sh by default
- release: v0.0.37

## v0.0.36

- improve: move prop spoofing to late_start service mode (service.sh)
- improve: "Hide /sdcard/Android/data Items" toggle
- revert: "improve: use /storage/emulated/0 instead of /sdcard" manually
- improve: remove the use of add_sus_path and replace it with add_sus_path_loop
- webui: update simplified_chinese_webui.html, Thanks to Telegram user @TaoMuYun
- webui: add a dialog for "Simplified Chinese WebUI" toggle
- release: v0.0.36

**Full Changelog**: https://github.com/bikram-agarwal/BRENE/commits/v0.0.36
