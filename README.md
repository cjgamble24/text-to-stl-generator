# text-to-stl-generator

## Overview

This project is a simple Python GUI tool for generating 3D printable STL files of custom text labels. It uses OpenSCAD to create a block with your chosen text embossed or recessed, and automatically sizes the block so the text always fits. You can select from several fonts, including free and system fonts, and export the result as an STL for 3D printing.

### Features
- Enter any label text and choose from several fonts
- Plate is automatically sized to fit the text (fixed width, dynamic length)
- Choose between raised (embossed) or recessed text
- Preview the 3D model before exporting
- Export to STL for 3D printing

### Requirements
- Python 3.x
- Pillow (PIL) library
- OpenSCAD (must be installed and path set in the script)

### Adding Fonts
To use a custom font, add the TTF file to your system's font directory (e.g., `C:\Windows\Fonts`) and update the font list in the script if needed.

#### AldotheApache Font
This project includes support for the free "AldotheApache" font, which you can download here:
https://dl.dafont.com/dl/?f=aldo_the_apache

After downloading, install the font on your system so both Pillow and OpenSCAD can use it.

---
For any issues or suggestions, please open an issue or pull request.