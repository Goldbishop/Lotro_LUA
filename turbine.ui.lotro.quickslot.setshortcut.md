<a href="index">Home</a> > <a href="turbine.ui.lotro">Turbine.UI.Lotro</a> > <a href="turbine.ui.lotro.quickslot">Quickslot</a>

<h1>SetShortcut Method</h1>
<hr/>
<sub style="color:red; font-weight:bold">Beta Documentation - Subject to change.</sub>

Sets the shortcut on the quickslot

## Remarks
Sets the shortcut on the quickslot

## Syntax 
```lua
function Quickslot:SetShortcut(value)
```
### Parameters
<dl>
<dt>value</dt>
<dd>Type: <a href="turbine.ui.lotro.shortcut">Shortcut</a><dd>
<dd>The new shortcut information to set the quickslot to use.</dd>
</dl>

## Examples
<details><summary>Basic</summary>
Setting a new shortcut
```lua
quickslot = Turbine.UI.Lotro.Quickslot();
quickslot:SetParent( myWindow );
quickslot:SetPosition( 50, 50 );
quickslot:SetSize( 38, 38 );
quickslot:SetShortcut( Turbine.UI.Shortcut( Turbine.UI.Lotro.ShortcutType.Undefined, "") );
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
* <a href="turbine.ui.lotro.quickslot">Quickslot</a>
* <a href="turbine.ui.lotro">Turbine.UI.Lotro</a>

<hr/>
<sub>Copyright &copy; Standing Stone Games, LLC.  All rights reserved.</sub>