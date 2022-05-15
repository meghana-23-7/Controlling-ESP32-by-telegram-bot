# Controlling-ESP32-by-telegram-bot
Here ,we are controlling an led connected to ESP32 by sending commands to telegram bot.

## Task number: 03

## Task name: controlling GPIO pins using telegram bot.

## Reference 
https://iotdesignpro.com/projects/telegram-bot-with-esp32-control-gpio-pins-through-telegram-chat

## Components used
ESP32, USB cable. Along with Arduino IDE and Telegram app.

Connections: connect ESP32 to computer using USB cable. Create a telegram bot to monitor the GPIO pins of ESP32.

## Theory
Here in this task, we are controlling an led connected to ESP32 by sending commands to telegram bot.
Creating a bot: go to your telegram account, search for botfather and click on it. This helps us to create, delete and manage our bots. Click on start, type /newbot, give name and username to the bot. Once a bot is successfully created, we will receive a message with a link to access it and a token(unique ID) which helps us to communicate with the bot.
Getting Telegram chat ID: we use this to avoid unauthorized access to the bot. This helps to uniquely identify a use or chat or group. Go to IDBot, type /getid, it sends an ID, save this for later use.
Also install the necessary bot library for telegram bot.

## Code
https://github.com/meghana-23-7/Controlling-ESP32-by-telegram-bot/blob/main/sketch_task3.ino

## Problems faced
The bot isn’t responding to any of the commands, I'm still working on this error. 

## Output

There was no change or response, I'm still working on this.
