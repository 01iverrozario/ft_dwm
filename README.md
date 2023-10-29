# ft_dwm

ft_dwm is my custom build of dwm.

# Dependenices

To use ft_dwm, you need to have the following dependenices installed:
* xlib header files
* ttf-ubuntu-mono-nerd
* alacritty

# Installation

To install ft_dwm, clone this repository and run `make`:

```bash
git clone https://github.com/OliverRozario/ft_dwm
cd ft_dwm
sudo make clean install
```
Then, create dwm.desktop in /usr/share/xsessions/ and copy type
```bash
Name=Dwm
Comment=Log in using the dwm
Exec=/usr/local/bin/dwm
Icon=/usr/local/bin/dwm
Type=Application
```

# Usage 


|Key comibination | Action        |
|-----------------|:-------------:|
|Super+d          |Spawns dmenu   |
|Super+Escape     |Close apps     |
|Super+Enter      |Opens alacritty|
