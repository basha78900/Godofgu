# Telegram Bot

A Telegram bot for managing attack requests with admin approval system, MongoDB database, and external API integration.

## Features

- 🔐 User approval system with expiration dates
- 👑 Admin commands for user management
- 📊 Attack statistics and logging
- 🚫 Blocked ports validation
- 💾 MongoDB database for persistent storage
- 🔄 24/7 deployment ready (Railway, Heroku, etc.)

## Prerequisites

- Python 3.11 or higher
- MongoDB database (Atlas or local)
- Telegram Bot Token (from @BotFather)
- External API endpoint with authentication key

## Environment Variables Setup

Create a `.env` file in the root directory with the following variables:

```env
BOT_TOKEN=8597609771:AAFx6QhB_feM-5-WwAeXEVLz8--cPn2LDlg
MONGODB_URI=mongodb+srv://bashabashaa9049_db_user:<L1HZpqxIk7io2HB5>@bashaapio.vvml1qb.mongodb.net/?appName=Bashaapio
DATABASE_NAME=bashabashaa9049_db_use
API_URL=https://your-api-domain.com
API_KEY=your_api_key_here
ADMIN_IDS=1219524068
```