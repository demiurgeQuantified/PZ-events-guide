# CalculateStats
## Trigger Condition
This hook is called every player update, before the player's stats are calculated. Specifically, before hunger, thirst, endurance, fatigue, stress, unhappiness, boredom, fitness and trip chance are updated. This hook does not allow you to stop player health updates.  
Triggered by: IsoGameCharacter:calculateStats()
## Parameters
| Type | Name | Description |
| :--- | :--- | :--- |
| [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | character | The character whose stats are being calculated |
## Return Values
| Value | Effect |
| :--- | :--- |
| true | Stats are calculated as normal |
| false | Stats are not calculated |

[Return](../Hooks.md)
