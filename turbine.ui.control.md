<a href="index">Home</a> > <a href="turbine.ui">Turbine.UI</a>

<h1>Control Class</h1>
<hr/>
<sub style="color:red; font-weight:bold">Beta Documentation - Subject to change.</sub>

The base control class for all available user interface elements.

## Inheritance Hierarchy
<a href="turbine.object">Turbine.Object</a>
* Turbine.UI.Control
	* Turbine.UI.ScrollableControl
	* Turbine.UI.ScrollBar
	* Turbine.UI.TreeNode
	* Turbine.UI.Window
	* Turbine.UI.Lotro.BaseItemControl
	* Turbine.UI.Lotro.EffectDisplay
	* Turbine.UI.Lotro.EntityControl
	* Turbine.UI.Lotro.Quickslot

## Remarks
To use the Chat Object, you will need to `import "Turbine.UI.Lotro"` at the top of the file it will be used.

## Members
<details>
<summary>Methods</summary>
	
| Name | Inherited | Description |
| --- | ---: | --- |
| Focus | | Request that the control take focus. |
| GetAllowDrop | | Gets if the control supports drop operations from drag and drop. |
| GetBackColor | | Gets the solid background color of the control. |
| GetBackColorBlendMode | | Gets the blend mode applied to the background color. |
| GetBackground | | Gets the background graphic of the control. |
| GetBlendMode | | Gets the blend mode applied to the background image. |
| GetControls | | Gets the list of child controls. |
| GetHeight | | Gets the height of the control. |
| GetLeft | | Gets the left coordinate of the control. |
| GetMousePosition | | Gets the mouse position relative to this control. |
| GetOpacity | | Gets the opacity of the window. |
| GetParent | | Gets the parent of the control. |
| GetPosition | | Gets the position of the control. |
| GetSize | | Gets the size of the control. |
| GetTop | | Gets the top coordinate of the window. |
| GetWantsKeyEvents | | Gets a flag indicating if the control wants to receive key events. |
| GetWantsUpdates | | Gets the flag indicating if the control wants to receive Update notifications |
| GetWidth | | Gets the width of the control. |
| GetZOrder | | Gets the Z ordering index of the control. |
| HasFocus | | Returns true if the control has focus. |
| IsAltKeyDown | | Test if the alt key is pressed. |
| IsControlKeyDown | | Test if the control key is pressed. |
| IsDisplayed | | Gets a flag indicating if the control is displayed. |
| IsEnabled | | Gets a flag indicating if the control is enabled. |
| IsMouseVisible | | Gets a flag indicating if the mouse will see this control. |
| IsShiftKeyDown | | Test if the shift key is pressed. |
| IsVisible | | Gets a flag indicating if the control is visible. |
| PointToClient | | Converts a coordinate from control space to screen space. |
| PointToScreen | | Converts a coordinate from control space to screen space. |
| SetAllowDrop | | Sets if the control supports drop operations from drag and drop. |
| SetBackColor | | Sets the background color of the control. |
| SetBackColorBlendMode | | Sets the blend mode applied to the background color. |
| SetBackground | | Sets the background image of the control. |
| SetBlendMode | | Sets the blend mode applied to the background image. |
| SetEnabled | | Sets a flag indicating if the control is enabled. |
| SetHeight | | Sets the height of the control. |
| SetLeft | | Sets the left coordinate of the window. |
| SetMouseVisible | | Gets a flag indicating if the mouse will see this control. |
| SetOpacity | | Sets the opacity of the window. |
| SetParent | | Sets the parent of the control. |
| SetPosition | | Sets the position of the control. |
| SetSize | | Sets the size of the control. |
| SetTop | | Sets the top coordinate of the window. |
| SetVisible | | Sets the visible flag of a control. |
| SetWantsKeyEvents | | Sets a flag indicating if the control wants to receive key events. |
| SetWantsUpdates | | Sets the flag indicating if the control wants the receive update notifications. |
| SetWidth | | Sets the width of the control. |
| SetZOrder | | Sets the Z order of the control. |

</details>

<details>
<summary>Events</summary>

| Name | Inherited | Description |
| --- | ---: | --- |
| DragDrop | | Event fired when a drag drop operation is completed. |
| DragEnter | | Event fired when a drag drop operation enters the control. |
| DragLeave | | Event fired when a drag drop operation leaves the control. |
| DragStart | | Event fired when a drag drop operation starts the control. |
| EnabledChanged | | Event fired when the enabled state of the control changes. |
| FocusGained | | Event fired when the control gains focus. |
| FocusLost | | Event fired when the control loses focus. |
| KeyDown | | Event fired when a key is pressed down. |
| KeyUp | | Event fired when a key is released. |
| MouseClick | | Event fired when a mouse button is clicked. |
| MouseDoubleClick | | Event fired when a mouse button is double clicked. |
| MouseDown | | Event fired when a mouse button is pressed. |
| MouseEnter | | Event fired when the mouse enters the control. |
| MouseHover | | Event fired when the mouse is hovering over the control. |
| MouseLeave | | Event fired when the mouse leaves the control. |
| MouseMove | | Event fired when the mouse moves. |
| MouseUp | | Event fired when a mouse button is released. |
| MouseWheel | | Event fired when a mouse wheel moves. |
| PositionChanged | | Event fired when the position of the control changes. |
| SizeChanged | | Event fired when the size of the control changes. |
| Update | | Event fired every frame when WantsUpdates is enabled. |
| <a href="turbine.ui.control.visiblechanged">VisibleChanged</a> | | Event fired when the visible state of the control changes. | 

</details>

## Examples
<details><summary>Basic</summary>

** Coming Soon **
```lua
```

</details>

<details><summary>Intermediate</summary>

** Coming Soon **
```lua
```

</details>

<details><summary>Complex/Advanced</summary>

** Coming Soon **
```lua
```

</details>
<br/>

## See Also
- <a href="turbine.ui">Turbine.UI</a>

<hr/>
<sub>Copyright &copy; Standing Stone Games, LLC.  All rights reserved.</sub>
