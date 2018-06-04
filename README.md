# ALIT - A large-image tiler

This is a utility that I wrote to help me with my work. It consists of a simple
graphical interface which allows a user to tile a (very large) image 
in a timely manner. 
Professional graphic editors possess
similar features, though I was surprised to learn that no commercial 
software really does what I need, which is the following:

- Load and tile very large TIFF images (~700 Mb) in a few seconds. 
- To easily draw, drag, and resize grids to conveniently choose the tiling pattern.
- To be able to save files following the labels of a 96-well plates 
(commonly used in biology). 

The screenshot gives you an idea of what the software accomplishes and how 
it works. Enjoy!

![alt text][screenshot]

[screenshot]: https://github.com/lewlin/grid-image-cropper/blob/master/main_screenshot.png "Screenshot"


## Installation
`ALIT` is written in `Python 3` and requires the `PyQt5` library and this 
should be everything you need. Currently, `ALIT` cannot be installed using 
`pip`, but I might distribute it as a Python package in future releases. 


## How to use

- Load the TIFF image you want to tile using the *Load TIFF button*. TIFF is
the only image type currently supported.
- To draw a grid, left-click with the mouse and move the pointer. A second 
left-click places the grid, right-click to cancel. The result will look similar 
to the following (omitting a background image for clarity) 


![alt text][screenshot]

[screenshot]: https://github.com/lewlin/grid-image-cropper/blob/master/howto_screenshot_1.png "Screenshot"


