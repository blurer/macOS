# MacOS Setup

## Systems

- M1 mini: m1, 8gb, 256gb, 1tb nvme via dock
- M4 mbp: m4 pro, 24gb, 512gb

## Initial setup

- Install homebrew: ``/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``
- Add brew to path: ``echo "export PATH=/opt/homebrew/bin:$PATH" >> ~/.bash_profile && source ~/.bash_profile``
- Install tabby (my preferred terminal): ``brew install --cask tabby``

## Install brews

brew install htop vim git curl macmon stats tailscale uv python python-pip coreutils jq ansible btop
brew install --cask firefox obsidian discord visual-studio-code 1password appcleaner hiddenbar microsoft-word microsoft-excel raycast

### App Descriptions

- clop: compression
- raycast: alfred alternative
- uv: pip+venv alternative
- macmon: htop+btop alternative
- coreutils: GNU File, Shell, and Text utilities