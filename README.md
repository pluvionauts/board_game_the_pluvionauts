# The Pluvionauts: a Free(Libre) board game

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

**NOTE: Everything in this repository is currently WORK IN PROGRESS! A lot of things are not up to date. A lot of changes are to be expected in the next few weeks.**

The official repository of the board game "The Pluvionauts".
This repository contains all numeric assets of "The Pluvionauts" board game project.

## Requirements

Currently, the project heavily relies on:

1. the software [Inkscape](https://inkscape.org/) (the last version is recommended)
2. [Inkscape Extensions to Manage Image Links](https://github.com/pluvionauts/inkscape_manage_image_links#inkscape-extensions-to-manage-image-links), a set of Inkscape extensions

## Usage

### Quick and Dirty way (Recommended for personal use)

1. Open an SVG file located in the directory [assets/merge/400_x_400_color](assets/merge/400_x_400_color) with Inkscape
2. Select all images of the file: Ctrl + A
3. Run the **SVG Image Link -> Embeded SVG** extension: `Extensions menu > The Pluvionauts > SVG Image Link -> Embeded SVG`
4. Edit anything as you see fit.

TODO: THESE FOLLOWING STEPS SHOULD BE AUTOMATED IN THE FUTURE

5. Export all red borders as a DXF file
6. Export everything else as a PNG file

The DXF files are to be used for laser cutting.
The PNG files are to be used for printing.

### Clean way (Recommended to contribute to this repository)

1. Open and edit any SVG file in the repository

TODO: THESE FOLLOWING STEPS SHOULD BE AUTOMATED IN THE FUTURE

2. Open any SVG file that links to the file you edited, select it and run the **SVG Image Link -> Embeded SVG** extension to update it.
3. Save that file and perform theme all the steps of the **Quick and Dirty way** in you want to export it for production.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

**Important:** Authors of all modifications, corrections or contributions to this repository accepts to release their work under the same license. 
This do not apply if you fork this repository.

All resources here (images, videos and more) are under the same license.
