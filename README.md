# Puffin-Internet-Terminal-Demo

TO INSTALL:
``` bash
git clone https://github.com/SF-Rocker/Puffin-Internet-Terminal.git
```
``` bash
makepkg PKGBUILD
```
cd into directory and find puffin-internet-terminal-bin-8.2.4.705-1-aarch64.pkg.tar.zst
copy location of the file and install with
``` bash
sudo pacman -U puffin-internet-terminal-bin-8.2.4.705-1-aarch64.pkg.tar.zst
```
it is easier just to install with yay wrapper
``` bash
sudo pacman -S yay
```
``` bash
yay puffin-internet-terminal-demo-bin
```
if it is not installing and showing the old cache from Version 1.0
``` bash
rm -rfv ~/.cache/yay/
```
then
``` bash
yay puffin-internet-terminal-demo-bin
```

Works on Manjaro on aarch64 architecture
kernel 6.0

