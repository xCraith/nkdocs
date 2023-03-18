# DB:GetTable

------------

## Get Table

```lua
DB:GetTable(tablename,database)
```


## Arguments

| argument                     | description                                      | 
|------------------------------|--------------------------------------------------|
| `:AddColumn(name, datatype)` | Adds column to table                             |
| `:GetFromPlayerSteamID(ply)` | adds "WHERE SteamID=steamidofply"                |
| `:GetFromPlayerCharID(ply)`  | adds "WHERE CharID=charidofply                   |
| ` :SetPlayerSteamID(ply)`    | adds "SteamID=steamidofply" when you insert data |
| `:SetPlayerCharID(ply)`      | adds "CharID=charidofply" when you insert data   |
| `:Delete()`                  | Activates delete mode                            |
| `:Where(column,is,operator)` | Where condition                                  |
| `:Set(column,value)`         | Updates value in a column                        |
| `:GetTable(column)`          | ?                                                |
| `:Init()`                    | returns a table                                  |


------------

## Example
```lua
local items = DB:GetTable("AuktionsMarkt"):Where("Category",cat):Init()

            local data = DB:GetTable("Whitelist");
            data:SetPlayerSteamID(steamid)
            data:Init()

            local data = DB:GetTable("Whitelist");
            data:GetFromPlayerSteamID(steamid)
            data:Delete()
            data:Init()

            local data = DB:GetTable("Whitelist");
            data:GetFromPlayerSteamID(steamID64)
            data:Init()
```