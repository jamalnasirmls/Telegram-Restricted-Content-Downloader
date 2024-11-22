# Telegram-Restricted-Content-Downloader

A Telegram bot designed to streamline the process of downloading restricted and non-restricted content from Telegram groups and channels. Just copy a media link to your clipboard, and the bot will automatically add it to a download queue. Once you're ready, press enter to start downloading.

## Features

📋 Clipboard Monitoring: Automatically detects and adds Telegram media links from your clipboard.
📥 Download Restricted Content: Supports downloading media from private groups and channels you have access to.
🔓 Download Non-Restricted Content: Handles public Telegram content seamlessly.
⏸ Queue Management: Builds a list of links until you press enter to download.
🔄 Reset Functionality: Reset the list anytime by pressing r + enter.

## How it Works

Copy any Telegram media link to your clipboard (e.g., https://t.me/TelegramTips/479).
The bot automatically detects the link and adds it to the queue.
Once ready, press enter to download all queued media.
To clear the queue, press r + enter.

## Example Interface

![ ](./examples/#1.png)
![ ](./examples/#2.png)
![ ](./examples/#3.png)
![ ](./examples/#4.png)
![ ](./examples/#5.png)
![ ](./examples/#6.png)

# Requirements

Ensure you have Python 3.8+ installed. Install the following dependencies:

pyaes==1.6.1
pyperclip==1.9.0
pyrotgfork==2.1.35
PySocks==1.7.1
PyTgCrypto==1.2.6
python-dotenv==1.0.1
TgCrypto==1.2.5
uvloop==0.19.0

## Installation

### 1. Clone this repository:

```bash
git clone https://github.com/victorjalonzo/Telegram-Restricted-Content-Downloader.git
cd Telegram-Restricted-Content-Downloader
```

### 2. Install dependencies:

```bash
pip install -r requirements.txt
```

### 3. Create a .env file in the project's root directory with the following content:

```bash

#Replace it with your Telegram application credentials
API_ID="YOUR_API_ID"
API_HASH="YOUR_API_HASH"

```
Replace the placeholders with your corresponding information.

## Usage

To start the bot, run the following command:
```bash
python app.py
```

## Contributions

Contributions are welcome. If you'd like to contribute, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.