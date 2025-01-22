# .bashrc Configuration

This is a custom `.bashrc` configuration for setting up a more user-friendly and efficient Bash environment on a Linux system. It includes essential configurations for command history management, prompt customization, aliases, and additional enhancements for a better terminal experience.

## Features

- **Interactive Shell**: Ensures the script only runs in an interactive shell.
- **History Management**: 
  - Prevents duplicate lines in history.
  - Appends to the history file instead of overwriting it.
  - Configures history size.
- **Window Size Check**: Automatically adjusts terminal window size after each command.
- **Prompt Customization**: 
  - Sets a color-friendly prompt if supported by the terminal.
  - Displays the username, hostname, and current working directory in different colors.
  - Adjusts the terminal title for xterm-like terminals.
- **Command Aliases**: 
  - Simplifies common commands like `att` (update and upgrade), `shutdown`, `reboot`, and navigation with `..` and `...`.
  - Clears the terminal with `c`.
- **Color Support for Commands**: Adds color support to `ls` and other commands for better readability.
- **Programmable Completion**: Enables autocompletion for commands and paths.
- **Command Spell Correction**: Automatically corrects simple typing errors in commands like `cd` and directory names.

## Installation

To apply these settings, copy the content of this `.bashrc` file into your `~/.bashrc` file:

```bash
cp .bashrc ~/.bashrc
