# IPInfo Discord Bot

This is a Discord bot that uses the ipinfo.io API to get information about a given IP. By using the `/ipinfo <IP>` command, the bot returns details such as country, city, organization and more, based on the provided IP.

## Requirements

To run this bot, you will need to have the following:

- [Node.js 18.x](https://nodejs.org/es/download) (includes npm).
- An account on [ipinfo.io](https://ipinfo.io/signup) to get an API Key (Required for the bot to work)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/brunomedinap/IpInfo.git

2. Entra a la carpeta del proyecto:
    ```bash
    cd IpInfo-Bot

3. Instala las dependencias:
    ```bash
    npm i

4. configure the Token, Client ID, GuildID and Api Key on the config.yml (/settings/config.yml):
    ```yml
    BOT_CONFIG:
      NAME: "IpInfo Bot"
      EMBED_COLOR: "#ff0000"
      TOKEN: "BOT_TOKEN_HERE"
      GUILD_ID: "YOUR_GUILD_ID"
      BOT_ID: "CLIENT_ID_HERE"
      IPINFO_API_KEY: "IPINFO_API_KEY"

5. Start the bot using
    ```bash
    npm run start