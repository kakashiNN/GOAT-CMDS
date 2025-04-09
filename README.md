# Eren's Command Store

This is a simple **cmdstore** system for storing and displaying commands available in your bot. It uses a JSON structure to store the commands and provides a user-friendly interface to view them.

## Features

- **List Commands**: Shows available commands, their authors, and last updated dates.
- **Pagination**: Supports pagination to display commands in multiple pages.
- **Search**: Allows searching by command name or page number.
- **Links to Commands**: Fetches and displays raw URLs for each command.

## Usage

- To use, type **cmdstore** followed by a command name, single character, or page number to find relevant commands.
- For example:  
  `cmdstore truthdare`  
  `cmdstore 1` (for page 1)

## Setup

1. Clone this repository to your local machine.
2. Upload the **availableCmds.json** and **cmdUrls.json** files to GitHub or your hosting provider.
3. Install required dependencies using `npm install`.
4. Run your bot with **cmdstore.js** integrated.

## File Structure

- **availableCmds.json**: Stores a list of available commands.
- **cmdUrls.json**: Maps commands to their respective raw URLs.
- **cmdstore.js**: The command handler and display system.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Eren Yeh** | Developer  
For support, contact **Eren** on WhatsApp: +8801839268235
