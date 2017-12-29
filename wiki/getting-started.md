---
Title: Getting Started  on IRC
excerpt: How to get connected to IRC and some basic pointers.
---
# Getting Started
# Choose an IRC Client
An [IRC client](/wiki/client/) is required to connect to an [IRC server](/wiki/ircd/). To get started [choose IRC Client from this list](/wiki/client/#list-of-web-irc-clients).

# Choose an IRC Network
There are many networks and channels to choose from. Many clients will have a default list of networks. To find a network and some channels there are many available [to search from](https://irc-source.com/) as well.

# Choose an IRC Channel
Once connected to a network you can query the server for a list of channels using the `/list` command. Once you find a channel that you like you can join it with the `/join` command (eg- `/join #channel`).

# Basic Commands
## Client
* `/join` -  Joins you to a channel. *Example:* `/join #channel`
* `/list` - Lists channels on the network
* `/msg` - On most  clients this will send a private message to the given nickname. *Example:* `/msg nickname hello`
* `/nick` - Changes your nickname. *Example:* `/nick 0`
* `/part` - Leaves the channel *Example:* `/part #channel`


## Services
For networks that provide services there are typically  2  bots that you will find, Nickserv & Chanserv.
### Register your nickname
To register your nickname you would generally type something such as `/msg nickserv register <password> <email>`

### Login to your nickname
The easiest way to login to your nickname is to use the Nickserv's identify command, however [SASLL](/wiki/sasl) is typically an option too.

To use the identify command type something such as `/msg nickserv identify <password>`.

### Register a channel
If you have a channel on IRC you can register the channel to protect it from other people taking over. To register your channel you would typically type something like `/msg chanserv register <channel>`.