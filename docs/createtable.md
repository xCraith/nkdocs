# DB:CreateTable

------------

## Get Table

```lua
DB:GetTable(tablename,database)
```


## Arguments

| argument                     | description                              | 
|------------------------------|------------------------------------------|
| `:AddColumn(name, datatype)` | Adds column to table                     |
| `:AddCharID()`               | Creates a column with the name "CharID"  |
| `:AddSteamID()`              | Creates a column with the name "SteamID" |
| `:Init()`                    | Yarak                                    |



------------

## Example
```lua
    DB:CreateTable("Whitelist")
    :AddSteamID()
    :Init()

     DB:CreateTable("AuktionsMarkt")
    :AddColumn("ItemID","TEXT")
    :AddColumn("Category","TEXT")
    :AddCharID()
    :Init()
```