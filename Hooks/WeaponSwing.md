# Weapon Swing
## Trigger Condition
This hook is called when a character swings a weapon (including shoves and stomps) before the attack connects with any targets.  
Triggered by: [SwipeStatePlayer:enter()](https://projectzomboid.com/modding/zombie/ai/states/SwipeStatePlayer.html#enter(zombie.characters.IsoGameCharacter))
## Parameters
| Type | Name | Description |
| :--- | :--- | :--- |
|[IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | owner | The player swinging the weapon |
|[HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html)| weapon | The weapon being swung |
## Return Values
| Value | Effect |
| :--- | :--- |
| true | The attack is cancelled |
| false | The attack proceeds as normal |

[Return](../Hooks.md)
