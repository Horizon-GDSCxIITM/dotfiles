# Dotfiles Repository

This repository contains dotfiles for configuring Linux-based systems. Dotfiles are configuration files that control the behavior and appearance of various programs and utilities on your system. By keeping these files organized and version-controlled, it becomes easy to set up and maintain a consistent environment across multiple machines.

## Setup

To use these dotfiles on your Linux system, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using Git.

    ```bash
    git clone https://github.com/your-username/dotfiles.git ~/.dotfiles
    ```

2. **Run the Setup Script**: Navigate to the repository directory and execute the setup script.

    ```bash
    cd ~/.dotfiles
    ./setup.sh
    ```

    This script will symlink the dotfiles to their respective locations in your home directory. It may also install additional packages or perform other setup tasks as specified in the script.

3. **Customize Configuration**: Feel free to customize any of the configuration files to suit your preferences. You can edit these files directly in the repository, and changes will be reflected in your system's configuration.

4. If you want to pull `enderboi` configs then, you need to run the following command too
    ```bash
    git submobule update --init --recursive
    ```

## Contents

This repository includes configurations for various tools and programs commonly used in a Linux environment, including:

- Shell (e.g., Bash, Zsh)
- Editor (e.g., Vim, Neovim)
- Terminal emulator (e.g., Alacritty, GNOME Terminal)
- Window manager (e.g., i3, Sway)
- Desktop environment (e.g., GNOME, KDE Plasma)
- Git (global configuration, aliases)
- and more...

Feel free to explore the repository to see all the included configurations and scripts.

## Contributions

Contributions to this repository are welcome! 

Please do follow theses following rules !!
- Make a new folder of your username (or name)
- Contribute your dotfiles into that folder
- Also make a Readme and inside it put a screenshot of your config 
