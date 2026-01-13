# BubbleLogin+

**BubbleLogin+** is a modern, secure and lightweight authentication plugin for Minecraft servers  
Compatible with **1.7 → 1.21.1**  
Supports **SQLite, MySQL/MariaDB** and optional **Proxy mode** (Bungee / Velocity)

---

## ✨ Features

- Secure password hashing (BCRYPT, ARGON2, SHA512)
- SQLite & MySQL support  
- Session system with IP validation  
- Anti-bot protection  
- Pre-login restrictions (movement, chat, commands, etc.)
- Fully customizable messages  
- Titles support  
- Optional Proxy mode (Login server → Lobby)
- Lightweight & optimized  

---

## 📥 Download

➡ **[Click here to download the latest version](https://github.com/BubbleAC/BubbleLogin/releases/latest)**

---

## ⚙ Installation

1. Download the `.jar` file  
2. Put it in your `plugins/` folder  
3. Restart the server  
4. Edit `config.yml`  
5. Restart again  

---

## 🗄 Database Setup

### SQLite (Default)
No setup needed.  
Just run the plugin.

### MySQL / MariaDB
Edit `config.yml`:

```yml
database:
  type: MYSQL
  mysql:
    host: "localhost"
    port: 3306
    database: "bubblelogin"
    username: "root"
    password: ""

---

## ❤️ Credits
Developed by BubbleAC
If you like it, leave a ⭐ on GitHub!
