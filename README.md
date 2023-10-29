# ft_dwm

ft_dwm is my custom build of dwm.

# Dependenices

To use ft_dwm, you need to install the following dependenices:
``` bash
sudo yay -S ttf-ubuntu-mono-nerd alacritty
```

# Installation

To install ft_dwm, clone this repository and run `make`:

```bash
git clone https://github.com/OliverRozario/ft_dwm
cd ft_dwm
sudo make clean install
```
Then, create dwm.desktop in /usr/share/xsessions/ and copy the following content:
```bash
Name=Dwm
Exec=/usr/local/bin/dwm
Icon=/usr/local/bin/dwm
Type=Application
```

# Usage 

Here's are some of the custom keyboard shortcuts that you can use:

|Key comibination | Action        |
|-----------------|:-------------:|
|Super+d          |Spawns dmenu   |
|Super+Escape     |Close apps     |
|Super+Enter      |Opens alacritty|

# Feedback

If you have any feedback or suggestions for ft_dwm, feel free to open an issue or a pull request on GitHub. I appreciate your input.
