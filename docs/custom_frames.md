# Frames

------------

## Clientside Functions

!!! tip "Informationen"

    Hier findest du sämtliche custom Frames welche im Gamemode enthalten sind.

##### Custom Frames

| DefaultName                  | CustomName                               | 
|------------------------------|------------------------------------------|
| `DFrame`                     | SWFrame                                  |
| `DScrollPanel`               | SWScroll                                 |
| `DTextEntry`                 | SWTextEntry                              |
| `DButton`                    | SWButton                                 |
| `DModelPanel`                | SWModelPanel                             |

!!! tip "Custom Message / Query"

    Hier findest du Infos zu der Custom Derma message und Derma query.

```lua
SW_Message( strText, strTitle, strButtonText )
```

!!! exampe "Beispiel"

    ```lua
    SW_Message( "Es ist ein Fehler aufgetreten", "Fehler", "Okay" )
    ```

```lua
SW_Query( strText, strTitle, ... )
```

!!! exampe "Beispiel"

    ```lua
    SW_Query("Namens Änderungen kosten 30.000 Credits, möchtest du fortfahren ?", "Bestätigung",
        "Bestätigen",
        function() 
            -- do something
        end,
        "Abbrechen"
    )
    ```