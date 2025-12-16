## v1.7.1

Changes since v1.7.0:
* Perf: Parallelize conflict analysis and mount plan generation using Rayon
* [skip ci]Remove unused version update from release.yml
* Perf: Parallelize module scanning and rules loading using Rayon
* Refactor: Replace unwrap with anyhow::Context and improve config error handling
* refactor: Add dead code allowance for unused functions in hymofs and utils
* refactor: Replace raw ioctl implementation with nix crate
* feat: Check CONFIG_TMPFS_XATTR=y runtime support for OverlayFS on tmpfs
* chore(deps-dev): bump svelte from 5.45.4 to 5.46.0 in /webui
* chore(deps-dev): bump vite from 7.2.6 to 7.3.0 in /webui (#49)