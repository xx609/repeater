# repeater

## Usage

1. Copy `.env.example` to `.env`.
2. Add your bot token to `.env`:

```env
TELEGRAM_APITOKEN=YOUR_BOT_TOKEN
```

3. Start the bot:

```bash
docker compose up --build
```

## Behavior

The bot repeats a message 3 times if it is no longer than 10 characters and ends with `！`.

To use the bot in a group and allow it to receive all messages, disable privacy mode with `/setprivacy` in BotFather.
