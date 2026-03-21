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
