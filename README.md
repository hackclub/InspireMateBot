# Inspire Mate Bot

Inspire Mate Bot is a Discord bot designed to bring inspiration, motivation, and positive vibes to your Discord server.

## Features

- **Inspirational Quotes:** Get random inspirational quotes to boost your spirits.
- **Encouragement:** Responds to messages containing sad words with uplifting messages.
- **Programming Motivation:** Provides motivation specifically tailored for programmers.
- **Custom Messages:** Users can add, delete, and list custom encouraging messages.

## Usage

To use Inspire Mate Bot in your Discord server, follow these steps:

1. **Invite the Bot:**
   - Get the bot token by setting up a Discord App.
   - Invite the bot to your Discord server using the provided bot token.

2. **Set Up Environment Variables:**
   - Create a `.env` file in the root directory.
   - Add your bot token to the `.env` file: `TOKEN=your-bot-token`.

3. **Run the Bot:**
   - Install dependencies: `pip install -r requirements.txt`
   - Run the bot: `python main.py`

## Commands

- **$inspire**
  - Get a random inspirational quote.
- **$new [message]**
  - Add a new custom encouraging message.
- **$del [index]**
  - Delete a custom encouraging message at the specified index.
- **$list**
  - List all custom encouraging messages.
- **$motivate**
  - Get motivation specifically tailored for programming.
- **$help**
  - Display a help message with a list of available commands.

## Contributing

Contributions are welcome! If you'd like to contribute to Inspire Mate Bot, please check out the [CONTRIBUTING.md](https://github.com/hackclub/InspireMateBot/blob/main/.github/CONTRIBUTING.md) file for guidelines.

---

Feel free to customize or expand upon this README to better fit your project's needs!
