# Widgets module
The `utils` module defines the utilities of the GUI.

## colorTable

* `hexToRGB`: Change the HEX color values to RGB color values.
* `mapLabelID2RGB`: Map the matrices value to RGB color values.
* `mapLabelsToColors`: Return the dict that maps label to RGB.
* `mapMaskLabelToRGB`: Map the gray picture to RGB and return the R,G,B channels individually.

## config

* Class `const` defines the constants of the minimum image width and height, along with the colors.

## icon

* Class `icons` defines the icons of buttons. `# TODO: @classmethod`
    * `init_icons`: Defines the icons of the buttons
    * `__getitem__`: Defines the method to add colors on icons (icons would be colored when click it)

## utils

* `processPILImageWithFlip`: Define the function to flip the images (translations ops).
* `initImageObjFromNifity`: Load the raw nifty data to image objects.
* `prompt`: 
* `cutv`: Cut the volume of the organs
* `theRectPen`: Define the rectangular pen
* `theCrossPen`: 
* `theBoundaryPen`: 
* `theBrushPen`:
* `wrappaste`:
* `affineMapping`: Map the 3D images along specific axis.
* `computeViewSizeByNumImages`: 
* `computeMargin`:
* `updateIndexWithAxis`: Update the indices by the axis directions.
* `computeCoordinateByGrid`: Compute the coordinates by viewer size.
* `getImageSizeByAxis`: Get the image size by the axis directions.
* `handleImageDropEvent`: handler to control the operations when drag and drop *.nii files to GUI. 