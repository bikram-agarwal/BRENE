# BRENE

BRENE - A SuSFS/KernelSU module for SuSFS patched kernels

## Changelog

# BRENE v0.0.51 - Supports SuSFS 2.1.0

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

# BRENE v0.0.50 - Supports SuSFS 2.1.0

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
