# 🚀 Haha Wallet BOT

> Automated claim karma and quest completion and multi-account management


## 🎯 Overview

Haha Wallet BOT is an automated tool designed to claim karma and quest completion across multiple accounts. It provides seamless offers robust proxy support for enhanced security and reliability.

**🔗 Get Started:** [Register on Haha Wallet](hhttps://join.haha.me/REYVALDI-QURTBV)  
**🎁 Use My Code:** `REYVALDI-QURTBV`

## ✨ Features

- 🔄 **Automated Account Management** - Retrieve account information automatically
- 🌐 **Flexible Proxy Support** - Run with or without proxy configuration
- 🔀 **Smart Proxy Rotation** - Automatic rotation of invalid proxies
- ⏰ **Claim Daily Karma** - Automated claim daily karma
- 📜 **Quest Completion** - Automated complete available quests
- 👥 **Multi-Account Support** - Manage multiple accounts simultaneously

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/dopezayn/Haha-Auto-Bot.git
cd Haha-Auto-Bot
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

### 3. Library Version Management

> ⚠️ **Important:** Ensure library versions match those specified in `requirements.txt`

**Check installed library version:**
```bash
pip show library_name
```

**Uninstall conflicting library:**
```bash
pip uninstall library_name
```

**Install specific library version:**
```bash
pip install library_name==version
```

## ⚙️ Configuration

### Account Setup

Create or edit `accounts.json` in the project directory:

```json
[
    {
        "Email": "your_email_address_1",
        "Password": "your_password_1"
    },
    {
        "Email": "your_email_address_2",
        "Password": "your_password_2"
    }
]
```

### Proxy Configuration (Optional)

Create or edit `proxy.txt` in the project directory:

```
# Simple format (HTTP protocol by default)
192.168.1.1:8080

# With protocol specification
http://192.168.1.1:8080
https://192.168.1.1:8080

# With authentication
http://username:password@192.168.1.1:8080
```

## 🚀 Usage

Run the bot using one of the following commands:

```bash
python bot.py
# or for Python 3 specifically
python3 bot.py
```

### Runtime Options

When starting the bot, you'll be prompted to choose:

1. **Proxy Mode Selection:**
   - Option `1`: Run with proxy
   - Option `2`: Run without proxy

2. **Auto-Rotation:** 
   - `y`: Enable automatic invalid proxy rotation
   - `n`: Disable auto-rotation



## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. ⭐ **Star this repository** if you find it useful
2. 👥 **Follow** for updates on new features
3. 🐛 **Report issues** via GitHub Issues
4. 💡 **Suggest improvements** or new features
5. 🔧 **Submit pull requests** for bug fixes or enhancements

## 📞 Contact & Support

- **Developer:** A K H I I
- **Issues:** [GitHub Issues](https://github.com/dopezayn/Haha-Auto-Bot/issues)
- **Discussions:** [GitHub Discussions](https://github.com/dopezayn/Haha-Auto-Bot/discussions)

---

<div align="center">

**Made with ❤️ by [vonssy](https://github.com/vonssy)**

*Thank you for using Haha Wallet BOT! Don't forget to ⭐ star this repository.*

</div>
