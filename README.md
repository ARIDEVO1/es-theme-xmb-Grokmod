# es-theme-xmb-Grokmod

XMB-styled theme for EmulationStation (FCAMOD), modified from [jovemlcxx/es-theme-xmb-fcamod](https://github.com/jovemlcxx/es-theme-xmb-fcamod).

Optimized for R36S and other 4:3 / 1:1 handhelds running ArkOS / dArkOS / FCAMOD.

## Changes in Grokmod

### Dark Mode Fix
- Fixed broken textbox / menu text input in Dark mode (was referencing missing PNG images → white box + black text).
- Now uses the solid white.png base so the background correctly follows the color scheme.

### New Color Schemes
Available in **Theme Configuration → Color Scheme**:

| Scheme               | Style                              |
|----------------------|------------------------------------|
| Dark                 | Original dark                      |
| Light                | Original light                     |
| **Pink**             | Soft pink / hot pink accents       |
| **Dark Blue**        | Deep navy / cyan accents           |
| **Light Gray**       | Soft light gray / neutral          |
| **PlayStation Blue** | Classic PS blue (XMB vibes)        |
| **Firefox**          | Purple + Yellow (Firefox vibes)    |
| **Purple Blue**      | Deep purple-blue                   |

### Font Support
New option in **Theme Configuration → Font Set**:

| Option       | Files expected in `_inc/fonts/`          |
|--------------|------------------------------------------|
| Default      | FOT-NewRodin Pro DB.otf / B.otf (original) |
| Minecraft    | `Minecraft.ttf`                          |
| Pixel        | `Pixel.ttf`                              |
| Custom 1     | `Custom1.ttf`                            |
| Custom 2     | `Custom2.ttf`                            |
| Custom 3     | `Custom3.ttf`                            |
| Custom 4     | `Custom4.ttf`                            |
| Custom 5     | `Custom5.ttf`                            |

Just drop your font files into `_inc/fonts/` with the exact names above and select the corresponding Font Set.

### Still supported
- Aspect Ratio: 4:3 (R36S) / 1:1
- System Layout: Horizontal (XMB Classic) / Vertical (Left Bar)
- Wallpaper 1–20 + optional background video
- All original sounds, icons, and layouts

## Installation
1. Copy the whole `es-theme-xmb-Grokmod` folder to your themes directory (`/roms/themes/` or `~/.emulationstation/themes/`).
2. In EmulationStation go to **UI Settings → Theme Set** and select **xmb-Grokmod**.
3. Open **Theme Configuration** to pick Color Scheme, Font Set, Aspect Ratio, Layout, Wallpaper, etc.

## Adding your own fonts
Place the `.ttf` / `.otf` files in:
```
es-theme-xmb-Grokmod/_inc/fonts/
```
Then choose the matching Font Set in Theme Configuration.

## Credits & Tribute

**Original Theme**
- [jovemlcxx/es-theme-xmb-fcamod](https://github.com/jovemlcxx/es-theme-xmb-fcamod) — base XMB theme for FCAMOD
- Original assets, layout, and structure by jovemlcxx and the projects credited in the original README

**Grokmod**
- Dark mode textbox fix, extra color schemes, and multi-font support by Grok
- Additional color palettes: Pink, Dark Blue, Light Gray, PlayStation Blue, Firefox, Purple Blue

**Your Custom Content**
Feel free to add your own backgrounds, wallpapers, fonts, and further color tweaks.  
If you share or redistribute your version, please keep credit to the original theme and Grokmod.

## License
Same as original (GPL-3.0).  
You are free to modify, share, and expand this theme — just keep the credits.
