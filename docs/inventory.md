# Additional Inventory Functions

------------

## Server Side Functions

##### Get if player owns item no matter what inv

```lua
PLAYER:HasInvItem(itemName) -- If player has item == true if not == false
```

##### Clear inv of an player

```lua
PLAYER:ClearInventory()
```

##### Check player for inv space

```lua
PLAYER:HasInvSpace() -- if space == true if not == false
```

##### Give player an item no matter what inv

```lua
PLAYER:GiveInvItem(itemName) -- returns false if player has no space, check space func or itself for check
```

##### Remove player an item no matter what inv

```lua
PLAYER:RemoveInvItem(itemName) -- returns false if player hasn't the specific item, check space func or itself for check
```

##### Get players item count inv all invs together

```lua
PLAYER:GetInvItemCount(itemName) -- returns count as int
```
