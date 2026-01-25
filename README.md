## Installation

### Prerequisites
- [Komorebi](https://github.com/LGUG2Z/komorebi) - Tiling window manager
- [WHKD](https://github.com/LGUG2Z/whkd) - Hotkey daemon
- [YASB](https://github.com/denBot/yasb) - Status bar

### Setup

1. **Clone this repository:**
   ```powershell
   git clone <your-repo-url> ~/.config
   cd ~/.config
   ```

2. **Set environment variable (add to PowerShell profile):**
   ```powershell
   $Env:KOMOREBI_CONFIG_HOME = 'C:\Users\YourUsername\.config\komorebi'
   ```

3. **Start the components:**
   ```powershell
   # Start komorebi & hotkey daemon
   komorebic start --whkd
   
   # Start status bar
   yasbc start
   ```
