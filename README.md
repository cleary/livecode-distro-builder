# This project is currently very WIP

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
