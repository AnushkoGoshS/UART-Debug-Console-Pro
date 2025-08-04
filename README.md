# COMING SOON - August 10, 2025

# 🔧 UART GUI Debug Console Pro – Raspberry Pi 5 Edition

### 📅 Coming August 10, 2025  
**Multilingual (EN / DE)**  
**Designed & Developed by Thorsten Bylicki | BYLICKILABS**

---

## 🚀 About the Tool

**UART Debug Console Pro** is a modern, user-friendly desktop application to monitor and interact with the UART serial interface of your **Raspberry Pi 5**.  
Built for developers, system integrators, and embedded engineers, this tool is the **ideal solution for headless debugging**, live diagnostics, and console-level interaction — without the need for HDMI or SSH.

---

## ⚙️ Features at Launch

- ✅ Full UART interface access (RX/TX/GND via USB-to-TTL)
- 🧪 Live console with timestamped output
- 🔍 Filter support (Regex & Text)
- ⏱️ Realtime runtime counter + line count
- 🌐 Language switcher: DE / EN
- 🎨 Dark Mode toggle
- 📈 Live temperature visualization (Matplotlib)
- 🔁 Autoreconnect + Keep-alive (Ping)
- 🗂 Export logs (TXT)
- 🧠 Command history and hot-buttons
- ℹ️ Info panel + GitHub shortcut
- 📄 Configurable via `settings.json`

---

## 📦 Installation

**Requirements:**

- Python 3.8+
- OS: Windows, macOS, Linux
- Raspberry Pi 5 (target device)

**Install dependencies:**

```bash
pip install pyserial matplotlib

Optional:
pip install -r requirements.txt
```

**Run the app:**

```bash
python app.py
```

---

## 📁 Project Structure

```
uart_debugger_pro/
├── app.py                 # Main application (GUI)
├── settings.json          # Config (language, baudrate, port, etc.)
├── logs/                  # Exported session logs
├── README.md              # This file
```

---

## 🌍 Language Support

> Toggle live within the application – no restart required!

---

## 🛠 Use Case Example

1. Connect the USB-to-TTL cable (e.g. FTDI FT232) to the Pi’s UART header
2. Launch the app on your PC
3. Select the serial port and baudrate (default: `115200`)
4. View logs, send commands, visualize temperature, and debug in real-time

---

## 📅 RELEASE

**🗓️ Date:** August 10, 2025  
**🌐 Available in:** English & German  
**📁 Format:** Python source (.py) & .exe (Windows binary, optional)

---

## 🧾 License

© 2025 Thorsten Bylicki • [BYLICKILABS](https://github.com/bylickilabs)  
All rights reserved. Redistribution without explicit permission is prohibited.

---

## 🔗 GitHub

> Follow the development and get the latest updates on  
[https://github.com/bylickilabs](https://github.com/bylickilabs)
