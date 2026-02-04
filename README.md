# TileMicroscope

A web-based side-by-side image viewer for comparing simulated microscopy images.

## Features

- **Side-by-Side Comparison**: View two simulated images simultaneously with a resizable divider
- **Drag & Drop**: Simply drag and drop images directly onto either panel
- **Tiled Background**: Images are automatically tiled/repeated to fill the viewing area
- **Custom Resolution**: Set pixels-per-picometer ratio to adjust scale bars (10 pm/px default)
- **URL Input**: Load images via file path or URL

## Use Cases

Perfect for comparing different microscopy imaging modes such as:
- HAADF (High-Angle Annular Dark Field)
- ABF (Annular Bright Field)
- Other TEM/STEM imaging techniques

## Usage

1. **Drag & Drop Method** (recommended):
   - Drag an image file onto the left or right panel
2. **URL Method**:
   - Enter the image path/URL in the text field
   - Click "Go" to load the image
3. **Adjust Scale Bar**:
   - Enter pm/pixel value
   - Click "update scale" to adjust the scale bars

## Technical Details

- Pure HTML/CSS/JavaScript with jQuery
- No server required - runs entirely in the browser
- Supports standard image formats (jpg, png, etc.)
- Resizable left panel using CSS resize property


