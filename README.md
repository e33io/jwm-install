# JWM install

### Features:
- Custom [JWM](https://joewing.net/projects/jwm) installation for [Arch](https://github.com/e33io/scripts/blob/main/arch-install-jwm.sh) or [Debian](https://github.com/e33io/scripts/blob/main/debian-install-jwm.sh)
- Base set of apps for a ready-to-use desktop session
- HiDPI or standard HD scaling setup option
- Device specific optimizations for desktop, laptop or VM devices
- [Polybar](https://github.com/polybar/polybar) for system bar and app tray
- 18 system theme options (15 dark and 3 light)
- 3 Rofi style options (dmenu, floating and panel)
- Inter and [SovranMono](https://github.com/e33io/sovran-fonts) fonts

### Installation:
```bash
# install git on Arch
sudo pacman -S git

# install git on Debian
sudo apt install git

# clone repo
git clone https://github.com/e33io/jwm-install

# change directory
cd jwm-install

# run script
sh install.sh
```

### Utilities:
```bash
# change wallpaper
set-bg /path/to/image

# change system theme
set-theming-jwm

# change Rofi style
rofi-style

# select wifi connection
wifi
```

&nbsp;

## JWM Keybindings

```
Modifier keys:

Mod4      Windows (Super) key
A         Alt key
C         Control key
S         Shift key
Return    Enter key
space     Space bar
Left      Left arrow key
Right     Right arrow key
Up        Up arrow key
Down      Down arrow key
Tab       Tab key
equal     Equal key
minus     Minus key
Print     PrtSc (Print Screen) key
button1   Left mouse button
button3   Right mouse button
```
```
Custom keybindings:

Mod4+d          Program launcher (app menu)
Mod4+Return     Launch terminal
Mod4+S+Return   Launch file manager
Mod4+b          Launch web browser
Mod4+1          Switch to workspace 1
Mod4+2          Switch to workspace 2
Mod4+3          Switch to workspace 3
Mod4+4          Switch to workspace 4
Mod4+5          Switch to workspace 5
Mod4+6          Switch to workspace 6
Mod4+7          Switch to workspace 7
Mod4+8          Switch to workspace 8
Mod4+9          Switch to workspace 9
C+A+Right       Switch to next workspace
C+A+Left        Switch to previous workspace
Mod4+S+1        Send active window to workspace 1
Mod4+S+2        Send active window to workspace 2
Mod4+S+3        Send active window to workspace 3
Mod4+S+4        Send active window to workspace 4
Mod4+S+5        Send active window to workspace 5
Mod4+S+6        Send active window to workspace 6
Mod4+S+7        Send active window to workspace 7
Mod4+S+8        Send active window to workspace 8
Mod4+S+9        Send active window to workspace 9
Mod4+S+Right    Send active window to next workspace
Mod4+S+Left     Send active window to previous workspace
A+Tab           Change active window focus to next window
Mod4+A+Right    Change active window focus to next window
A+S+Tab         Change active window focus to previous window
Mod4+A+Left     Change active window focus to previous window
Mod4+S+f        Toggle active window fullscreen
Mod4+S+m        Maximize and unmaximize active window
Mod4+S+v        Maximize and unmaximize active window vertically
Mod4+S+h        Maximize and unmaximize active window horizontally
Mod4+C+Right    Move active window right
Mod4+C+Left     Move active window left
Mod4+C+Up       Move active window up
Mod4+C+Down     Move active window down
C+S+Right       Resize active window width larger
C+S+Left        Resize active window width smaller
C+S+Up          Resize active window height smaller
C+S+Down        Resize active window height larger
Mod4+S+space    Move active window to center of screen
Mod4+Right      Tile active window right
Mod4+Left       Tile active window left
Mod4+Up         Tile active window up
Mod4+Down       Tile active window down
A+space         Show active window's menu
Mod4+o          Show list of open windows
Mod4+S+q        Close active window
Print           Screenshot entire desktop
S+Print         Screenshot selected area
Mod4+Print      Screenshot active window
Mod4+C+equal    Disable dpms to keep session awake (like Caffeine)
Mod4+C+minus    Re-enable dpms to resume screen blanking and locking
Mod4+x          Lock screen
Mod4+p          Power menu (lock, logout, reboot, shutdown)

Mod4+button1 in the window and drag     Move active window
Mod4+button3 in the window and drag     Resize active window
button1 on the window border and drag   Resize active window
```

View the [~/.config/jwm/jwmrc](https://github.com/e33io/core/blob/main/home/.config/jwm/jwmrc) file to see all the configured keybindings that aren’t indicated in the box above

&nbsp;
