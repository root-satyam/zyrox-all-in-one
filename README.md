
<div align="center">

```text
 ██████╗  ██████╗  ██████╗ ████████╗
 ██╔══██╗██╔═══██╗██╔═══██╗╚══██╔══╝
 ██████╔╝██║   ██║██║   ██║   ██║
 ██╔══██╗██║   ██║██║   ██║   ██║
 ██║  ██║╚██████╔╝╚██████╔╝   ██║
 ╚═╝  ╚═╝ ╚═════╝  ╚═════╝    ╚═╝
```

# ✦ ZyroX Discord Bot

A powerful Discord bot built with `discord.py v2`, featuring a FastAPI backend for its web dashboard.

Everything runs from a single command:

```bash
python root_zyrox.py
```

</div>

## ✦ Project Structure

```text
bot/
├── api/                   FastAPI backend
│   └── routes/            /bot  /guilds  /admin
├── cogs/
│   ├── antinuke/          Antinuke protection
│   ├── automod/           Automod enforcement
│   ├── commands/          Slash and prefix commands
│   ├── events/            Discord event listeners
│   ├── moderation/        Moderation modules
│   └── zyrox/             Core ZyroX features
├── core/                  Bot client, context, and cog base classes
├── games/                 Game logic and button views
├── utils/                 Emoji, tools, sync, and tunnel utilities
├── assets/                Fonts, backgrounds, and GIFs
└── root_zyrox.py          Main entry point
```

## ✦ Setup

### 1 — Install dependencies

```bash
python -m venv .venv
```

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### 2 — Configure environment

Create a `.env` file from `.env.example` and configure your bot token, owner IDs, Lavalink, API, and Cloudflare settings.

Never upload your actual `.env` file or bot token to GitHub.

### 3 — Start the bot

```bash
python root_zyrox.py
```

## ✦ Deployment

Upload the complete `bot/` folder to your hosting provider and set the startup command to:

```bash
python root_zyrox.py
```

---

<div align="center">

## ✦ ROOT

**All credits go to ROOT.**

*Built for protection. Designed for style.*

</div>
