# This project is currently very WIP

It's a tool to build livecds. Originally based off the debian-focussed [pyfll](https://github.com/fullstory/pyfll) project by Stefan Lippers-Hollmann and Kel Modderman et al of the sidux/aptosid projects.

This code was forked about 10 years ago to use the Ubuntu casper initramfs livecd architecture, added ansible package profile management, and in this form is intended as a purpose driven livecoding focussed livecd builder. Of course, you can probably use it to build anything ... 

See also: https://github.com/cleary/livecode-distro-package-profile

## Usage:
  See ./fll --help

## Example Usage:
```
cp fll.conf.example fll.conf
```
```
./fll -c fll.conf -b /tmp/fll/ -o /tmp/fll/
```

## Dependencies:
```
  python (>= 2.5)
  python-apt
  python-configobj
  cdebootstrap | debootstrap
  xorriso
  squashfs-tools
  syslinux-common
  isolinux
```

## Recommends:
  reprepro (for liveapt functionality and extras (amd64 with efi))
