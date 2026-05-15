# Miraculous Ladybug RPG Bot

## Run on Windows

1. Install Node.js 18 or newer.
2. Rename `.env.example` to `.env` or set the variables in your host panel.
3. Put your real Discord bot token in `DISCORD_TOKEN`.
4. Double-click `start.bat`.

## Run manually

```bash
npm install
npm start
```

## 24/7 Hosting

Use a VPS, Railway, Render, Fly.io, or another Node.js host. Set these environment variables:

```bash
DISCORD_TOKEN=your_token
CLIENT_ID=your_client_id
GUILD_IDS=server_id_1,server_id_2
ADMIN_IDS=your_discord_user_id
```

Then use:

```bash
npm install
npm start
```
