# 🤖 Meme Discord Bot (Python + Railway)
This is a Python-based Discord bot deployed on [Railway](https://railway.app) and kept alive 24/7 using a lightweight Flask web server.
A simple bot that replies with a random meme from Reddit when you type $meme.

1. Create Bot on Discord:  
   Go to [discord.com/developers](https://discord.com/developers) → New App → Bot → Copy token.


2. Edit the file bot.py :
   DISCORD_TOKEN=your_token_here


3.  Deploy to Railway
   Push this project to GitHub.

   Go to Railway → New Project → Deploy from GitHub.

   Add environment variables (DISCORD_TOKEN) in the Railway dashboard.

   Set start command:
   python main.py

4. Run the bot:
   invite it to your server, and type $meme 🎉
