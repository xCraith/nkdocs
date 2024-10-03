# Discord Webhook

------------

## Serverside Functions

##### Post Discord Webooks

## Arguments

| argument                     | description                                      | 
|------------------------------|--------------------------------------------------|
| `title`                      | title of the log                                 |
| `msg`                        | message of the log                               |
| `logname`                    | name of the log (printed under the embed)        |
| `player`                     | active player                                    |
| `target`                     | passive player                                   |
| `image`                      | image url with .png                              |
| `color`                      | color hexcode (dont use letters)                 |
| `webHook`                    | webHook url                                      |

```lua
WEBHOOK.DiscordLog( title, msg, logname, player, target, image, color, webHook )
```
