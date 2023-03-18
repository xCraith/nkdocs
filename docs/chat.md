# Chat Functions

------------

## Chat:Register
Example:
```lua
Chat:Register("ooc", {
	commands = {"/ooc", "//"},
	message = function(sender, message)
		local messageTable = {}

        table.insert(messageTable, Color(240, 120, 0))
		table.insert(messageTable, "[OOC] ")
		table.insert(messageTable, team.GetColor(sender:Team()))
		table.insert(messageTable, sender)
		table.insert(messageTable, Color(255, 255, 255))
		table.insert(messageTable, ": " .. message)

        return messageTable
	end,
	shouldSend = function(receiver, sender)
		return true
	end
})
```
------------

## Chat:RegisterCommand
Example:
```lua
Chat:RegisterCommand("kleidung", {
    commands = {"/kleidung"},
    execute = function(ply, args)
        net.Start("BodyGroups.Open")
		net.Send( ply )
    end
})
```