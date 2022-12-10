# WeaponHitCharacter
## Trigger Condition
This hook is called when a weapon successfully hits a character, but before any effects are applied. It is not called when zombies are hit.  
Triggered by: [IsoGameCharacter:Hit()](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html#Hit(zombie.inventory.types.HandWeapon,zombie.characters.IsoGameCharacter,float,boolean,float,boolean))
## Parameters
| Type | Name | Description |
| :--- | :--- | :--- |
| [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | attacker | The player swinging the weapon |
| [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | target | The player being hit by the weapon |
| [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) | weapon | The weapon used in the attack |
| float | damageSplit | The damage the attack will deal |
## Return Values
| Value | Effect |
| :--- | :--- |
| true | No damage or other effects of the attack are applied |
| false | The character is hit as normal |

[Return](../Hooks.md)
