# menubar module
The `menubar` module defines the functions of the mouse and keyboard actions.

## dialogues

* `getValidFile`: Get the valid *.nii files.
* `checkMainImageLoaded`: Return bool. Open dialogue to show error message and check whether main image has been loaded.
* `checkImageSize`: Return bool. Open dialogue to show error message and check whether the dimension of *.nii is 3D.
* `checkSizeEqual`: Return bool. Open dialogue to show error message and check whether the two loaded *.nii have the same size.
* `checkSaveCurrentSegmentation`: Return bool. Open dialogue to select the options of segmentation and check whether the segmentation has been saved.

## mainMenuBar

* Class `mainMenuBar` defines the menu component of the menu bar.
    * `openImageAction`: Define open the valid image files action.
    * `openImage`: Open the main image with 3 dimensions.
    * `addImageAction`: Define add the valid image files action.
    * `addImage`: Open the additional image with the same size as the main image.
    * `dragOpenImageAction`: Define drag and drop to open the valid image files action.
    * `dragAddImageAction`: Define drag and drop to add the valid image files action.
    * `dragOpenMaskAction`: Define drag and drop to open the valid segmentation files action.
    * `newSegmentationAction`: Define the action to save previous segmentation and update the mask status.
    * `openSegmtationAction`: Define open the valid segmentation files action.
    * `openSegmtation`: Load the corresponding segmentation that has the same size as the main image when main image is loaded.
    * `saveSegmtationAction`: Define the save action of the segmentation when the main image is loaded.
    * `setProps`: Set the status of the loading process.
    * `update`: Update the prompt of the object. 

## menuComponent

* Class `menuComponent` define the class method of menu component
    * `_applyStructure`: Add menu contents and corresponding actions to the GUI.