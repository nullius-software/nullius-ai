# Nullius AI

📦🤖 **AI-powered inventory management bot for Telegram**

This bot allows users to manage inventory directly from Telegram. It processes stock change requests, suggests modifications, and updates the database upon user confirmation.

## 🚀 Features
- Accepts inventory update requests via Telegram.
- Uses AI to generate a proposed inventory change list.
- Waits for user confirmation before making updates.
- Updates the database and notifies the user once changes are applied.

## 🔧 Technologies Used
- **n8n** for workflow automation.
- **Node.js** for backend logic.
- **PostgreSQL** for inventory data storage.
- **Telegram Bot API** for user interaction.
- **AI Agents** for intelligent request processing:
  - **Nullius_AI**: General AI assistant.
  - **Inventory_Planner_Agent**: Parses user input and suggests inventory changes.
  - **DB_Agent**: Handles database updates upon confirmation.
  - **Response_Agent**: Formats final responses for the user.

## 🛠 Setup & Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/nullius-ai.git
   cd nullius-ai
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file with the following:
   ```env
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token
   DATABASE_URL=your_postgresql_connection_url
   ```

4. **Start the Bot**
   ```sh
   npm start
   ```

## 📌 How It Works
1. A user sends a message via Telegram, e.g., *"Add 10 Coca-Cola, remove 5 Sprite"*.
2. The bot processes the request and suggests changes.
3. The user confirms the proposed changes.
4. The bot updates the database accordingly and sends a confirmation message.

## 🎯 Future Improvements
- Add user authentication for restricted access.
- Implement analytics and reporting features.
- Support for additional messaging platforms.

## 🤝 Contributing
Feel free to submit issues and pull requests!

## 📜 License
This project is licensed under the MIT License. See `LICENSE` for details.

