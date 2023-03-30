# Reveal

Reveal is a simple, lightweight, and fast tool for League of Legends to reveal your team mates names in champ select.

### Usage
Head over to the [releases]() and download the precompiled binary, then simply just run it and it will automatically start revealing your team-mates names in champ select.

### Why this instead of LobbyReveal?
[LobbyReveal](https://github.com/Riotphobia/LobbyReveal) is great, but here's a few reasons.
- Smaller binary size
- Less memory usage
- Not dependent on the .NET runtime (You don't need it installed)
- Faster startup time and faster execution time
- We don't spam the LCU API with requests, we only request the data as it's needed by connecting to the LCU's event websocket. (This could make our tool a bit safer to use)

## Credits
- [Shaco](https://github.com/Leastrio/Shaco/tree/main) for the LCU API wrapper so I didn't need to go through the pain.
- [LobbyReveal](https://github.com/Riotphobia/LobbyReveal) the original tool, thanks to [Inception](https://github.com/0xInception) for making it.