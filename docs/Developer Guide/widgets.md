# Widgets module
The `Widgets` module mainly defines the display of the images.

## sliceSlider

* class `sliceSlider` defines the display style and function of the MRI images.
    * `uiInit`: Initialize the layout of the image display region of GUI.
    * `update`: Update the image display (i.e. cursor position)
    * `toggleViewAction`: Define toggle between different images  
    * `toggleTileAction`: Define toggle between tiles
    * `sliderAction`: Defines the axis move and indices in the image region.
    * `renderStyle`: Set the render style of the image region.

## viewerLowerPanel

* class `viewerLowerPanel` defines the lower panel of the GUI.
    * `uiInit`: Initialize the layout of the lower panel.
    * `renderStyle`: Set the render style of the button (zoom to fit).
    * `buttonAction`: Set the button actions.
    * `update`: Update the index of the slice.