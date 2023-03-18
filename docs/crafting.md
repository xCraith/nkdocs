# Crafting Functions

------------

## Shared Functions

##### Gets Players Crafting Upgrade amount

```lua
PLAYER:GetCraftUpgrade( key ) -- amount_lvl or speed_lvl
```

##### Gets Players Crafting Materials amount

```lua
PLAYER:GetCraftingMaterials( key )
```

##### Available Materials

| argument                     |
|------------------------------|
| `lizium`                     |
| `diamond`                    |
| `obsidian`                   |
| `darkmatter`                 |
| `stoff`                      |
| `leder`                      |
| `elektronik`                 |
| `crystalparts`               |

------------

## Serverside Functions

##### Add Materials to a Player

```lua
CRAFTING.AddMats( ply, mat, amount )
```