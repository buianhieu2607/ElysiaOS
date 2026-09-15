<p align="center">
<a href="https://github.com/ElysiaOS/ElysiaOS">
  <img src="assets/cover.png">
  </a>
</p>

<div align="center">

# 🌸 ElysiaOS Release 🌸
### THIS PROJECT IS A FORK AIMED TO FIX OUTDATED BINARIES AND SYNTAXES
### Original repo: [ElysiaOS/ElysiaOS](https://github.com/ElysiaOS/ElysiaOS)

<h2><sub><img src="assets/signet.png" alt="Elysia" width="25" height="25" /></sub> Elysia Theme</h2>
<table align="center">
  <tr>
    <td colspan="4"><img src="assets/elysia1.png"></td>
  </tr>
  <tr>
    <td colspan="1"><img src="assets/elysia2.png"></td>
    <td colspan="1"><img src="assets/elysia3.png"></td>
    <td colspan="1" align="center"><img src="assets/elysia4.png"></td>
    <td colspan="1" align="center"><img src="assets/elysia5.png"></td>
  </tr>
</table>

<h2><sub><img src="assets/signet2.png" alt="HoC" width="25" height="25" /></sub> Elysia-HoC Theme</h2>
<table align="center">
  <tr>
    <td colspan="4"><img src="assets/hoc1.png"></td>
  </tr>
  <tr>
    <td colspan="1"><img src="assets/hoc2.png"></td>
    <td colspan="1"><img src="assets/hoc3.png"></td>
    <td colspan="1" align="center"><img src="assets/hoc4.png"></td>
    <td colspan="1" align="center"><img src="assets/hoc5.png"></td>
  </tr>
</table>

<h2><sub><img src="assets/signet3.png" alt="Cyrene" width="25" height="25" /></sub> Cyrene Theme</h2>
<table align="center">
  <tr>
    <td colspan="4"><img src="assets/cyrene1.png"></td>
  </tr>
  <tr>
    <td colspan="1"><img src="assets/cyrene2.png"></td>
    <td colspan="1"><img src="assets/cyrene3.png"></td>
    <td colspan="1" align="center"><img src="assets/cyrene4.png"></td>
    <td colspan="1" align="center"><img src="assets/cyrene5.png"></td>
  </tr>
</table>

<h2><sub><img src="assets/signet.png" alt="Elysia Signet" width="25" height="25" /></sub> Other Features</h2>
<table align="center">
  <tr>
    <td colspan="4"><img src="assets/bootup.png"></td>
  </tr>
  <tr>
    <td colspan="1"><img src="assets/grub.png"></td>
    <td colspan="1"><img src="assets/settings1.png"></td>
    <td colspan="1" align="center"><img src="assets/settings.png"></td>
    <td colspan="1" align="center"><img src="assets/updater.png"></td>
  </tr>
</table>

</div>

<h2><sub><img src="assets/eri.png" alt="Eri" width="25" height="25" /></sub> Installation</h2>

> [!NOTE]
> 
> ~~Wallpapers in screenshots are not mine nor i'm affiliated with the artists and they are not provided with the OS.~~
> 
> I will try to find the credits for the wallpapers, some may already have the credits on one of the corners
>
> Seems like the rice author announced the next version. I will abandon this repository once it drops.

