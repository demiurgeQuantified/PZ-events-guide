# Attack
## Hooks:
This hooks the code related to attempting to attack with a weapon. It is called every frame while a player is pressing their attack button.
Hooked function: [IsoLivingCharacter:attemptAttack()](https://projectzomboid.com/modding/zombie/characters/IsoLivingCharacter.html#AttemptAttack(float))  
Note: This function is already hooked by Vanilla lua, so hooking it will not actually replace anything.
## Parameters:
| Type | Name | Description |
| :--- | :--- | :--- |
| [IsoLivingCharacter](https://projectzomboid.com/modding/zombie/characters/IsoLivingCharacter.html) | attacker | The player attempting to attack |
| float | ChargeDelta | A delta representing how long the player has had their weapon readied (charging) |
| [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) | weapon | The weapon the player is attemping to attack with |

[Return](../Hooks.md)
