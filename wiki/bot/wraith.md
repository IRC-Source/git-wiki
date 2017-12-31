---
title: Wraith IRC Bot
excerpt: Wraith is an IRC bot based on eggdrop which is designed to  protect channels on networks with no services.
---
# Wraith IRC Bot
The **Wraith IRC Bot** is an IRC channel management bot based on Eggdrop 1.6.12. TCL scripts and other modules are not supported by Wraith. Wraith has been around since 2003.

# Wraith Hubs
A hub is a Wraith bot that does not connect to IRC, but instead allows other bots, known as leafs, to connect to it.

# Wraith Leafs
A leaf connects to IRC and to a hub on the [botnet](/wiki/bot/#irc-botnets).

## Leaf Security
Wraith keeps an encrypted copy of its configuration file inside of the binary for the bot. To reconfigure the bot you must provide a password. Wraith also only stores an encrypted copy of the user file only on hubs so that nothing is kept locally on the leafs.

# External Links
1. [Wraith website](http://wraith.botpack.net)
2. [Wraith on Github](https://github.com/wraith/wraith)