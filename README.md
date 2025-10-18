# 🧩 shvde12/dotfiles

Minimal, cross-platform, and fast development environment.  
Terminal, coding, automation, and games — unified under one configuration.

---

## 🚀 Concept

Universal dotfiles designed for comfortable terminal work and  
quick environment setup on macOS, Linux, or WSL2.

> Principle: clean, reproducible, and minimal.

### 💡 Features

- 🧠 Simple structure & predictable behavior  
- 🧰 Handy CLI aliases and functions  
- 💻 Development-ready: *Python, JS, C++, C#, Node.js*  
- 🐳 DevOps tools: *Docker, SSH, AWS CLI*  
- 🕹 Game configs *(e.g., CS2)*  
- 🧩 App integrations: *Neovim, Hammerspoon*  
- 🌑 No autosuggestions or external themes — clean terminal interface  

---

## 💻 Terminal

🕶 Dark theme, soft contrast colors.  
Minimal prompt style:

```bash 
username $

Each user sees their own name automatically.
No autosuggestions or syntax highlighting —
instant shell startup and minimal load.

🧱 Structure
arduino
Copy code
dotfiles/
│
├── zsh/
│   ├── .zshrc
│   ├── aliases.zsh
│   ├── exports.zsh
│   └── functions.zsh
│
├── git/
│   ├── .gitconfig
│   └── .gitignore
│
├── config/
│   └── config.toml
│
├── apps/
│   ├── hammerspoon/
│   │   ├── init.lua
│   │   └── modules/
│   │       ├── window.lua
│   │       └── audio.lua
│   └── neovim/
│       └── .vimrc
│
├── games/
│   └── cs2/
│       └── autoexec.cfg
│
├── setup.sh
└── README.md
🔧 Customization
Add or modify files within the corresponding directories:

Folder  Purpose
zsh/  Shell setup, aliases, functions
git/  Global Git configuration
config/  Shared configuration (e.g. config.toml)
apps/  App settings (Neovim, Hammerspoon, etc.)
games/  Game-specific configs (CS2 and others)

New configs can be automatically linked via setup.sh.

💾 Compatibility
OS  Support
macOS  ✅ Full
Linux  ⚙️ Partial (no Hammerspoon)
Windows (WSL2)  🧩 In testing

📜 License
MIT License — free to use, modify, and distribute.