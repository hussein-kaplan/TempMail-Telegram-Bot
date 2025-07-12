# 📬 TempMail Telegram Bot

A powerful and easy-to-use Telegram bot for generating and managing **temporary email addresses** using the [mail.tm](https://mail.tm) API.

---

## 🚀 Features

- 📧 Generate temporary email addresses
- 📥 View received messages (last 3)
- 🗑️ Delete your current email session
- 👤 Admin features:
  - 📊 View total user count
  - 📣 Broadcast messages
- ✅ Require users to join a channel before using the bot

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/hussein-kaplan/TempMail-Telegram-Bot.git
cd temp-mail-bot
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure the Bot

Edit `bot.py`:

- Replace `YOUR_BOT_TOKEN` with your actual Telegram bot token.
- Replace `ADMIN_IDS = [...]` with your Telegram user ID(s).
- Replace `REQUIRED_CHANNEL` with your channel's username (e.g., `@MyChannel`).

### 4. Run the Bot
```bash
python bot.py
```

---

## 📎 Dependencies

- [`python-telegram-bot`](https://github.com/python-telegram-bot/python-telegram-bot)
- `requests`

Install with:
```bash
pip install -r requirements.txt
```

---

## 📄 License

This project is licensed under the MIT License.  
Made with ❤️ for the open-source community.
