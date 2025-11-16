# Project 5
## Implementation / Features you added
- Elaborate level, 4 levers generate in a random spot somewhere in the maze, each with a unique light, and the game generates a password that requires the player to hit the levers in a specific order. Hitting the wrong lever unflips any flipped levers, and also resets the 30 second timer, but only once for each color lever. Hitting the right lever adds 5 seconds to the timer. The timer starts at 30 and ticks down. When the timer reaches 0, it spawns an enemy that hunts down the player. If the timer goes back above 0, the enemy despawns. If the enemy hits the player, the enemy disappears, the password resets, and so do the wrong levers that you've hit. If you flip the levers in the right order, you win. (+1)
- Different model, gave the enemy a model I found (+1)  
- Music and sound effects, general horror music, sound effects for flipping and resetting the levers, enemy makes a horror ambience sound, horror sound for when caught by the enemy. (+1)
- Creative use of lights, I hope the mechanic of the game counts as a creative use of them (+1)
- Attention paid to the start- and end-game experience, I did this as best as possible using the timer additions. Here's the idea: At the very start, the player is likely to hit the wrong lever. As a result, the timer refreshes any time they get it wrong. However, hitting that lever out of order again in the future will not reset the timer, making it harder as you go on. (This is reset any time the enemy touches the player). Once you do hit a lever in the right order, 5 seconds are added to the timer, which is meant to do two things. One, it gives the player some extra grace time to find the next lever. Two, if the enemy has already spawned in and is chasing the player, hitting the correct lever will despawn the enemy and give them 5 seconds of breathing room. (+1)


## References
https://opengameart.org/content/demonic-eye (enemy model)  
https://opengameart.org/content/horror-cinema-6 (death sound)  
https://opengameart.org/content/stove-switch (lever flip sound)  
https://opengameart.org/content/ambient-pulse-noise (lever reset sound)  
https://opengameart.org/content/horror-loop (enemy ambient sound)  
https://opengameart.org/content/horror-atmosphere (horror music)

## Future Development

## Created by
Kihrun Scott
