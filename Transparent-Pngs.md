If you're using photoshop you might run into issues when exporting transparent pngs.

## Problem

When saving a png with full transparency, photoshop changes the pixels behind the transparency to white. This can be an issue with textures because of things like mipmaps and bilinear filtering cause those white pixels to bleed, leading to ugly white lines down the side of your textures.

## Solution

There's a Png plugin called [SuperPNG](http://www.fnordware.com/superpng/). This will save your Pngs without messing with them.

## Tips

* When opening a Png in photoshop hold down shift to see the SuperPNG an import menu