# Nexus Exchange Bot

## Overview
The Nexus Exchange Bot is a Discord bot designed to facilitate currency exchange and middleman requests through a ticketing system. Users can easily create tickets for their exchange needs, and the bot manages the communication between users and exchangers in dedicated channels.

## Features
- **Ticket Creation**: Users can open tickets for currency exchange or middleman requests using an interactive embed menu.
- **Channel Management**: Each ticket creates a dedicated channel for communication, ensuring privacy and organization.
- **Permission Control**: The bot manages permissions to ensure that only the ticket creator and designated exchangers can interact within the ticket channels.
- **Support Controls**: Users can close tickets and access support controls, including transcript retrieval and ticket deletion.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/nexus-exchange-bot.git
   cd nexus-exchange-bot
   ```

2. **Install Dependencies**:
   Make sure you have Node.js installed, then run:
   ```bash
   npm install
   ```

3. **Configure the Bot**:
   Edit the `config.json` file to include your Discord bot token and any necessary role IDs.

4. **Run the Bot**:
   Start the bot using:
   ```bash
   npm start
   ```

## Usage
- Users can interact with the bot by clicking buttons in the embed menu to create tickets.
- The bot will guide users through the process of specifying their exchange needs.
- Exchangers can monitor and respond to requests in the designated ticket channels.

## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests to improve the bot's functionality.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
