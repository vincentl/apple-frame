# Three Layer Apple Frame

![Six Apple Frames displayed on mantel](https://github.com/vincentl/apple-frame/blob/main/images/display.jpeg)

This project contains SVG files that describe cut lines for a three layer permanent apple shaped picture
frame that is approximately 100 mm (4 in) wide by 105 mm (4.2 in) high. A photo is glued to the bottom layer
that is in the shape of a solid apple with leaf and stem. The middle layer is a thin outline of the
apple, leaf, and stem. The top layer is a thicker frame for just the apple.

## Steps

- On 3mm plywood, cut a top, middle, and bottom layer
- Optionally, cut an L-shaped stand
- Stain the leaf and stem on the bottom layer
- Stain the top layer
- Seal the stained areas with spray lacquer
  ![Front, middle, back layers](https://github.com/vincentl/apple-frame/blob/main/images/layers.jpeg)
- Use the `image-clip.svg` file to clip a image to fit inside the middle layer frame
- Print the image and trim to fit inside the middle frame
- Glue the middle layer to the bottom layer
  ![Middle layer glued to back layer](https://github.com/vincentl/apple-frame/blob/main/images/middle-layer.jpeg)
- Glue the image to the bottom layer
  ![PVA Glue on back layer before photo adhesion](https://github.com/vincentl/apple-frame/blob/main/images/mount-image.jpeg)
- Glue the top layer to the middle layer
  ![Six Apple Frames with Photos](https://github.com/vincentl/apple-frame/blob/main/images/final-assembly.jpeg)
- Glue the stand
  ![Closeup of Apple Frame back with optional stand](https://github.com/vincentl/apple-frame/blob/main/images/back.jpeg)

## Finished Frames

![Three completed Apple Frames](https://github.com/vincentl/apple-frame/blob/main/images/three.jpeg)

## Supplies

- 3mm plywood
- Unicorn Spit Concentrated Paint, Stain & Glaze (mixed to achieve desired shades)
- Watco Semi-Gloss Clear Spray lacquer
- PVA Glue
- Weld Bond Glue

## Inkscape - Scale and Clip a Photo

This section describes how to use [Inkscape](https://inkscape.org) version 1.3.2 to import an image at
a resolution appropriate for printing, scale to fit in the frame, and clip to make cutting easier.

- Open `Inkscape Settings > Imported Images` and change
  - Export resolution to 300 dpi
  - Default import resolution to 300 dpi
- `File > Open...`
  - Select the desired image
  - Choose `Default import solution` radio button
  - Click `OK`
- `File > Import...`
  - Choose the `image-clip.svg` file
  - Choose `Include SVG image as editable object`
  - Click `OK`
- With the `Selector Tool`
  - Double click on the image
  - Control-click on one of the scaling arrows and drag to change the image size
  - Move the Apple outline to frame the desired part of the image
- Open `Layer > Layers and Objects...`
  - Select both the image and path layers
  - Choose the menu option `Object > Clip > Set Clip`
- With the clipped image selected, `File > Export...`
  - Click the `Selection` option
  - Check the DPI is 300
  - Set a file name and location and click `Export`
- Print the exported image without any additional scaling
- Trim away all the unprinted photo paper

## License

Three Layer Apple Frame © 2024 by Vincent Lucarelli is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)
