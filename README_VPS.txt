FACEBOOK UID MONITOR - VPS PACKAGE

1. Upload/unzip this folder on your VPS.

2. Set your Telegram bot token as an environment variable:
   export BOT_TOKEN="PUT_YOUR_NEW_BOT_TOKEN_HERE"

3. Optional:
   export ALLOWED_CHAT_ID="6656858850"
   export SCAN_INTERVAL="300"
   export REQUEST_TIMEOUT="8"
   export DAILY_REPORT_TIME="23:59"

4. Run:
   chmod +x install.sh
   ./install.sh

The Python file also auto-installs requests if it is missing.

IMPORTANT:
The bot token previously pasted in chat should be considered exposed.
Generate a new token with @BotFather and use the new token in BOT_TOKEN.
