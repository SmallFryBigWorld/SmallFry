# SmallFry
# CoachKev Discord Bot

**CoachKev** is a Discord bot for GTA V communities that lets you send “legit” callouts for heists, missions, sales, races, and more—and give people the power to subscribe to exactly the pings they want.

---

## 📦 Features

- Self-assignable roles via reaction (Legit Heists, Legit MC, Legit Helper, etc.)  
- `!legit<topic>` commands for:
  - `legitheist`, `legitmc`, `legitnightclub`, `legitmissions`, `legitgunrunner`, `legitceo`, `legitlobby`, `legitraces`, `legitarena`, `legithelper`  
- Automatic “helpers” callout whenever a help command runs  
- Clear “no griefing” reminders and host-invite instructions  
- Always-on web ping endpoint (Flask + keep_alive)  

---

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/CoachKev-Bot.git
   cd CoachKev-Bot
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate    # Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set your bot token** in the environment:
   - Create a file named `.env` (and add `.env` to your `.gitignore`)
   - Inside `.env`:
     ```
     DISCORD_BOT_TOKEN=YOUR_DISCORD_TOKEN_HERE
     ```

5. **Run the bot:**
   ```bash
   python coachkev_helpers_host_mentions.py
   ```

---

## 🔧 Commands

Type `!legithelp` in Discord to see a full list, but here’s a quick summary:

| Command            | Description                           |
|--------------------|---------------------------------------|
| `!legitheist`      | Legit Heist Help callout              |
| `!legitmc`         | Legit MC Help callout                 |
| `!legitnightclub`  | Legit Nightclub Help callout          |
| `!legitmissions`   | Legit Missions Help callout           |
| `!legitgunrunner`  | Legit Gunrunner Help callout          |
| `!legitceo`        | Legit CEO/Agency Help callout         |
| `!legitlobby`      | Legit Crew Lobby                      |
| `!legitraces`      | Legit Races                           |
| `!legitarena`      | Legit Arena                           |
| `!legithelper`     | Legit Helpers Assemble!               |
| `!legitdone`       | End session ping to all Legit roles   |
| `!legithelp`       | Display this help message             |

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Feel free to open issues or submit pull requests! Make sure to run the tests (if any) and follow the existing code style.

---

*Happy gaming—and stay legit!* 🧢💰  
