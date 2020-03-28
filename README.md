# mpd-menu

## Description
Simple mpd client in rofi. 

## Screenshots
![scr1](./screenshot1.png)

![scr2](./screenshot2.png)

![scr3](./screenshot3.png)

## Installation
### Dependencies
Package | Description
:--- | :---
rofi | application menu, dmenu replacement
mpd | music player daemon
mpc | CLI client for mpd

### Install dependencies
#### Arch Linux
```
sudo pacman -S --needed rofi mpd mpc
```
#### Debian/Ubuntu
```
sudo apt install rofi mpd mpc
```
#### Fedora
```
sudo dnf install rofi mpd mpc
```
#### openSUSE
```
sudo zypper in rofi mpd mpc
```
### Clone repository
```
git clone https://github.com/samedamci/rofi-mpd
```

### Usage
Use `./rofi-mpd` with `--help` or `-h` flag to get help.
```
usage: rofi-mpd [-h] [-l] [-s] [-a]

arguments:
-h, --help      show this message and exit
-l              library mode (artist -> album)
-s              song mode (select one song)
-a              ask for mode
```
