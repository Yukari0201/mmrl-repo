## v1.9.5

Changes since v1.9.41:
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