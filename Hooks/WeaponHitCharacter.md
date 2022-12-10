# WeaponHitCharacter
## Parameters
[IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) attacker, [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) target, [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) weapon, float damageSplit
## Trigger Condition
This hook is called when a weapon successfully hits a character, but before any effects are applied. It is not called by zombies.  
Triggered by: [IsoGameCharacter:Hit()](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html#Hit(zombie.inventory.types.HandWeapon,zombie.characters.IsoGameCharacter,float,boolean,float,boolean))
## Return Values
| Value | Effect |
| :--- | :--- |
| true | No damage or other effects of the attack are applied |
| false | The character is hit as normal |

[Return](../Hooks.md)
