# Icon Library

A comprehensive icon library containing organized collections of SVG icons for design and development projects.

## Overview

This repository serves as a version-controlled IconJar library containing 96 curated icon sets with thousands of vector icons. The icons are primarily Material Design icons available in multiple styles and sizes.

## Structure

```
├── Sets/                   # Icon collections (96 sets)
│   ├── {UUID}/            # Individual icon sets
│   │   └── *.svg          # Vector icon files
├── Export Presets/        # IconJar export configurations
├── Swatches/             # Color palette definitions
├── META                  # Library metadata
└── Jars.db              # IconJar database
```

## Icon Styles

Icons are available in multiple Material Design styles:

- **Outlined** - Line-based icons with transparent fills
- **Sharp** - Angular, geometric variants
- **Round** - Rounded corner variants  
- **Twotone** - Two-color filled variants
- **Filled** - Solid filled variants

## Icon Sizes

Most icons are available in standard sizes:
- 20px
- 24px

## Naming Convention

Icons follow a consistent naming pattern:
```
{function}-{style}-{size}px.svg
```

Examples:
- `call-outlined-24px.svg`
- `phone-sharp-20px.svg`
- `email-round-24px.svg`

## Usage

### Direct SVG Usage

Icons can be used directly as SVG files:

```html
<img src="Sets/{set-id}/icon-name-outlined-24px.svg" alt="Icon">
```

### In Web Projects

```html
<svg>
  <!-- Copy SVG content directly -->
</svg>
```

### In Design Tools

Import the entire library into design tools that support IconJar format, or use individual SVG files.

## Icon Sets

The library contains 96 organized icon sets covering categories such as:
- Communication (calls, messaging, email)
- Navigation (arrows, directions, location)
- Media (audio, video, playback controls)
- Devices (hardware, mobile, desktop)
- Maps & Places (locations, transportation)
- And many more...

## File Formats

- **SVG**: Vector icon files (primary content)
- **IconJar Database**: `.db` file containing library metadata
- **Export Presets**: `.ijpreset` files for export configurations
- **Color Swatches**: `.ijcolors` files for color palettes

## Version Information

Library metadata is stored in the `META` file, including:
- Build version
- Build date
- Model version
- Backup date

## Contributing

When adding new icons:
1. Follow the existing naming conventions
2. Ensure SVG files are optimized
3. Place icons in appropriate set directories
4. Update library metadata as needed

## License

Please check individual icon licenses and attribution requirements. Many icons are based on Material Design icons which have specific usage guidelines.