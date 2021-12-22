<a href="index">Home</a> > <a href="turbine.ui.lotro">Turbine.UI.Lotro</a>

<h1>Quickslot Class</h1>
<hr/>
<sub style="color:red; font-weight:bold">Beta Documentation - Subject to change.</sub>

A quickslot control contains all the functionality to create custom quickslots that can represent skills, items, alias, etc.

## Inheritance Hierarchy
<a href="turbine.object">Turbine.Object</a>
* <a href="turbine.ui.control">Turbine.UI.Control</a>
	* Turbine.UI.Lotro.Quickslot

## Remarks
To use the Chat Object, you will need to `import "Turbine.UI.Lotro"` at the top of the file it will be used.

## Members
<details>
<summary>Methods</summary>
	
| Name | Inherited | Description |
| --- | ---: | --- |
| Focus | <a href="turbine.ui.control">Control</a> | Request that the control take focus. |
| GetAllowDrop | <a href="turbine.ui.control">Control</a> | Gets if the control supports drop operations from drag and drop. |
| GetBackColor | <a href="turbine.ui.control">Control</a> | Gets the solid background color of the control. |
| GetBackColorBlendMode | <a href="turbine.ui.control">Control</a> | Gets the blend mode applied to the background color. |
| GetBackground | <a href="turbine.ui.control">Control</a> | Gets the background graphic of the control. |
| GetBlendMode | <a href="turbine.ui.control">Control</a> | Gets the blend mode applied to the background image. |
| GetControls | <a href="turbine.ui.control">Control</a> | Gets the list of child controls. |
| GetHeight | <a href="turbine.ui.control">Control</a> | Gets the height of the control. |
| GetLeft | <a href="turbine.ui.control">Control</a> | Gets the left coordinate of the control. |
| GetMousePosition | <a href="turbine.ui.control">Control</a> | Gets the mouse position relative to this control. |
| GetOpacity | <a href="turbine.ui.control">Control</a> | Gets the opacity of the window. |
| GetParent | <a href="turbine.ui.control">Control</a> | Gets the parent of the control. |
| GetPosition | <a href="turbine.ui.control">Control</a> | Gets the position of the control. |
| GetShortcut | | Gets the shortcut on the quickslot. |
| GetSize | <a href="turbine.ui.control">Control</a> | Gets the size of the control. |
| GetTop | <a href="turbine.ui.control">Control</a> | Gets the top coordinate of the window. |
| GetWantsKeyEvents | <a href="turbine.ui.control">Control</a> | Gets a flag indicating if the control wants to receive key events. |
| GetWantsUpdates | <a href="turbine.ui.control">Control</a> | Gets the flag indicating if the control wants to receive Update notifications |
| GetWidth | <a href="turbine.ui.control">Control</a> | Gets the width of the control. |
| GetZOrder | <a href="turbine.ui.control">Control</a> | Gets the Z ordering index of the control. |
| HasFocus | <a href="turbine.ui.control">Control</a> | Returns true if the control has focus. |
| IsAltKeyDown | <a href="turbine.ui.control">Control</a> | Test if the alt key is pressed. |
| IsControlKeyDown | <a href="turbine.ui.control">Control</a> | Test if the control key is pressed. |
| IsDisplayed | <a href="turbine.ui.control">Control</a> | Gets a flag indicating if the control is displayed. |
| IsEnabled | <a href="turbine.ui.control">Control</a> | Gets a flag indicating if the control is enabled. |
| IsMouseVisible | <a href="turbine.ui.control">Control</a> | Gets a flag indicating if the mouse will see this control. |
| IsShiftKeyDown | <a href="turbine.ui.control">Control</a> | Test if the shift key is pressed. |
| IsUseOnRightClick | | Gets whether right clicks will activate the quickslot. |
| IsVisible | <a href="turbine.ui.control">Control</a> | Gets a flag indicating if the control is visible. |
| PointToClient | <a href="turbine.ui.control">Control</a> | Converts a coordinate from control space to screen space. |
| PointToScreen | <a href="turbine.ui.control">Control</a> | Converts a coordinate from control space to screen space. |
| SetAllowDrop | <a href="turbine.ui.control">Control</a> | Sets if the control supports drop operations from drag and drop. |
| SetBackColor | <a href="turbine.ui.control">Control</a> | Sets the background color of the control. |
| SetBackColorBlendMode | <a href="turbine.ui.control">Control</a> | Sets the blend mode applied to the background color. |
| SetBackground | <a href="turbine.ui.control">Control</a> | Sets the background image of the control. |
| SetBlendMode | <a href="turbine.ui.control">Control</a> | Sets the blend mode applied to the background image. |
| SetEnabled | <a href="turbine.ui.control">Control</a> | Sets a flag indicating if the control is enabled. |
| SetHeight | <a href="turbine.ui.control">Control</a> | Sets the height of the control. |
| SetLeft | <a href="turbine.ui.control">Control</a> | Sets the left coordinate of the window. |
| SetMouseVisible | <a href="turbine.ui.control">Control</a> | Gets a flag indicating if the mouse will see this control. |
| SetOpacity | <a href="turbine.ui.control">Control</a> | Sets the opacity of the window. |
| SetParent | <a href="turbine.ui.control">Control</a> | Sets the parent of the control. |
| SetPosition | <a href="turbine.ui.control">Control</a> | Sets the position of the control. |
| SetShortcut | | Sets the shortcut on the quickslot. |
| SetSize | <a href="turbine.ui.control">Control</a> | Sets the size of the control. |
| SetTop | <a href="turbine.ui.control">Control</a> | Sets the top coordinate of the window. |
| <a href="turbine.ui.lotro.quickslot.setuseonrightclick">SetUseOnRightClick</a> | | Sets whether right clicks will activate the quickslot. |
| SetVisible | <a href="turbine.ui.control">Control</a> | Sets the visible flag of a control. |
| SetWantsKeyEvents | <a href="turbine.ui.control">Control</a> | Sets a flag indicating if the control wants to receive key events. |
| SetWantsUpdates | <a href="turbine.ui.control">Control</a> | Sets the flag indicating if the control wants the receive update notifications. |
| SetWidth | <a href="turbine.ui.control">Control</a> | Sets the width of the control. |
| SetZOrder | <a href="turbine.ui.control">Control</a> | Sets the Z order of the control. |

