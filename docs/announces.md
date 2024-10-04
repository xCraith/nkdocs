# Announce Functions

------------

## Client Net Messages

##### Announce

```lua
net.Start("SWTOR.Announce")
net.WriteString(message)
net.SendToServer()
```

##### Faction Announce

```lua
net.Start("SWTOR.FrakAnnounce")
net.WriteString(message)
net.WriteEntity(ply)
net.SendToServer()
```

##### Master Announce

```lua
net.Start("SWTOR.MasterAnnounce")
net.WriteString(message)
net.WriteEntity(ply)
net.SendToServer()
```

##### Hacking Announce

```lua
net.Start("SWTOR.HackAnnounce")
net.WriteString(message)
net.WriteEntity(ply)
net.SendToServer()
```
