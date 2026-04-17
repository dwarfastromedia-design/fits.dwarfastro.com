# FITS Studio

FITS Studio is a free, browser-based FITS processor built for **DWARF 3 stacked FITS files**.

I built it because I wanted more control than the default smart telescope workflow, but without the friction and learning curve of traditional desktop tools. The goal is simple: take a linear stacked FITS from the DWARF 3 and make it practical to process right in the browser.

## Live app

[fits.dwarfastro.com](https://fits.dwarfastro.com)

## What it does

- Background extraction
- Channel neutralization after gradient removal
- Stretch tools including **GHS**, **Asinh**, and **MTF**
- Multi-pass editing with history
- Fast preview workflow
- Full-resolution processing in the browser
- Designed around **DWARF 3** linear stacked FITS files

## Why it exists

The DWARF 3 already makes it easy to capture and stack data. What I wanted next was a cleaner way to process those stacked FITS files with more control over gradients, color balance, and stretching, without needing a heavy desktop workflow for every edit.

FITS Studio is meant to fill that gap.

## Privacy

Your FITS file stays on your machine. The app runs in the browser and does not upload your image for processing.

## Who it is for

FITS Studio is built first for the **DWARF 3 community**, but anyone working with compatible linear FITS files may find it useful.

## License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.
