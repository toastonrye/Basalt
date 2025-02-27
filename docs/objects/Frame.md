Frames are like groups or windows. You can add objects on them and if you move the frame, all its children objects will also be moved. Frames also have
some special functionality to create very advanced programs.

[Object](objects/Object.md) methods also apply for frames.

|   |   |
|---|---|
|[addObject](objects/Frame/addObject.md)|Adds a new object
|[setBar](objects/Frame/setBar.md)|Sets the top bar text and colors - deprecated
|[setBarTextAlign](objects/Frame/setBarTextAlign.md)|Sets the top bars text align - deprecated
|[showBar](objects/Frame/showBar.md)|Shows the top bar - deprecated
|[setMonitor](objects/Frame/setMonitor.md)|Sets the frame to be a monitor frame (only for base frames)
|[setMonitorScale](objects/Frame/setMonitorScale.md)|Sets the monitor scale (same as monitor.setTextScale)
|[setMirror](objects/Frame/setMirror.md)|Sets the frame to mirror onto a monitor (only for base frames)
|[getObject](objects/Frame/getObject.md)|Returns the object by its name (or id)
|[removeObject](objects/Frame/removeObject.md)|Removes the object by its name (or id)
|[setFocusedObject](objects/Frame/setFocusedObject.md)|Sets the currently focused object by this frame
|[removeFocusedObject](objects/Frame/removeFocusedObject.md)|Removes the currenlty focused object (it only removes beeing focused)
|[getFocusedObject](objects/Frame/getFocusedObject.md)|Returns the currently focused object
|[setMovable](objects/Frame/setMovable.md)|Makes the frame movable (only for sub frames)
|[setOffset](objects/Frame/setOffset.md)|Sets the frames offset (will be added to the childrens x and y positions)
|[getOffset](objects/Frame/getOffset.md)|Returns the current x and y offset
|[addLayout](objects/Frame/addLayout.md)|Adds a new XML Layout into the frame
|[addLayoutFromString](objects/Frame/addLayoutFromString.md)|Adds a new XML Layout via string into the frame
|[getLastLayout](objects/Frame/getLastLayout.md)|Returns a table of all objects generated by the last addLayout/FromString method
|[setTheme](objects/Frame/setTheme.md)|Sets the theme of that frame and all its childrens
|[setScrollable](objects/Frame/setScrollable.md)|Makes the frame scrollable via mousewheel (internally this uses setOffset)
|[setScrollAmount](objects/Frame/setScrollAmount.md)|Sets how far the user is allowed to scroll

This is how you would implement frames via xml:
```xml
<frame>
    <frame width="parent.w * 0.5" bg="red">
        <button x="2" y="2" width="17" text="Example Button!"/>
    </frame>
    <frame x="parent.w * 0.5 + 1" width="parent.w * 0.5 +1" bg="black">
        <textfield bg="green" x="2" width="parent.w-2" />
    </frame>
</frame>
```