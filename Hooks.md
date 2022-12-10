# Hooks
## What is a hook?
Hooks are similar to events, but can return a value that the vanilla code will use.
## List of Hooks
Note: Objects passed/triggering can sometimes children of the classes specified (for example, an [IsoPlayer](https://projectzomboid.com/modding/zombie/characters/IsoPlayer.html) may be passed in place of an [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html))
| Hook | Parameters | Triggered by |
| :--- | :--- | :--- |
| [AutoDrink](/Hooks/AutoDrink.md) | [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) character | [IsoGameCharacter:autoDrink()](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html#autoDrink()) |
| [Attack](/Hooks/Attack.md) | [IsoLivingCharacter](https://projectzomboid.com/modding/zombie/characters/IsoLivingCharacter.html) attacker, float ChargeDelta, [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) weapon | [IsoLivingCharacter:attemptAttack()](https://projectzomboid.com/modding/zombie/characters/IsoLivingCharacter.html#AttemptAttack(float)) |
| [CalculateStats](/Hooks/CalculateStats.md) | [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) character | IsoGameCharacter:calculateStats() |
| [WeaponHitCharacter](/Hooks/WeaponHitCharacter.md) | [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) attacker, [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) target, [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) weapon, float damageSplit | [IsoGameCharacter:Hit()](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html#Hit(zombie.inventory.types.HandWeapon,zombie.characters.IsoGameCharacter,float,boolean,float,boolean)) |
| [WeaponSwing](/Hooks/WeaponSwing.md) | [IsoGameCharacter](https://projectzomboid.com/modding/zombie/characters/IsoGameCharacter.html) owner, [HandWeapon](https://projectzomboid.com/modding/zombie/inventory/types/HandWeapon.html) weapon | [SwipeStatePlayer:enter()](https://projectzomboid.com/modding/zombie/ai/states/SwipeStatePlayer.html#enter(zombie.characters.IsoGameCharacter)) |
| Deprecated hooks: |
| UseItem |
| WeaponSwingHitPoint |
## See also:
[Events](/Events.md)
