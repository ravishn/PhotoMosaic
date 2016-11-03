# PhotoMosaic

Photo mosaic
------------

Javascript/HTML program to create a photo mosaic

The goal of this project is to implement the following flow in a client-side app.
1. Select a local image file.
2. The app loads that image, divides the image into tiles, computes the average
   color of each tile, fetches a tile from the server for that color, and
   composites the results into a photomosaic of the original image.
3. The composited photomosaic will be displayed according to the following
   constraints:
    - tiles should be rendered a complete row at a time (a user should never
      see a row with some completed tiles and some incomplete)
    - the mosaic should be rendered from the top row to the bottom row.
