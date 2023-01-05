# Macros and Plugins for ImageJ
These are going to be my list of macros and plugins for ImageJ. I'll be developing them as and when require. Copy these in the `/macros/StarupMacros.txt` file so that they will be loaded when ImageJ starts up.

* `GridPlot.txt`  
The default macro of generating grid on the ImageJ does not create a grid which is initialised at the origin. This macro creates girds of horizontal and vertical lines which is initialised at the origin of the image.
	* Add this to `/macros/StarupMacros.txt` file.
	* Restart ImageJ.
	* The macro will be available on the toolbar with `+` symbol.

By default it creates a `10X10` grid which can be changed by editing the line `nLines = 10`.

* `Sharpening.ijm.rtf`  
This will sharpen the opened image.  
This macro is under development where I want to creat a button on the toolbar of ImageJ.

# Disclaimer
No copyright infringement intended. These codes are not associated with ImageJ. You can modify them but do it at your own risk.  
ImageJ can be downloaded from its official [website](https://imagej.nih.gov/ij/download.html).

ImageJ is an excellent tool for converting images from one format to another.
