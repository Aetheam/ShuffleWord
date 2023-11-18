[![Discord](https://img.shields.io/discord/915046808009441323.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/AzJ7Uz7wkx)


# ShuffleWord
Simple plugin to earn rewards for the first player who finds the random word.

## How to use
Set up the words that have to be in the game in `config.yml`


## Video
[![Alt text](https://i.ytimg.com/vi/JiV3LT24R_Q/hqdefault.jpg?sqp=-oaymwEjCNACELwBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLDZsunzJDF8pu2wCrMzxeUHD-QxQw)](https://www.youtube.com/watch?v=9rcDk5-vRqc&ab_channel=Ayzrix)

## Config
```yaml
# Time between 2 events in seconds
timer: 60
# Rewards commands
rewards:
  - "give {player} 1 64"
# Message broadcasted
broadcast: "§6§l[§f!!!§6]§r Be the first to find the matching word to win §664 stone §f! Word: §6{word} §f!"
broadcast_win: "§6§l[§f!!!§6]§r The player §6{player} §fwas the first to find the word §6{word} §f!"
words:
  - "minecraft"
  - "pocketmine"
  - "microsoft"
```

