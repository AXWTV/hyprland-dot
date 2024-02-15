<div align="center">

# ----- AXWTV-HYPRLAND-DOTFILE -----

<a href="https://github.com/D3Ext/aesthetic-wallpapers/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/AXWTV/Hyprland-DotFiles?style=for-the-badge&logo=starship&color=89b4fa&logoColor=D9E0EE&labelColor=302D41"></a>
  <a href="https://github.com/AXWTV/Hyprland-DotFiles/graphs/contributors">
    <img alt="Contributors" src="https://img.shields.io/github/contributors/AXWTV/Hyprland-DotFiles?style=for-the-badge&logo=gitbook&color=89b4fa&logoColor=D9E0EE&labelColor=302D41"></a>
  <a href="https://lbesson.mit-license.org/">
    <img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge&color=89b4fa&logoColor=D9E0EE&labelColor=302D41"></a>
  <a herf="https://github.com/AXWTV/Hyprland-DotFiles/commits/main">
    <img alt="last-commit" src="https://img.shields.io/github/last-commit/AXWTV/Hyprland-DotFiles?style=for-the-badge&color=89b4fa&logo=github&logoColor=D9E0EE&labelColor=302D41"></a> 
  <a href="https://github.com/AXWTV/Hyprland-DotFiles/releases/latest">
    <img alt="GitHub release" src="https://img.shields.io/github/v/release/AXWTV/Hyprland-DotFiles?style=for-the-badge&color=89b4fa&logo=github&logoColor=D9E0EE&labelColor=302D41"></a>

<br/>
</div>

### 💥 Copying / Installation / Update instructions 💥
- [`MORE INFO HERE`](https://github.com/AXWTV/Hyprland-DotFiles/wiki) 
> [!Note] 
> The auto copy script will create backups of intended folders to be copied. However, still a good idea to manually backup just incase script failed to backup!
- ~/.config (alacritty btop cava hypr kitty rofi swappy swaylock swaync waybar wlogout) - These are folders to be copied.
- ~/Pictures/wallpapers - Will be backed up
- clone this repo by using git. Change directory, make executable and run the script
```bash
git clone --depth=1 https://github.com/AXWTV/Hyprland-DotFiles.git
cd Hyprland-DotFiles
```
- to copy/install from upstream (possible bugs)
```bash
chmod +x copy.sh
./copy.sh
```
- to copy/install from releases (more "stable")
```bash
chmod +x release.sh
./release.sh
```

- UPGRADE.sh (Experimental)
> [!IMPORTANT]
> You should atleast v1.1.0 in your hyprland dots (ls ~/.config/hypr) to check version
> You need rsync for it to work

> [!CAUTION]
> you should have already up and running Hyprland before using this function
```bash
chmod +x upgrade.sh
./upgrade.sh
```

## Having Problems with installation or Other stuff
- Feel Free to open issues
- Also for guids go to [Wiki](https://github.com/AXWTV/Hyprland-DotFiles/wiki)

## This repo is a fork of [JaKooLit's Hyprland-Dots](https://github.com/JaKooLit/Hyprland-Dots).
