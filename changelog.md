## v0.0.54

BRENE v0.0.54 - Supports SuSFS 2.2.0

- webui: add Custom ROM indicator
- drop: "/data/media/0" paths hiding
- improve: update resetprop usage with new flags
- drop: old SuSFS patches support
- add: new toggle "Hide framework-res.apk"
- bump: version to v0.0.54

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.53...v0.0.54

## v0.0.53

BRENE v0.0.53 - Support for SuSFS 2.1.0 & 2.2.0

- webui: add recommendation for Specter module
- improve: sync with upstream (resetprop Magisk-compatible system property tool)
- improve: simplify "Injections Hiding" code
- improve: hide additional .so files in "Injections Hiding"
- improve: "Remove Custom ROM Properties" and "Remove Play Integrity Fix Properties" options
- improve: "SELinux Enforcing" option
- webui: open links directly on the browser
- webui: improve ..5.u.S Status
- improve: add additional custom ROM props
- webui: improve swipe
- bump: version to v0.0.53

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.52...v0.0.53

## v0.0.52

BRENE - A SuSFS/KernelSU module for SuSFS patched kernels

BRENE v0.0.52 - Supports SuSFS 2.1.0 & 2.2.0

- webui: add BreWheel recommendation
- webui: add description for ..5.u.S Status
- improve: "/sdcard/Android/[data | media | obb]" option and remove the experimental tag
- add: hiding support for Neo Backup
- update: README.md
- add: new toggle "Hide Suspicious PTYs"
- webui: add TEESimulator-RS recommendation
- bump: version to v0.0.52

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.51...v0.0.52

## v0.0.51

BRENE v0.0.51 - Supports SuSFS 2.1.0

- improve: README.md
- optimize: Enhanced script security (#23)
- add: a new toggle "Umount Suspicious Mounts"
- webui: update descriptions
- fix: rename correctly the name of CHANGELOG.md file
- update: .gitignore
- add: .vscode folder, settings.json file and set LF as default line ending in VSCode
- add: .gitattributes file and set LF as default line ending
- improve: ignore binaries in .gitattributes
- fix: ignore .jpg binaries in .gitattributes
- improve: normalize all the line endings
- fix: remove "..5.u.S" and improve performance
- fix: remove existence check for custom sus paths to support dynamic directories (#28)
- improve: "Non-standard /sdcard" option and follow to upstream
- fix: keep MIUI folder on MIUI/HyperOS to avoid recording failures (#30)
- improve: "/sdcard/Android/[data | media | obb]" option and follow to upstream
- improve: reuse "rm -rf" command
- add: new section "STATUS"; improve: WebUI
- add: new toggle "Umount Suspicious Mounts 2B"
- webui: add experimental tag to "/sdcard/Android/[data | media | obb]" toggle
- bump: version to v0.0.51

## What's Changed
* optimize: Enhanced script security by @helloworld2540 in https://github.com/rrr333nnn333/BRENE/pull/23
* fix: remove existence check for custom sus paths to support dynamic directories by @Guxin12 in https://github.com/rrr333nnn333/BRENE/pull/28
* fix: keep MIUI folder on MIUI/HyperOS to avoid recording failures by @Guxin12 in https://github.com/rrr333nnn333/BRENE/pull/30

## New Contributors
* @helloworld2540 made their first contribution in https://github.com/rrr333nnn333/BRENE/pull/23
* @Guxin12 made their first contribution in https://github.com/rrr333nnn333/BRENE/pull/28

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.50...v0.0.51

## v0.0.50

BRENE v0.0.50 - Supports SuSFS 2.1.0

- improve: WebUI, thanks to telegram user @dnascorpionofficial (code reference)
- webui: improve swipe
- improve: new section "Paths Hiding"
- improve: new section "Other Hiding"
- improve: new section "Custom SuSFS Entries"
- webui: some improvements
- improve: BRENE logs
- Also cover halcyon props with "Hide Custom ROM props"
- Merge pull request #22 from bitThrived/main
- add: a new toggle "BRENE Logs"
- drop: old SuSFS patches support

## What's Changed
* Also cover halcyon props with "Hide Custom ROM props" by @bitThrived in https://github.com/rrr333nnn333/BRENE/pull/22

## New Contributors
* @bitThrived made their first contribution in https://github.com/rrr333nnn333/BRENE/pull/22

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.49...v0.0.50

## v0.0.49

Supports SuSFS 2.1.0

- add: a new toggle "SU Compat"
- improve: unify the Non-standard /sdcard Paths Hiding toggles
- remove: old Chinese WebUI
- improve: unify the Injections Hiding toggles
- webui: add a warning to "SU Compat" toggle; and a few improvements
- release: v0.0.49

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.48...v0.0.49

## v0.0.48

- improve: simplify the code to remove "/sdcard/..5.u.S"
- refactor: customize.sh
- refactor: post-fs-data.sh
- refactor: post-mount.sh
- refactor: service.sh
- refactor: boot-completed.sh
- update: uninstall.sh, utils.sh and script.js
- update: .gitignore
- improve: add "#!/system/bin/sh" and format code
- improve: code quality, bug fixes, logs, format code, use "#!/bin/bash"
- improve: sync with upstream (ksu_module_susfs)
- improve: my implementation to remove "..5.u.S"
- release: v0.0.48

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.47...v0.0.48

## v0.0.47

- improve: update susfs binary
- improve: use inotifyd to improve performance ("/sdcard/..5.u.S")
- improve: use "[[ ]]" instead of "[ ]"
- release: v0.0.47

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.46...v0.0.47

## v0.0.46

- add: a new toggle "Android System Properties Spoofing"
- improve: "Remove Play Integrity Fix Props" toggle
- improve: update susfs binary
- improve: Uname Spoofing
- improve: remove "/sdcard/..5.u.S" automatically (attack vector)
- release: v0.0.46

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.45...v0.0.46

## v0.0.45

- webui: a few improvements
- add: BRENE logs
- release: v0.0.45

**Full Changelog**: https://github.com/rrr333nnn333/BRENE/compare/v0.0.44...v0.0.45

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
