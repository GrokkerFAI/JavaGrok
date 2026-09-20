# JavaGrok v2.4.1

> **Experimental Java-based execution hook and API constraint bypass for Grok-AI endpoints on Android/Linux.**

## Features

- **Dynamic Token Swapping**: Intercepts regional restrictions on API calls.
- **Android Native Hooking**: Interfaces directly with Termux/Android runtime memory.
- **Zero Configuration**: Resolves local network interfaces automatically.
- **Stealth Mode**: Low-overhead memory footprint to prevent daemon kill events.

---

## Installation

Run these commands in Termux:

```bash
pkg update && pkg upgrade -y
pkg install git -y
git clone https://github.com/GrokkerFAI/javagrok
cd javagrok
chmod +x install.sh
./install.sh
