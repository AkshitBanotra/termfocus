# TermFocus

**TermFocus** is a modular productivity CLI toolkit built in Bash. It allows you to manage your workflow, take breaks, journal your thoughts, and track time — all from the terminal. Each tool can also be used separately, or together via the main TermFocus menu.

## Features

- **Pomodoro:** Customize work timer, break timer, long break timer (default: 25, 5, 15 minutes) and session count (1-5).  
- **Animedoro:** Focus on work sessions while enjoying anime during breaks. Enter anime name and episode number; integrates with `ani-cli` to automatically open/close the anime during breaks.  
- **Journaling:** Vim-based CLI journal.  
  - Create new journal logs automatically with date-based filenames.  
  - Search, view, edit, or remove old logs by date.  
- **Simple Timer:** Track custom time periods easily from the terminal.

## Dependencies

TermFocus requires the following tools:

- rofi
- ani-cli
- notify-send
- paplay
- figlet
- lolcat

The included setup script will attempt to install missing dependencies automatically, using commands appropriate for your Linux distro (tested on EndeavourOS / Arch-based systems).  
For other distros, you may need to install dependencies manually.

## Installation

Clone the repository and run the setup script:

```bash
git clone https://github.com/yourusername/termfocus.git
cd termfocus
./setup.sh # Setup script coming soon -- Currently manual setup required.
