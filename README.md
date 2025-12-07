💧 Water & Stretch Reminder Bot
A friendly Discord bot that keeps you hydrated and healthy! This bot sends personalized reminders to drink water and stretch, featuring random fun images to keep things lively.

✨ Features
Per-User Loops: Reminders are personalized—only the user who started the command gets tagged.

Channel Aware: Works in any text channel. Reminders are sent to the channel where the command was initiated.

Friendly Commands: Simple slash-style text commands like !hydrate and !stretch.

Media Integration: Sends random images/GIFs from the memes/ and stretch/ directories with every reminder.

Robust Cancellation: !stop halts loops immediately without any lagging "one last ping."

Single-Embed Help: Clean !help command with inline examples.

Secure: Uses .env for safe token management.

🚀 Getting Started
Follow these instructions to get the bot up and running on your local machine or server.

Prerequisites

Python 3.8+

A Discord Bot Token (Guide: How to get a token)

📥 Installation

Clone the repository:

Bash
git clone https://github.com/Abhigyan-Shekhar/water_reminder_bot.git
cd water_reminder_bot
Set up a virtual environment (Optional but Recommended):

Bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
Install dependencies: Since there is no requirements.txt included, install the core libraries manually:

Bash
pip install discord.py python-dotenv
⚙️ Configuration

Create a file named .env in the root directory.

Add your Discord Bot Token to the file:

Code snippet
DISCORD_TOKEN=your_super_secret_bot_token_here
🖼️ Adding Images

The bot sends random images from specific folders. Make sure these folders are populated!

Water Memes: Add images (.jpg, .png, .gif) to the memes/ folder.

Stretch Images: Add images to the stretch/ folder.

Note: The bot checks these folders relative to where you run the script. Ensure they exist and contain at least one file.

🎮 Usage
Run the bot:

Bash
python bot.py
Invite the bot to your server (ensure it has permissions to Read Messages, Send Messages, and Embed Links).

🤖 Commands

Command	Usage	Description
!hydrate	!hydrate [minutes]	Starts a water reminder loop. Defaults to 60 mins if no time is specified.
!stretch	!stretch [minutes]	Starts a stretching reminder loop. Defaults to 30 mins if no time is specified.
!stop	!stop	Stops all active reminders for you.
!help	!help	Shows the help menu with examples.
Examples:

!hydrate 30 -> Reminds you to drink water every 30 minutes.

!stretch 45 -> Reminds you to stretch every 45 minutes.

🤝 Contributing
Contributions are welcome!

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
Distributed under the MIT License. See LICENSE for more information.

🔗 Quick Add Link

Invite the Bot to your Server
