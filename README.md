OpenBSD src patches
===================
Convenience patches for me. You can use them, but do not try to submit them.
This is mostly here so I don't lose things.

List of patches
---------------
| Name | Description | Alternative |
| ---- | ----------- | ----------- |
| `pax-J-flag.diff` | Adds a -J flag to cpio/pax/tar to extract xz archives | `xzdec <file.tar.xz \| tar xf -` |
| `posix_fadvise.diff` | Adds posix_fadvise(3) from DragonFly BSD | Remove the posix_fadvise call |
| `top-B-flag.diff` | Adds a -B flag to top for bar graphs of CPU usage (from edd@) | Use `htop` |
| `fluxbox-current.diff` | Updates x11/fluxbox to latest git HEAD | Use the older fluxbox package |
