# Assets Folder Structure

This folder contains all customizable assets for the Ẹjá Pixel Multiplatform game.

## Folder Structure

```
assets/
└── images/
    ├── background/
    │   ├── start-screen-bg.jpg (or .png)
    │   └── game-screen-bg.jpg (or .png)
    └── items/
        ├── good/
        │   ├── item1.png
        │   ├── item2.png
        │   ├── item3.png
        │   └── item4.png
        └── bad/
            ├── item1.png
            ├── item2.png
            ├── item3.png
            └── item4.png
```

## Asset Requirements

### Background Images

1. **start-screen-bg.jpg/png**
   - Dimensions: Recommended 1920x1080 or larger
   - Format: JPG or PNG
   - Description: Background image for the start/menu screen
   - Used in: Start screen overlay

2. **game-screen-bg.jpg/png**
   - Dimensions: Recommended 600x320 or larger (will be cropped/scaled)
   - Format: JPG or PNG
   - Description: Background image for the main game area
   - Used in: Game container background

### Good Items (Collectibles)

These items **decrease stress** when collected:
- **item1.png** - First good item (recommended 32x32px or 64x64px)
- **item2.png** - Second good item
- **item3.png** - Third good item
- **item4.png** - Fourth good item

**Current default:** 💃, 🎵, ✈️, 💰

### Bad Items (Obstacles)

These items **increase stress** when hit:
- **item1.png** - First bad item (recommended 32x32px or 64x64px)
- **item2.png** - Second bad item
- **item3.png** - Third bad item
- **item4.png** - Fourth bad item

**Current default:** 📄, 😠, 💸, 📉

## Image Specifications

- **Format:** PNG (recommended for items with transparency) or JPG (for backgrounds)
- **Item Size:** 32x32px to 64x64px recommended (will be scaled to 32px font-size)
- **Background:** Any size (will be scaled/cropped to fit)
- **Transparency:** Use PNG with alpha channel for items if needed

## Customization

Simply replace the image files in their respective folders with your own assets. The game will automatically load them when you refresh the page.

**Note:** If you want to use different filenames, you'll need to update the paths in `eja-game.html`.
