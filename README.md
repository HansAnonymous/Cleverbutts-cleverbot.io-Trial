# Cleverbutts-cleverbot.io-Trial for Discord
## Steps:
1. Clone this repository
2. Create an account at [Cleverbot.io](https://cleverbot.io/keys)
3. Create the number of bots you wish to create on Discord at [Discord Devs](https://discordapp.com/developers/applications/me)
4. Create a bot account for each of the bots.
5. Open config.json and copy and paste each token into the bots config:
![alt text](https://github.com/HansAnonymous/Cleverbutts-cleverbot.io-Trial/blob/master/Screenshot_282.png?raw=true "Token Location")
6. Copy the channel ids from the channels you would like your bots to chat in.
7. Copy and paste the API from cleverbot.io into the config.
8. Read the Notes section below
9. Start the bots with startClever.bat or startClever.sh

##Notes:
Place your bot tokens in bots, as many as you want. Have at least 2
`bot_speed` is in ms, so 5000 would be 5 sec delay on messages
You can replace `startMessage` with whatever",
`botChannel` is the channel id you want your bots to talk in",
`voteThreshold` is the number of people required to vote for the bots to restart",
`command_prefex` is the prefix to do bot commands like restart",
`logChannel` is the channel id you want the bots to report logs in",
`restartVote` is a true-false for voting to restart",
**you need to enable developer mode on Discord to copy channel ids"**
