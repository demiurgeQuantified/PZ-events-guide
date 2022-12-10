# WeaponHitCharacter
## Hooks:
This hooks all the consequences of being hit by an attack - both the damage and the stagger animation, as well as the endurance usage for the attacker.  
Hooked function: [IsoGameCharacter:Hit()](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html#Hit(zombie.inventory.types.HandWeapon,zombie.characters.IsoGameCharacter,float,boolean,float,boolean))
## Parameters
| Type | Name | Description |
| :--- | :--- | :--- |
| [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | attacker | The player swinging the weapon |
| [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) | target | The player being hit by the weapon |
| [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) | weapon | The weapon used in the attack |
| float | damageSplit | The damage the attack will deal |

[Return](../Hooks.md)
