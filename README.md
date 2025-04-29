# Termux Auto Setup Script

An automated setup script for Termux to quickly install essential and advanced packages, including Python, Git, Ruby, PHP, and popular Python libraries. Ideal for developers, ethical hackers, and enthusiasts looking to save setup time.

---

## 📌 Features

- 📡 Internet connectivity check
- 🎨 Colored terminal output and banners
- 📥 Menu-based interface (Basic or Full setup)
- ⚙️ Automatically installs:
  - Termux packages (`python`, `git`, `curl`, etc.)
  - Python libraries via `pip` and `pip2`
  - Ruby gems (e.g., `lolcat`)
- 🧰 Modular functions for easy customization

---

## 🛠️ Requirements

- Termux (Android terminal emulator)
- Active internet connection

---

## 📥 Installation & Usage

```bash
pkg update && pkg upgrade -y
pkg install git -y
git clone https://github.com/ak-alien/termux-setup-script
cd termux-setup-script
chmod +x setup.sh
./setup.sh
```

---

## 📋 Menu Options

```
[1] Basic Setup (575-700 MB)
[2] Full Setup  (665-800 MB)
[0] Exit
```

---

## ⚠️ Disclaimer

This script is intended for educational and personal use on Termux. Use responsibly. The developer is not responsible for any misuse or damage.

---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for more info.

