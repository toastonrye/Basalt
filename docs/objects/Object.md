This is the base class for all visual objects. It covers positioning, sizing, showing/hiding and much more.

By default a freshly created object is visible and automatically listens to all incoming events. 
Its default position is always 1, 1 (based on it's parent frame). The default anchor is also topLeft.

|   |   |
|---|---|
|[show](objects/Object/show.md)|Makes the object visible
|[hide](objects/Object/hide.md)|Makes the object invisible
|[isVisible](objects/Object/isVisible.md)|Returns if the object is currently visible
|[enable](objects/Object/enable.md)|Listens to incoming events
|[disable](objects/Object/disable.md)|Ignores all incoming events
|[setPosition](objects/Object/setPosition.md)|Changes the position (x,y)
|[getPosition](objects/Object/getPosition.md)|Returns the current position
|[setBackground](objects/Object/setBackground.md)|Changes the object's background
|[setForeground](objects/Object/setForeground.md)|Changes the object's text color
|[setSize](objects/Object/setSize.md)|Changes the object to a new size
|[getSize](objects/Object/getSize.md)|Returns the width and height
|[setFocus](objects/Object/setFocus.md)|Changes the object to be the focused object
|[isFocused](objects/Object/isFocused.md)|Returns if the object is currently focused
|[setZIndex](objects/Object/setZIndex.md)|Changes the z-index
|[setParent](objects/Object/setParent.md)|Changes the parent of that object
|[getAnchorPosition](objects/Object/getAnchorPosition.md)|Returns the relative x and y coordinates of that object
|[setAnchor](objects/Object/setAnchor.md)|Sets the current anchor
|[getAbsolutePosition](objects/Object/getAbsolutePosition.md)|Returns the absolute x and y coordinates of that object
|[setValue](objects/Object/setValue.md)|Changes the stored value
|[getValue](objects/Object/getValue.md)|Returns the currently stored value
|[getName](objects/Object/getName.md)|Returns the name (or in other words: id) of that object
|[setShadow](objects/Object/setShadow.md)|Changes the shadow of that object
|[setBorder](objects/Object/setBorder.md)|Changes the border lines

# Events

|   |   |
|---|---|
|[onClick](objects/Object/onClick.md)|Fires as soon as the object gets clicked
|[onClickUp](objects/Object/onClickUp.md)|Fires as soon as the mouse button gets released on the object
|[onScroll](objects/Object/onScroll.md)|Fires as soon as you scroll with the mousewheel 
|[onDrag](objects/Object/onDrag.md)|Fires as soon as the object is beeing dragged
|[onKey](objects/Object/onKey.md)|Fires when the object is focused and a keyboard key has been clicked
|[onKeyUp](objects/Object/onKeyUp.md)|Fires when the object is focused and a keyboard key has been released
|[onChange](objects/Object/onChange.md)|Fires when the object value has been changed
|[onResize](objects/Object/onResize.md)|Fires when the object got resized
|[onReposition](objects/Object/onReposition.md)|Fires when the object has been repositioned
|[onGetFocus](objects/Object/onGetFocus.md)|Fires when the object is focused
|[onLoseFocus](objects/Object/onLoseFocus.md)|Fires when the object lost it's focus