# AllPing
The AllPing discord bot is intented to become an easy way to ping, ssh, portscan, and recieve info about domains. All from the comfort of discord.
In the future, integration with Rhasspy, Alexa and Google may be avaliable.

Current ability of AllPing;
     Ping URL
     Choose a favourite URL, that can be pinged by the use of short term word such as “home" or "default".
  
In order to use the script, please set up your own bot, through the discord website "https://discordapp.com/developers/applications". Then use the token from your newly created bot it to replace the token into the config file. Also edit the channels "on_ready_channel" and "downtime_channel" So that you recieve a startup message and that an alert is sent to the appropriate channel when checking for downtime.
To cancel downtime alert's currently, you have to restart the bot.

This little project, was intended to be able to "ping" my raspberry pi device which ran Dietpi. But realised ICMP does not affect TCP, therefore went ahead with the little venture, and decided to create a multi-functioning bot, as my second attempt at a project.


