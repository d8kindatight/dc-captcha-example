# dc-captcha-example

a simple discord verification bot using text-based captchas

## requirements
- python 3.8+
- discord.py
- a discord bot

## quick start

1. clone the repo
2. install dependencies
   ```bash
   pip install discord.py
   ```
3. create a `.env` file with:
   ```env
   DISCORD_TOKEN=your_bot_token
   GUILD_ID=your_guild_id
   VERIFIED_ROLE_ID=verified_role_id
   UNVERIFIED_ROLE_ID=not_verified_role_id
   CHANNEL_ID=your_channel_id
   ```
4. run the bot:
   ```bash
   python discord_main.py
   ```

## how it works
- bot sends message with "verify" button
- user clicks it and puts their answer into a form
- bot verifies user almost instantly
