# Hyprland Dotfiles (Graphite Color Scheme) 🌑
> [!NOTE]
> This repository is no longer actively maintained because i needed to change my OS, but in the future i probably return.

My personal Linux desktop configuration in the 'Graphite' color scheme, built around [Hyprland](https://hyprland.org/), a dynamic tiling Wayland compositor. Feel free to use the dotfiles or for inspiration!  

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c52be35e-36df-4b5c-a85f-10c8693fa97e" />

🖌️ **Base Color Palette Codes:**
  - ![#1e1e1e](https://placehold.co/15x15/1e1e1e/1e1e1e.png)⠀`#1e1e1e`
  - ![#2a2a2a](https://placehold.co/15x15/2a2a2a/2a2a2a.png)⠀`#2a2a2a` 
  - ![#3c3c3c](https://placehold.co/15x15/3c3c3c/3c3c3c.png)⠀`#3c3c3c`
  - ![#3f3f3f](https://placehold.co/15x15/3f3f3f/3f3f3f.png)⠀`#3f3f3f`
  - ![#f2f2f2](https://placehold.co/15x15/f2f2f2/f2f2f2.png)⠀`#f2f2f2`
  - ![#a0a0a0](https://placehold.co/15x15/a0a0a0/a0a0a0.png)⠀`#a0a0a0`
  - ![#d0d0d0](https://placehold.co/15x15/d0d0d0/d0d0d0.png)⠀`#d0d0d0`
  - ![#505050](https://placehold.co/15x15/505050/505050.png)⠀`#505050`
  
# ❓ What's included

| Component | Tool |
|-----------|------|
| Window manager | Hyprland |
| Status bar | Waybar & Wlogout |
| Terminal | Kitty, Fastfetch, Superfile & Btop |
| Launcher | Rofi |
| Notifications | Swaync |
| Shell | zsh |
| Wallpaper | Hyprpaper |
| Font | JetBrainsMonoNerd |
| Theme | Kvantum-Graphite |
| Spicetify | Graphite colors and spotifytui theme |
| Vesktop | Graphite color | 

## 📂 Structure

```
.
├── hypr/           # Hyprland configuration
├── waybar/         # Status bar
├── wlogout/        # Power options in waybar configuration
├── kitty/          # Terminal configuration
├── kvantum/        # Kvantum theme
├── btop/           # Btop configuration
├── fastfetch/      # Custom fastfetch
├── superfile/      # File manager terminal configuration
├── rofi/           # App launcher configuration
├── spotitui-graph/ # Spotifytui custom colors
├── vesktop/        # Vesktop custom colors
```

## 🔧 Installation

> **Note:** these are my personal settings. Review the files and back up your current configuration before using them.

1. Install the dependencies:

```zsh
   # Example for Arch Linux
   sudo pacman -S hyprland hyprpaper hyprcursor kitty fastfetch waybar swaync wlogout kvantum qt5ct qt6ct rofi 
```

2. Clone the repository:

```zsh
   git clone https://github.com/gkennyz/hyprland-dotfiles.git
   cd hyprland-dotfiles
```

3. Back up your existing configs and copy the new ones:

```zsh
   mkdir -p ~/.config-backup
   cp -r ~/.config/hypr ~/.config-backup/ 2>/dev/null
   cp -r hypr ~/.config/
   # repeat for the other folders you want to use
```

4. Log out and start a Hyprland session.

5. You need to specify the path where you saved the icons of the wlogout, so after the instalation, go to the style.css file and specify the path of icons:

```
~/.config/wlogout/style.css
```

## 📜 Notes

- Tested on: Arch Linux 6.15.7
- I don't updated to the new Hyprland version with the new config schema/language, in the future i will update

## 📃 Credits
[Inspired by: Graphite theme by vinceliuice]
