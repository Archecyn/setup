# MacOS Setup Instructions

Notes for setting up MacOS.

<br />

# Workspace Setup

Mouse size and colour; Settings -> Accessibility -> Display
Open Terminal in apps and pin.


<br />

# Tool install

KeePassXC - keepassxc.org
Chrome
Zed code editor
Homebrew
Docker
Rust
Python + Conda + Jupyter
RustDesk
Tailscale

Ollama

```
curl -fsSL https://ollama.com/install.sh | sh
```

LM Studio - https://lmstudio.ai/


<br />

# Terminal Setup

```
ssh-keygen
```

GitHub.com


To always show hidden files:

```
defaults write com.apple.finder AppleShowAllFiles TRUE; killall Finder
```

Install Developer tools (e.g. git)

check

```
xcode-select -p

xcode-select --install
```

Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> ~/.zprofile

eval "$(/opt/homebrew/bin/brew shellenv)"
``` 

<br />

Install snapcraft

```
brew install snapcraft
```

<br />

Install Rust

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

brew install rustup

rustup install stable
rustup default stable

rustup update

rustup doc
rustfmt
```

Install AWS Cli

```
brew install awscli
```

Install GCP Cli

```
https://cloud.google.com/sdk/docs/install-sdk
```

Install Azure Cli

```
brew update && brew install azure-cli
```
