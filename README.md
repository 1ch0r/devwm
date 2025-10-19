# devwm
A heavily customized chadwm fork. Includes alpha patch for transparency, and windowmap patch for fading affects.

# 🧠 devwm — A Transparent, Fading, Widget-Toggled DWM Fork for Gentoo Power Users

**devwm** is a heavily customized fork of [chadwm](https://github.com/siduck/chadwm), tailored for Gentoo users who want a more aesthetic dwm rice. It integrates transparency, fading effects, EWW widget toggling, and a custom Rofi theme — all modified with Gentoo in mind, but can be adapted to other distros.

## ✨ Features

- **Alpha Patch for Transparency**  
  Enables true window transparency using the official [alpha patch](https://dwm.suckless.org/patches/alpha/), compatible with picom.

- **WindowMap Patch for Fading**  
  Adds smooth fade-in/out transitions to window events, enhancing visual polish.

- **EWW Toggle Keybind**  
  A custom keybinding allows you to show/hide EWW widget instantly.

- **Custom Rofi Theme**  
  Includes a personalized Rofi configuration with transparency, left-centered layout, and modern styling.

## 📸 Screenshots

Here’s devwm in action:


## 📦 Dependencies

Make sure the following packages are installed:

- `picom` (recommended for transparency and fading)
- `eww` (for widgets)
- `rofi` (with custom theme)


## ⚙️ Installation

### Clone and Build

```bash
git clone https://github.com/1ch0r/devwm ~/.config/devwm
cd ~/.config/devwm/devwm
sudo make clean install
```
## ⌨️ Basic Keybindings
MOD + w:	Toggle EWW bar
MOD + q:  Quit active window
MOD + Enter:	Launch terminal
MOD + r:	Launch Rofi
MOD + f:	Launch ranger
MOD + u:  Launch flameshot

