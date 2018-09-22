# Work 9
#### Scanline conversion
* Create a new function that handles the scanline conversion.
* Call this in your draw_polygons function.
* Make sure that you change color values for each triangle.
#### z-buffering
* In the base files provided, I've added a z-buffer argument to the necessary functions, but have not done anything with it.
* The z-buffer should only be modified in your plot function, or when clear_zbuffer is called.
* You will need to calculate z values in both scanline_convert and draw_line.
* Your z values are not limited to the integers.
