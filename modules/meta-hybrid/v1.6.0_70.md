## v1.6.0

Changes since v1.5.4:
* Fix HymoFS compilation warnings and align ioctl struct with kernel patch
* Fix mount permission issues: move mount point to /dev and improve context repair
* Fix HymoFS mounting: add missing directory injection logic and verbose logging
* refactor(hymofs): strict logic alignment
* refactor(hymofs): align implementation