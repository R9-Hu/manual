# viewer module
The `viewer` module defines the functions of the mouse and keyboard actions.

## Viewer2D

* Class `Viewer2D` defines the interface of rendering and actions of GUI
    * `uiInit`: Initialize the setup of UI
    * `renderStyle`:
    * `update`: Update the size of scence
    * `mousePressEvent`: Define the 
    * `mouseMoveEvent`: 
    * `mouseReleaseEvent`:
    * `resizeEvent`:
    * `wheelEvent`: 
    * `dragEnterEvent`
    * `dragMoveEvent`
    * `dropEvent`

## ViewerPanel

* Class `ViewerPanel` defines the actions of GUI panel.
    * `uiInit`: Initialize the layout of panels
    * `renderStyle`: Set margin and spacing of the layout.
    * `update`: Update the parameters of scenes.
    * `showOrHide`: Determine whether to show an image.
    * `zoomToFit`: Update the image display and parameters after zooming.
    * `mouseStateChange`: 
    * `viewSizeChange`:
    * `maskChange`:
    * `displayChangeAction`:
    * `wheelValueChange`:
    * `indexChangeValue`:
    * `setIndex`:

## ViewerManager

* Class `ViewerManager` defines the parameters of images.
    * `uiInit`: Initialize the parameters of images.
    * `renderStyle`: Set margin and spacing of the layout.
    * `update`: Update the parameters of images.