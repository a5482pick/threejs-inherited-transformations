**A demonstration of coupling and decoupling ancestor and descendant objects in _three.js_.**


_THREE.SceneUtils_ is used to show how a structure rendered in _three.js_ may be temporarily (fully or partially) decoupled from e.g. its parent. &nbsp;In this demonstration, the smallest rendered box is a child of the largest, yet it is decoupled so that it inherits the largest box's rotation but not its translation (i.e. the smallest box rotates but doesn't translate). &nbsp;Also demonstrated is how e.g. 'grandchildren' superimpose their ancestor's transformations (in this case the rotation property) upon their own.

Drag the mouse to see renderings from other positions.

(Additionally, an unused function is provided that may nonetheless be used to return an object's screen position.)
