## v1.9.53

Changes since v1.9.41:
* chore (#93)
* 补充描述 (#92)
* chore(release): bump version to v1.9.52 [skip ci]
* utils: fix SELinux permission denied on tmpfs/EROFS
* fix(core): smart selinux context repair for system/vendor partitions
* chore(release): bump version to v1.9.51 [skip ci]
* feat: support trusted.overlay.opaque xattr for replace dir detection
* fix: log phase
* Revert "refactor(utils): simplify selinux handling to match cp -a behavior"
* deps: removed unused deps (#90)
* chore(release): bump version to v1.9.5 [skip ci]
* fix: fix mount overlayfs lower error (#89)
* fix: fix module files execute failed (#87)
* Update and rename metainstall.sh to post-fs-data.sh
* Update and rename metamount.sh to service.sh
* Delete module/metauninstall.sh
* Update customize.sh
* Enhance uninstall script with module checks
* feat: allow customizing mount point path
* feat: divide && move
* feat: add KernelSU check (#83)
* refactor(utils): simplify selinux handling to match cp -a behavior