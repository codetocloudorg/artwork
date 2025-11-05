# Download Packages

This directory will contain organized ZIP packages of Code To Cloud artwork for easy downloading.

## Available Packages (Coming Soon)

### `code_to_cloud_current_logos.zip`
Contains all current logo variations in both PNG and SVG formats:
- Black logos (standard and transparent)
- Black logos with text (standard and transparent)
- Organized by format and type

### `code_to_cloud_print_ready.zip`
High-resolution assets optimized for print use:
- Vector SVG files for unlimited scaling
- High-DPI PNG files (300+ DPI equivalent)
- CMYK color profile information

### `code_to_cloud_web_ready.zip`
Web-optimized assets in multiple sizes:
- PNG: 32px, 64px, 128px, 256px, 512px
- SVG files for responsive design
- Optimized file sizes for fast loading

### `code_to_cloud_wallpapers.zip`
Desktop wallpapers in all available resolutions:
- 1920x1080 (Full HD)
- 2560×1440 (QHD)
- 3840×2160 (4K UHD)

## Creating Packages

To create these packages, run the following commands from the repository root:

```bash
# Create current logos package
zip -r downloads/code_to_cloud_current_logos.zip examples/images/current/

# Create web-ready package (would need resized versions)
# zip -r downloads/code_to_cloud_web_ready.zip examples/images/current/ examples/web-sizes/

# Create wallpapers package
zip -r downloads/code_to_cloud_wallpapers.zip examples/images/current/*desktop* examples/images/legacy/*desktop*
```

*Note: These packages will be created and maintained by the repository maintainers.*