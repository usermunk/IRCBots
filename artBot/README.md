artBot
======

A simple IRC bot that sends out ASCII messages on the Art channel.

Dependencies
------------

* Twisted (python)

Commands
--------

* artBot, help: Shows the available commands
* artBot, paint `<`tag`>`: Paint ASCII message by its corresponding tag (random by default)
* artBot, list: Lists all of the valid message tags for painting

Config
------

* Nick: Nickname of the bot
* Admin: Administrator of the bot
* Channel: Server channel
* Server: URL that the bot connects to

To Do
-----

* Add more ASCII messages
* Add ability for bot to display ASCII messages at certain times, such as lunch or break
* Add function to escape characters in JSON file