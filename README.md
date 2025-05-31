# Houf-FangZheng Font Project

![Demo Image](./sampes/demo.png)

## Overview

This project is focused on creating, modifying, and merging fonts, particularly for the HoufFaze-Light and related typefaces. It includes scripts and resources for extracting, fixing, and converting font files, as well as generating previews.

## Directory Structure

- **generated/**: Contains generated font files, configuration, and SVG sources.
- **haifen_fix/**: PNG images used for hyphenation or glyph fixes.
- **haifen_images/**: Additional images for hyphen/glyph processing.
- **new_fonts/**: Output directory for new font files.
- **png_sources/**: Source PNG images for glyphs.
- **sampes/**: Sample images and previews.

## Key Files

- `extract_font.py`: Extracts glyphs from font files.
- `fix_haifen.py`: Script for fixing hyphenation in glyphs.
- `merge_fonts.bat` / `merge_fonts.ff`: Batch and FontForge script for merging fonts.
- `png2svg.py`: Converts PNG images to SVG format.
- `svg2tff.py`: Converts SVG files to TTF font files.
- `demo.html`, `preview-hoanchinh.html`: HTML previews for the fonts.

## Usage

1. **Extract glyphs**:  
   Run `extract_font.py` to extract glyphs from a font file.

2. **Fix hyphens**:  
   Use `fix_haifen.py` to process and fix hyphenation in glyph images.

3. **Convert images**:  
   Use `png2svg.py` to convert PNG glyphs to SVG.

4. **Generate TTF**:  
   Use `svg2tff.py` or the batch scripts to generate TTF font files from SVGs.

5. **Merge fonts**:  
   Use `merge_fonts.bat` and `merge_fonts.ff` to merge multiple font files.

6. **Preview**:  
   Open `demo.html` or `preview-hoanchinh.html` in your browser to preview the fonts.

## Requirements

- Python 3.x
- [FontForge](https://fontforge.org/) (for merging fonts)
- Additional Python packages as required by the scripts

## License

See individual font files and scripts for license information.

---

For more details, refer to the scripts and configuration files in the repository.