> ~~Open Sourced Apps [ElysiaOS Apps](https://github.com/ElysiaOS) here~~

### DOTFILES

> Original installation script (This script is not my modified script, and will overwrite some folders in the `/home` directory.
> Please read the `.sh` file before executing.

```bash
curl -sSf https:/elysiaos.vercel.app/eri.sh | bash
```

> SETTING UP FLOORP THEME
> The Floorp browser installation is skipped in my script, I recommend install via Flatpak
```
launch floorp first time to create config file for yourself
copy the theme files from .floorp "chrome/" and "extentions/" into "/home/<uyoursername>/.floorp/<usersomething.default>" folder
install Sidebery extention and use my style
https://elysiaos.vercel.app/sidebery-style.txt
```

> Manual installation
> 
> I will put my script here. It will also overwrite some folders in the `/home` directory.
> 
> Please read the `install.sh` file before executing.

```
git clone https://github.com/buianhieu2607/ElysiaOS
cd ElysiaOS
chmod +x install.sh
./install.sh
```
### PACKAGES
> Both the original and my script do installs the packages automatically. This is here in case some fails to install

Make sure to add the elysiaos-repo to your pacman.conf before any installation
```
[elysiaos-repo]
SigLevel = Optional DatabaseOptional
Server = https://raw.githubusercontent.com/ElysiaOS/$repo/refs/heads/main/$arch
```
Install the packages from the AUR:
```
yay -S --noconfirm thunar hyprland starship rofi discord krita google-chrome eww wlogout swww eww kitty kew btop fastfetch hyprcursor hyprgraphics hypridle hyprland-qt-support hyprlock hyprpicker hyprutils hyprswitch xdg-desktop-portal-hyprland xdg-desktop-portal-gnome gnome-text-editor xdg-desktop-portal xfce4-settings xfce4-taskmanager gsettings-desktop-schemas gsettings-system-schemas qt5-base qt5-multimedia qt5-svg qt5-wayland qt5ct qt6-base qt6-wayland qt6ct zip libzip file-roller unzip thunar-archive-plugin noto-fonts ttf-jetbrains-mono-nerd auto-cpufreq sddm-eucalyptus-drop swaylock-effects python python-cairo python-installer python-numpy python-pillow python-pip python-pipx python-psutil python-pyqt6 python-pyqt5 python-pyqt5-webengine python-pyqt6-sip python-pyqt5-sip python-tqdm visual-studio-code-bin sublime-text-4 grim xclip wl-clipboard libnotify clipnotify copyq gpu-screen-recorder gpu-screen-recorder-ui gpu-screen-recorder-notification playerctl xkb-switch jq elysia-updater-elysiaos elysia-settings-elysiaos signet-workspaces-elysiaos elysia-welcome-elysiaos elysia-launcher sysinfo-elysiaos elysia-downloader elysiaos-bar elysia-widgets
```

<h2><sub><img src="assets/eri.png" alt="Eri" width="25" height="25" /></sub> Keybindings</h2>

| Keys | Action |
| :--- | :--- |
| <kbd>Super</kbd> + <kbd>Q</kbd> | Close focused window|
| <kbd>Super</kbd> + <kbd>SPACE</kbd> | Launch Application manager |
| <kbd>Super</kbd> + <kbd>T</kbd> | Terminal |
| <kbd>CTRL</kbd> + <kbd>SPACE</kbd> | Change Language |
| <kbd>Super</kbd> + <kbd>L</kbd> | Lock your screen Hyprlock |
| <kbd>Super</kbd> + <kbd>M</kbd> | Powermenu |
| <kbd>Super</kbd> + <kbd>[0-9]</kbd> | Switch workspaces |
| <kbd>Super</kbd> + <kbd>SHIFT</kbd> + <kbd>S</kbd> | Workspaces viewer Hyprspace |
| <kbd>Super</kbd> + <kbd>W</kbd> | Opens Elysia Notifaction Widget |
| <kbd>Super</kbd> + <kbd>TAB</kbd> | Elysia Widget for system info |
| <kbd>Super</kbd> + <kbd>SHIFT</kbd> + <kbd>W</kbd> | Launches Wallpapers menu |
| <kbd>Super</kbd> + <kbd>SHIFT</kbd> + <kbd>M</kbd> | Exit Hyprland alltogether |
| <kbd>Super</kbd> + <kbd>V</kbd> | Toggle float a window |
| <kbd>Super</kbd> + <kbd>D</kbd> | Launch text editor VSCODE |
| <kbd>Super</kbd> + <kbd>E</kbd> | Launch File manager Thunar |
| <kbd>Super</kbd> + <kbd>O</kbd> | Launch Floorp Browser |
| <kbd>Super</kbd> + <kbd>D</kbd> | Launch text editor VSCODE |
| <kbd>Super</kbd> + <kbd>PRINTSC</kbd> | Take a full screenshot |
| <kbd>Super</kbd> + <kbd>S</kbd> | Take a region screenshot |
| <kbd>F1</kbd>| MUTE Volume |
| <kbd>F6</kbd>| Lower Brightness |
| <kbd>F7</kbd>| Lower Brightness |
| <kbd>FN</kbd> + <kbd>F2</kbd> | Lower Volume |
| <kbd>FN</kbd> + <kbd>F3</kbd> | Higher Volume |
| <kbd>FN</kbd> + <kbd>F4</kbd> | MUTE Microphone |
| <kbd>Right CLICK</kbd> + <kbd>On ElysiaSignet</kbd> | System Information |
| <kbd>Left CLICK</kbd> + <kbd>On ElysiaSignet</kbd> | Powermenu |
| <kbd>Middle CLICK</kbd> + <kbd>On ElysiaSignet</kbd> | Theme Changer |



</div>

</div>



<h2><sub><img src="assets/eri.png" alt="Eri" width="25" height="25" /></sub> Details</h2>

- **OS Based on**: Arch Linux
- **SHELL**: fish
- **WM**: [Hyprland](https://github.com/hyprwm/Hyprland)
- **Wallpaper**: [swww](https://github.com/LGFae/swww)
- **Applications Launcher**: Elysia App Launcher
- **Top Bar**: [Custom (`elysiaos-bar`)](https://github.com/ElysiaOS/elysiaos-bar)
- **Widgets**: [Custom (`elysiaos-widgets`)](https://github.com/ElysiaOS/elysiaos-widgets)
- **Notifications**: [Swaync](https://github.com/ErikReider/SwayNotificationCenter)
- **Terminal**: [kitty](https://github.com/kovidgoyal/kitty)
- **Theme**: Use the themes in `.themes`
- **Icons**: Use the icons in `.icons`
- **Cursors**: [1st](https://ko-fi.com/s/58bc1bc84c) [2nd](https://www.pixiv.net/en/users/16588440) both in `.icons`

<h2><sub><img src="assets/eri.png" alt="Eri" width="25" height="25" /></sub> Roadmap & Future Updates</h2>

- [x] Updater Manager
- [x] GRUB Theme
- [x] Elysia App Launcher
- [x] Elysia Art Downloader
- [x] Boot Animation Improvements
- [x] Waybar Improvements
- [x] Added Keyboard Lang switcher
- [x] Customizable UI
- [x] Fixed SDDM Theme
- [x] Emoji Picker (bemoji support type bemoji in rofi for Emoji Picker)
- [x] Improved Handling Notifications
- [x] Power Menu
- [x] Screen Recorder
- [x] Screenshot Recorder
- [ ] Improve Settings Manager stability and more (?)
- [ ] Future Elysia AI Assistant
- [x] Improve Dashboard (possibly moving from eww to my new featured GTK dashboard?)
- [x] Adding more Themes support in future for every app
- [x] Cyrene Theme added and Amphereous

<h2><sub><img src="assets/eri.png" alt="Eri" width="25" height="25" /></sub> Special Thanks ♪</h2>

- Original repository: [ElysiaOS/ElysiaOS](https://github.com/ElysiaOS/ElysiaOS)
- [Some of the Folder icons](https://ko-fi.com/s/e3be105b94)
- [Main Floorp theme idea](https://github.com/Shina-SG/Shina-Fox)
- And Everyone else who tested and reported issues and bugs!!
- Sponsors: None

</div>
