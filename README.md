# 🍃 Animal Crossing for Omarchy

A light **Omarchy** theme in cream paper, leaf green and sea-breeze blue — with three original hand-drawn wallpapers. Take it slow.

🌙 **Night mode**: [omarchy-animal-crossing-night-theme](https://github.com/junbaor/omarchy-animal-crossing-night-theme) — the starlit sister theme.

Language: **English** · [简体中文](README.zh-CN.md)

![Theme preview](preview.png)

## Wallpapers

| Island Morning | Leaf Meadow | Sunset Pier |
|:---:|:---:|:---:|
| ![Island Morning](backgrounds/1-island-morning.png) | ![Leaf Meadow](backgrounds/2-leaf-meadow.png) | ![Sunset Pier](backgrounds/3-sunset-pier.png) |

Cycle them with `omarchy theme bg next`.

## Install

```bash
omarchy theme install https://github.com/junbaor/omarchy-animal-crossing-theme
omarchy theme set animal-crossing
```

## Palette

| Role | Hex | Note |
|---|---|---|
| Background | `#FBF5E6` | Cream paper |
| Accent | `#3B7A2E` | Leaf green (Nook Leaves 🍃) |
| Foreground | `#4A3B2B` | Warm brown |
| Blue | `#2F6F99` | Sea breeze |
| Yellow | `#9C6F0A` | Bell gold (🔔) |
| Red | `#C34F4B` | Balloon coral |
| Magenta | `#A35A89` | Petal pink |
| Brown | `#8B5E3C` | Timber |

Full palette in [colors.toml](colors.toml). Foreground colors are calibrated to WCAG contrast (≥ 4.5:1) so they stay readable on the cream background.

## Customization

1. Edit `~/.config/omarchy/themes/animal-crossing/colors.toml`
2. Run `omarchy theme refresh`

Terminals, Neovim, btop, VS Code, GTK, fcitx5, menus/notifications/lock screen — everything is generated from `colors.toml` automatically.

## Boot splash

Wear the theme at boot too: menu → Style → Unlock, or

```bash
sudo omarchy-plymouth-set-by-theme animal-crossing
```

## Files

```
├── colors.toml        # core palette (everything else is generated from it)
├── backgrounds/       # three original 2560×1440 wallpapers
├── sources/           # SVG sources of the wallpapers — remix welcome
├── preview.png        # theme picker preview
├── icons.theme        # icon pack (Yaru-olive)
├── keyboard.rgb       # keyboard backlight color
├── unlock.png         # Plymouth boot logo (leaf green)
└── preview-unlock.png # boot splash preview
```

## Related

- 🌙 Night: [omarchy-animal-crossing-night-theme](https://github.com/junbaor/omarchy-animal-crossing-night-theme)
- [Omarchy](https://omarchy.org/)

All wallpapers are original vector art (SVG sources in `sources/`), free to modify and reuse.

## License

[MIT](LICENSE)
