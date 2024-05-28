# The Pluvionauts: a Free(Libre) board game

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

The official repository of the board game "The Pluvionauts".
This repository contains the assets of "The Pluvionauts" board game project (in case you want to build the game yourself and/or edit the design of the game).

For more information about the game and the project, feel free to checkout [the project website](https://pluvionauts.github.io/).

## Requirements

Currently, the project heavily relies on:

1. The software [Inkscape](https://inkscape.org/) (ideally the latest version).
2. [Inkscape Extensions to Manage Image Links](https://github.com/pluvionauts/inkscape_manage_image_links#inkscape-extensions-to-manage-image-links), a set of Inkscape extensions created for the project (optional).
3. The software [SolveSpace](https://solvespace.com/index.pl) for 2D CAD (optional).

## Usage

In all designs of this repository:
* **red paths** are intended to be used as **cut paths**
* **green paths** are intended to be used as paths for **line engraving**
* **paths filled with black** are intended to be used as paths for **surface engraving**

### Quick Start (Recommended for personal use)

1. Open the SVG files [assets/merge/cumulus/305_x_610/merge_0.svg](assets/merge/cumulus/305_x_610/merge_0.svg) and [assets/merge/cumulus/305_x_610/merge_1.svg](assets/merge/cumulus/305_x_610/merge_1.svg) with Inkscape.
2. Edit anything as you see fit.

You could directly send the design to your laser-cutting device however the design might be a little heavy as it is.
If that is the case, use the following steps to lighten the svg file.

3. Combine every red path together:
	- Double-Click continuously on a red path until a single red path is selected.
	- `Right-Click > Select Same > Stroke Color` to select all red paths.
	- `Path -> Combine` to combine all red paths.
	- Then `Right-Click > Move to Layer` and select root layer to move the combined red path to the root layer.
4. Perform the same steps to combine the green paths together.
5. Then delete every empty group from the document: Box select the entire drawing, then `Edit > Invert Selection` and press `delete`.
6. You may also run `Edit > Clean Up Document` and you should be good to go.

### Clean Contribution (Recommended to contribute to this repository)

1. Open and edit any SVG file in the repository.
2. Open any SVG file that links to the file you edited, select it and run the **SVG Image Link -> Embeded SVG** extension to update it.
3. Perform then the **Quick Start** steps to obtain a clean export file.

If one wants to change a **blueprint** file, ideally one would open the corresponding **.slvs** file with **SolveSpace** then edit the design from there and then export the blueprint into a **.svg** file from there.

## TODO

- [ ] Translate the game in English.
- [ ] Automate updating svg links.
- [ ] Automate the export process.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

**Important:** Authors of all modifications, corrections or contributions to this repository accepts to release their work under the same license. 
This does not apply if you fork this repository.

All resources here (images, videos and more) are under the same license.
