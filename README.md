## Cloud Drive Discord (discdrive)

This is a basic Discord bot that allows users to manage files in a virtual cloud drive. The bot is built using Node.js and the Discord.js library. The bot listens for commands and responds to user inputs to perform file management operations such as listing files, uploading files, downloading files, and changing directories.

The bot is built using an Express.js server and uses the Body Parser middleware to parse JSON data received from the client.

### Installation

1. Clone the repository
2. Install dependencies using `npm install`
3. Create a Discord bot and obtain a bot token
4. Set the bot token in an environment variable named `DISCORD_BOT_TOKEN`
5. Start the server using `npm start`

### Usage

1. Invite the bot to your Discord server
2. Use the `!clouddrive` command followed by one of the available subcommands:
    - `ls`: list files in the current directory
    - `cd <directory>`: change the current directory
    - `upload`: upload a file to the cloud drive
    - `download <filename>`: download a file from the cloud drive
3. Follow the prompts from the bot to complete the command

### CloudDrive Class

The `CloudDrive` class is responsible for managing the virtual cloud drive. It stores files in memory and provides methods for listing files, changing directories, uploading files, and downloading files.

### Dependencies

- Express.js
- Body Parser
- Discord.js

### License

This project is licensed under the MIT License. See the LICENSE file for details.
