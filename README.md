# Hyprland for Void Linux
Hyprland templates and buids for Void Linux

## Build from source
- Clone wlroots based on commit specified in the template file
- Create tar.gz archive and place it in masterdir/home
- Update common/shlibs, add the following:
> libwlroots.so.11032 wlroots-git-0.16.0+dev_2

Hyprland 0.7.0 onwards require at least GCC 12 to compile. Since the current GCC package in the Void repository is still in version 10.2.1, I am not able to update the package.

## Binary Releases
Releases are for **x86_64** only.