</details>

<details>
<summary>Events</summary>

| Name | Inherited | Description |
| --- | ---: | --- |
| <a href="turbine.ui.lotro.quickslot.dragdrop">DragDrop</a> | | Event fired when a drag drop operation is completed. |
| DragDrop | <a href="turbine.ui.control">Control</a> | Event fired when a drag drop operation is completed. |
| DragEnter | <a href="turbine.ui.control">Control</a> | Event fired when a drag drop operation enters the control. |
| DragLeave | <a href="turbine.ui.control">Control</a> | Event fired when a drag drop operation leaves the control. |
| DragStart | <a href="turbine.ui.control">Control</a> | Event fired when a drag drop operation starts the control. |
| EnabledChanged | <a href="turbine.ui.control">Control</a> | Event fired when the enabled state of the control changes. |
| FocusGained | <a href="turbine.ui.control">Control</a> | Event fired when the control gains focus. |
| FocusLost | <a href="turbine.ui.control">Control</a> | Event fired when the control loses focus. |
| KeyDown | <a href="turbine.ui.control">Control</a> | Event fired when a key is pressed down. |
| KeyUp | <a href="turbine.ui.control">Control</a> | Event fired when a key is released. |
| MouseClick | <a href="turbine.ui.control">Control</a> | Event fired when a mouse button is clicked. |
| MouseDoubleClick | <a href="turbine.ui.control">Control</a> | Event fired when a mouse button is double clicked. |
| MouseDown | <a href="turbine.ui.control">Control</a> | Event fired when a mouse button is pressed. |
| MouseEnter | <a href="turbine.ui.control">Control</a> | Event fired when the mouse enters the control. |
| MouseHover | <a href="turbine.ui.control">Control</a> | Event fired when the mouse is hovering over the control. |
| MouseLeave | <a href="turbine.ui.control">Control</a> | Event fired when the mouse leaves the control. |
| MouseMove | <a href="turbine.ui.control">Control</a> | Event fired when the mouse moves. |
| MouseUp | <a href="turbine.ui.control">Control</a> | Event fired when a mouse button is released. |
| MouseWheel | <a href="turbine.ui.control">Control</a> | Event fired when a mouse wheel moves. |
| PositionChanged | <a href="turbine.ui.control">Control</a> | Event fired when the position of the control changes. |
| <a href="turbine.ui.lotro.quickslot.shortcutchanged">ShortcutChanged</a> | | Event fired when the shortcut changes. |
| SizeChanged | <a href="turbine.ui.control">Control</a> | Event fired when the size of the control changes. |
| Update | <a href="turbine.ui.control">Control</a> | Event fired every frame when WantsUpdates is enabled. |
| VisibleChanged | <a href="turbine.ui.control">Control</a> | Event fired when the visible state of the control changes. | 

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
- <a href="turbine.ui.lotro">Turbine.UI.Lotro</a>

<hr/>
<sub>Copyright &copy; Standing Stone Games, LLC.  All rights reserved.</sub>
