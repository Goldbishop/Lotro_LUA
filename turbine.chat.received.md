<a href="index">Home</a> > <a href="turbine">Turbine</a> > <a href="turbine.chat">Chat</a>
<hr/>

This event is fired whenever a chat message is received.

## Remarks
This event is fired whenever any chat message is received from the game or other users. The arguments for this event will contain a combination of a Sender, a ChatType, and the Message itself. The ChatType enumeration can be used to determine what kind of message was received.

## Syntax 
```lua
function Chat:Received(sender, args)
```
### Parameters
<dl>
<dt>sender</dt>
<dd>Type: table - The event sender</dd>
<dt>args</dt>
<dd>Type: table - The event arguments</dd>
</dl>

## Examples
** Coming Soon **

## See Also
* <a href="turbine.chat">Chat</a>
* <a href="turbine">Turbine</a>

<hr/>
<sub>Copyright &copy; Standing Stone Games, LLC.  All rights reserved.</sub>