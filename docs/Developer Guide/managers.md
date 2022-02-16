# managers module
The `managers` module defines the functions of the mouse and keyboard actions.

## functions

* `drawOrEraseWithLabel`: Defines the functions to draw or erase the masks.
* `generateBoxCoordinates`: Generate the top left coordinates, width and height of the box. 
* `getSliceByAxis`: Get the image slice by the axis directions.
* `updateMaskByAxisPos`: Update the mask by the axis directions.

## keyStateManager

* Class `keyStateManager` defines the actions of keyboard.
    * `keyStateChange`: Update the status when specific keys has been pressed.
    * `handleParamChange`: Change the parameters of the image status.
    * `handleOpaChange`: Change the opacity of the mask layer. 

## mouseStateManager

* Class `mouseStateManager` define the actions of mouse.
    * `emitTransChange`: 

## rootState

* Class `rootState` define the 