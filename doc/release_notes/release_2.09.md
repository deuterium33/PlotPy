# Version 2.9 #

## PlotPy Version 2.9.0 ##

💥 New features:

* Added `QuiverItem` for displaying 2D vector fields (quiver plots), similar to
  Matplotlib's `quiver`. This closes
  [Issue #54](https://github.com/PlotPyStack/PlotPy/issues/54):
  * New `QuiverItem` plot item class supporting X, Y, U, V arrays (1D or 2D)
  * Auto-meshgrid expansion when X, Y are 1D and U, V are 2D
  * Configurable arrow scale, head size, and color
  * New `make.quiver()` builder method for easy item creation
  * New `quiver()` function in the interactive plotting interface (`plotpy.pyplot`)
  * Integrated with plot autoscale (initial zoom and middle-click reset)
  * Item icon displayed in the item list widget
