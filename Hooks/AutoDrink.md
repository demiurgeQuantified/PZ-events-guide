# AutoDrink
## Trigger Condition
This hook is triggered just before a character automatically drinks from their inventory because their thirst is low. This only happens when enabled from the options menu.  
Triggered by: [IsoGameCharacter:autoDrink()](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html#autoDrink())
## Parameters
| Type | Name | Description |
| :--- | :--- | :--- |
| [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | character | The character that is auto-drinking |
## Return Values
| Value | Description |
| :--- | :--- |
| true | The character auto-drinks as normal |
| false | The auto-drink is cancelled |

[Return](../Hooks.md)
