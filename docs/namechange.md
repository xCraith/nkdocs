# Namechange Functions

------------

## Serverside Net Message

##### Change Players name

```lua
net.Start("NAMESWITCH.ChangeName")
net.WriteString(nameString)
net.SendToServer()
```
