# Character System Hooks

------------

## Serverside Hooks

##### Hook after Character Switch

```lua
hook.Call("CHARSYS.PostChange", nil, ply , char.id )
```

##### Before Char Delete

```lua
hook.Call("CHARSYS.RemoveChar", nil, ply, id)
```

##### After Char Delete

```lua
hook.Call("CHARSYS.OnDeleteChar", nil, id )
```