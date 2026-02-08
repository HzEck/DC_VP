# GTPS Voice Points Bot

Discord bot that rewards users for being in voice channels.

## Features
- VP (Voice Points) for being in specific voice channels
- 1.05x Gems multiplier in special voice channel
- Discord account linking with GrowID
- In-game commands: /vp, /vpshop, /link
- Auto-save every 5 minutes
- Web dashboard (optional)

## Setup
1. Create Discord bot at https://discord.com/developers/applications
2. Set environment variables in Render.com
3. Deploy to Render
4. Use /link command in Discord to connect GrowID

## Environment Variables
- DISCORD_TOKEN: Your Discord bot token
- GTPS_SERVER_URL: https://api.gtps.cloud/g-api/PORT
- VP_CHANNEL_ID: Voice channel ID for VP earning
- GEMS_CHANNEL_ID: Voice channel ID for gems multiplier
- DATABASE_URL: PostgreSQL connection string (auto-provided by Render)
