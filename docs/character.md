# Character System Functions

------------

## Shared Functions

##### Gets Players Character info

```lua
PLAYER:GetChar( charid )
```

##### Gets Players CharID

```lua
PLAYER:GetCharID()
```

##### Gets Players Faction ID

```lua
PLAYER:GetFaction()
```

##### Gets Players Guild ID if Valid

```lua
PLAYER:GetGuildID()
```

##### Gets Players Sex

```lua
PLAYER:GetSex()
```

##### Returns Players Faction Color

```lua
PLAYER:GetFactionColor()
```

------------

## Serverside Functions

##### Gets a Table with all Characters

```lua
CHARSYS.GetChars( ply, steamid64 )
```

##### Resets Players Body

```lua
CHARSYS.ResetBody(ply)
```

##### Updates Players Body

```lua
CHARSYS.UpdateBody(ply, modelpath)
```

##### Resets Players Headmodel

```lua
CHARSYS.ResetHead(ply)
```

##### Updates Players Headmodel

```lua
CHARSYS.UpdateHead(ply, modelpath)
```

##### Updates Players Maskmodel

```lua
CHARSYS.UpdateMask(ply, modelpath)
```

##### Resets Players Maskmodel

```lua
CHARSYS.ResetMask(ply)
```

##### Saves Players Character to Database

```lua
CHARSYS.SaveCurrentChar( ply )
```

##### Sets Players Head

```lua
PLAYER:AddCharacterHead( mdl )
```

##### Remove Players Head

```lua
PLAYER:RemoveCharacterHead()
```

##### Sets Players Maskmodel

```lua
PLAYER:AddCharacterMask( mdl )
```

##### Remove Players Mask

```lua
PLAYER:RemoveCharacterMask()
```

##### Checks if Player is owner of the CharID

```lua
PLAYER:IsCharOwner( id )
```