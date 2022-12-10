# Events
## What is an event?
Events trigger lua functions attached to them and pass parameters to them. Modders can use them to trigger their own code only when certain conditions occur, instead of having to check for these conditions manually. They are most often triggered from the Java side of the game, where we would not usually be able to add our own code.  
You can add a function to an event using this format:  
`Events.EventName.Add(functionName)`  
As an example, this code triggers a function to make the player speak when a player spawns, as spawning triggers the OnCreatePlayer event:
```lua
function playerCreated(playerNum, player)
    player:Say("I just spawned!")
end

Events.OnCreatePlayer.Add(playerCreated)
```
## List of events
Note: 'Player Index' refers to the number returned by IsoPlayer:getPlayerNum(), most commonly used for getSpecificPlayer(n)
| Name | Parameters |
| :--- | :--- |
| [OnCreatePlayer](/Events/OnCreatePlayer.md) | Player Index, [IsoPlayer](https://projectzomboid.com/modding/zombie/characters/IsoPlayer.html) |
