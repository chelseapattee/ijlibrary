# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an IconJar icon library repository containing organized icon sets in vector format. The library serves as a version-controlled collection of SVG icons and related assets for design and development use.

## Repository Structure

- `Sets/`: Contains 96 icon set directories organized by UUID
  - Each set directory contains SVG icon files (typically Material Design icons)
  - Icons follow naming convention: `{name}-{style}-{size}px.svg` (e.g., `call-outlined-24px.svg`)
  - Common styles include: outlined, sharp, round, twotone, filled
  - Common sizes: 20px, 24px
- `Export Presets/`: Contains IconJar export presets (`.ijpreset` files)
- `Swatches/`: Contains color swatch definitions (`.ijcolors` files) 
- `META`: XML metadata file with library version and build information
- `Jars.db`: SQLite database containing IconJar library metadata

## File Types

- **SVG Files**: Vector icon assets - these are the primary content
- **Binary Files**: 
  - `Jars.db` (SQLite database)
  - `.ijpreset` files (binary plist format)
  - `.ijcolors` files
- **Metadata**: XML configuration in `META` file

## Common Operations

Since this is primarily an asset library without build processes:

### Working with Icons
- Icons are organized in UUID-named directories under `Sets/`
- Each icon is a standalone SVG file
- Icons can be viewed, copied, or referenced directly

### Version Control
- This repository tracks changes to icon assets over time
- The `META` file contains version and build date information
- Database file `Jars.db` contains IconJar-specific metadata

### No Build System
This repository contains static assets and does not have:
- Package managers (no package.json, requirements.txt, etc.)
- Build scripts or Makefiles
- Test frameworks
- Development servers

## Icon Naming Conventions

Icons follow Material Design naming patterns:
- `{function}-{variant}-{size}px.svg`
- Examples: `call-outlined-24px.svg`, `phone-sharp-20px.svg`
- Variants: outlined, sharp, round, twotone, filled

## Working with this Repository

When working with this icon library:
1. Browse icon sets in `Sets/` directories to understand available icons
2. Reference icons by their full path when using in projects
3. Be cautious when modifying the `Jars.db` file as it's binary
4. Export presets can be used to configure how icons are exported from IconJar