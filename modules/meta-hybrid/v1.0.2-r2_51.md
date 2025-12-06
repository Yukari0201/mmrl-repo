## v1.0.2-r2

Changes since v1.0.2-r1:
* fix(webui): localize google fonts dependency for accessibility in china
* merge: apply upstream patches for magic_mount and scripts
* fix(core): remove broken run() function and rename run_safe() to run()
* feat(webui): add dry-run switch dependent on verbose mode
* feat(cli): add --dry-run mode for simulation
* feat(core): implement parallel sync and prune using rayon
* [skip ci]add bug_report issue template
* feat(stealth): implement dynamic camouflage and fix mount leaks
* feat: implement webui storage keys
* feat(mount): parallelize magic mount module scanning
* chore(release): bump version to v1.0.2-r1 [skip ci]
* feat(core): introduce parallel overlayfs mounting using rayon