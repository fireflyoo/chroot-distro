# chroot-distro
Those simple code was generator from chatgpt.  
chroot-distro for openwrt  
Only implement the basic function  
such as:  
```
Usage: /bin/chroot-distro <command> [options]

Commands:
  help                     Show this message
  list                     List available distros
  install <distro> <url>        Install distro (simple tarball extract)
  remove <distro>          Remove installed distro
  login <distro>     Enter chroot for distro
```
and `chroot-distro install` function should manual add url ,and depend `opkg install tar`  
## Supppored OS
`chroot-distro install void "https://repo-default.voidlinux.org/live/current/void-aarch64-ROOTFS-20250202.tar.xz"`  
`chroot-distro install alpine https://dl-cdn.alpinelinux.org/alpine/latest-stable/releases/aarch64/alpine-minirootfs-3.23.3-aarch
64.tar.gz`
*Only tested void_aarch64 and alpine-aarch64 now.*  

this command function almost same as:  
https://github.com/Magisk-Modules-Alt-Repo/chroot-distro
