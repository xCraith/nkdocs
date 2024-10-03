# Discord Webhook

------------

## Serverside Functions

##### Post Discord WebHooks

## Arguments

| argument                     | description                                      | 
|------------------------------|--------------------------------------------------|
| `title`                      | title of the log                                 |
| `msg`                        | message of the log                               |
| `logname`                    | name of the log (printed under the embed)        |
| `player`                     | active player                                    |
| `target`                     | passive player                                   |
| `image`                      | image url with .png                              |
| `decimalColor`               | color decimalcode                                |
| `webHook`                    | webHook url                                      |
 
```lua
local hexColor = "COLORCODE"
local decimalColor = tonumber(hexColor, 16)

WEBHOOK.DiscordLog( title, msg, logname, player, target, image, decimalColor, webHook )
```
