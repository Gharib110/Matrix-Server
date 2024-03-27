# INCOMPLETE, WAIT ...
# Matrix-Server
How to communicate with 9 chat network through a decentralized chat network (Matrix Network)

## Beeper Cloud and Beeper Mini
Beeper company provide a cloud service to communicate over 9 centralized chat network through Matrix decentralized chat network, actually it is  matrix bridges that 
provide this functionality.<br/>
IF YOU WANT TO USE BEEPER YOU SHOULD go in a WAITLIST ! <br>
[Beeper](https://beeper.com)<br/>
But You can have this with running a private self-hosted private matrix server that gives you this functionality. Also, you can communicate to other nodes because of the FEDERATION 
mechanism.<br/>
[Matrix Bridges Lists](https://matrix.org/ecosystem/bridges/)<br/>
I have tested Telegram, Whatsapp, Facebook Messenger, Instagram, Slack, Discord, Google Chat, Twitter and Signal.
But you are not limited to them !<br/>
you can communicate to IRC servers, Linkedin, Mattermost servers, Emails, Android SMS, Imessage IOS, Line, Wechat, Tencent QQ and more !
My focus is based on what IRANIAN use daily ! <br/>
YOU USE THOSE MESSENGERS ON YOUR SERVER SO IT IS JUST PRIVATE TO YOU AND E2EE

## Clients
You can use element client on IOS, Android, MacOS, Windows and Linux Distros

## Commands
Commands you should run on your server to to operate your node properly
- `` mkdir -p /mnt/synapse `` create a directory for every docker containner like synapse (see the compose files)
- you should be aware of the required permissions !
- I use postgresql for synapse and sqlite3 for bridges just for simplicity you can use sqlite3 for synapse too, but if you plan to support many users use PostgreSQL for all servers
- 
