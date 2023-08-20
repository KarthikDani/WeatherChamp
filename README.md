# WeatherChamp Discord Bot

![WeatherChamp Logo](assets/logo.png)

Welcome to the WeatherChamp Discord Bot repository! This bot provides real-time weather information and forecasts for cities.

## Features

- Detailed weather information including temperature, humidity, and wind speed
- Get a weather forecast for a city
- Suggest similar city names
- Interactive map with city location


## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Commands](#commands)

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/KarthikDani/WeatherChamp.git
   cd WeatherChamp
   
2. Install the required Python packages:
   pip install -r requirements.txt
   
3. Create a Discord bot and obtain a bot token. [Follow these steps](https://discordpy.readthedocs.io/en/stable/discord.html) to create a bot and get the token.
  
4. Sign up on [OpenWeatherMap](https://home.openweathermap.org) to obtain an API key for weather data.

## Configuration

1. Open config.py in a text editor.
2. Replace DISCORD_TOKEN with your Discord bot token.
3. Replace WEATHER_API_KEY with your OpenWeatherMap API key.
4. Replace SERVER_ID value with your server_id after checking the bot in URL Generator in your Discord Developer application and granting read and send message 

## Usage

1. Invite your bot to your Discord server using the bot invitation link generated on your Discord Developer Portal.
   
2. Run the bot:
   python bot.py

## Commands

!weather <city>: Get the current weather for a city.
!forecast <city>: Get a weather forecast for a city.
!suggest <city>: Suggest similar city names.
!get_weather <city>: Get the current weather for a city.
