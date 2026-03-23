# 🎬 Jellyfin Banner Generator

A browser-based tool for creating custom library banner images for your [Jellyfin](https://jellyfin.org/) media server. No installation, no account, no server needed.

#***👉 [Open the generator](https://stradios.github.io/Custom-Jellyfin-library-banners/)***

---

## What is it?

Jellyfin lets you upload custom images for each of your media libraries (Movies, TV Shows, Music, etc.). These images show up as large cards on your home screen. The problem is making them — most people either use generic stock images or skip them entirely.

This tool lets you design and export those banners directly in your browser. Pick a library, choose colours, fonts, patterns and an emoji, preview it live, and download a 1536×1024px PNG ready to upload straight into Jellyfin.

---

## Features

### 🎨 Full visual control
- **Background colour** with a radial gradient centre glow
- **Accent colour** drives the left bar, underline, and geometric pattern tint
- **Text colour** and **icon/bokeh colour** separately adjustable
- All colours have both a **native colour picker** and a **hex input field** — type `#ff0000` directly or use the picker, they stay in sync

### 🔤 Typography
- **28 Google Fonts** in a custom dropdown — each font name is displayed in its own typeface so you can see what you're picking before committing
- Font weight: Light / Regular / Bold / Black
- **Auto-fit text sizing** — slider sets the title as a percentage of image width (10–85%), so the text always fills exactly the space you want regardless of font or title length
- Text alignment: Left / Centre / Right

### 😄 Emoji overlay (OpenMoji)
- Built-in emoji picker with **7 categories** and a search field
- Uses [OpenMoji](https://openmoji.org/) — open-source, CC BY-SA 4.0
- Full control over **size**, **opacity**, and **position**:
  - 3×3 grid: top-left, top-centre, top-right, mid-left, centre, mid-right, bottom-left, bottom-centre, bottom-right
  - Layer: behind text or in front of text
  - Inline: before or after the title, perfectly aligned with the text

### 🌐 Background effects
- **Bokeh** — soft glowing light blobs (adjustable amount and size)
- **8 geometric patterns**: Hex grid, Triangle mesh, Circuit lines, Diamond grid, Dot matrix, Chevrons, Crosshatch, or None
- **Vignette** — dark edge fade
- **Film grain** overlay
- Accent bar (left edge highlight) and underline beneath title text

### 📚 Library presets
Comes with presets for the most common Jellyfin libraries, each with its own colour palette and default emoji:

| Library | Default palette |
|---|---|
| Movies | Dark blue |
| TV Shows | Dark green |
| Music | Deep purple |
| Music Videos | Dark magenta |
| Anime | Dark red |
| Books | Warm amber |
| Kids | Emerald green |
| Documentary | Neutral grey |
| 4K / UHD | Indigo |
| Sports | Olive green |
| Stand-up | Burnt orange |
| Home Videos | Deep violet |
| Custom | Black |

Clicking a library auto-applies its colour palette. **Quick palette buttons** let you swap the full colour set in one click.

### 💾 Export
- **Download PNG** — exports the current banner as a 1536×1024px PNG
- **Download All** — batch exports every library preset as individual PNGs, auto-named `jellyfin-banner-movies.png` etc.

---

## Output size

Banners are generated at **1536×1024px**. Jellyfin displays library images at roughly half that size (768×512), so the extra resolution keeps them sharp on high-DPI screens.

---

## How to use it in Jellyfin

1. Open the generator and design your banner
2. Click **Download PNG**
3. In Jellyfin, go to **Dashboard → Libraries**
4. Click the three dots (⋯) next to a library → **Edit**
5. Scroll to the image section and upload your PNG
6. Save — the new banner appears on your home screen immediately

---

## Credits & licences

| Component | Licence |
|---|---|
| [OpenMoji](https://openmoji.org/) emoji set | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Google Fonts](https://fonts.google.com/) (Raleway, Cinzel, Orbitron, etc.) | Various open licences (SIL OFL, Apache 2.0) |

> All emojis designed by [OpenMoji](https://openmoji.org/) — the open-source emoji and icon project. License: CC BY-SA 4.0

---

## Contributing

Pull requests welcome. Some ideas for future improvements:

- Upload a custom background image
- Text shadow / outline options
- More silhouette icon sets per library type
- Export as SVG

---

*Made for the Jellyfin community. Not affiliated with the Jellyfin project.*
