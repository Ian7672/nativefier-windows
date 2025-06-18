# 🖥️ NATIV-ER-INSTALL - Web to Desktop App Converter

[![GitHub release](https://img.shields.io/github/v/release/Ian7672/nativefier-windows?style=for-the-badge)](https://github.com/Ian7672/nativefier-windows/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Ian7672/nativefier-windows/total?style=for-the-badge&color=success)](https://github.com/Ian7672/nativefier-windows/releases)
[![Windows Support](https://img.shields.io/badge/Windows-10%2B-0078D6?style=for-the-badge&logo=windows)](https://support.microsoft.com/en-us/windows)
[![No Admin Needed](https://img.shields.io/badge/No%20Admin%20Rights-Required-green?style=for-the-badge)]()

### What is Nativefier?
Nativefier is a powerful open-source tool that converts any web application into a standalone desktop application. It wraps websites in a minimal Electron container, providing a native-like experience without requiring browser tabs.

### Key Features:
- 🖥️ **Desktop Integration** - Runs as separate app with its own icon and window
- 🔐 **Isolated Session** - Separate cookies and storage from your browser
- 🚫 **No Browser Toolbar** - Clean interface without address bar or tabs
- 📌 **Pinned Apps** - Keep frequently used web apps easily accessible
- 🔋 **Offline Support** - Limited functionality when offline (depends on website)

### How It Works:
1. Nativefier uses Electron to create a lightweight Chromium browser
2. It loads your specified website as the "app"
3. Packages everything into an executable (.exe, .app, .deb etc.)
4. Adds native menus and basic desktop integration

### Technical Requirements:
- Node.js (for building apps)
- npm/yarn (to install Nativefier)
- Internet connection (for initial packaging)

Transform web applications into lightweight desktop apps with our user-friendly installer. Perfect for creating standalone versions of your favorite web tools without administrator privileges.

## 🌟 Key Features
- 🚀 **One-click installer** - Simple EXE with drag-and-drop support
- 🖱️ **Fully GUI-based** - No command line needed
- 🏠 **User-space installation** - No admin rights required
- 📌 **Automatic shortcuts** - Desktop & Start Menu
- 🗑️ **Clean uninstallation** - Through Windows Settings
- 🔄 **Easy updates** - Just re-run the installer

## 🛠️ System Requirements
| Component | Minimum |
|-----------|---------|
| OS | Windows 10+ |
| PowerShell | Version 5.1+ |
| 7-Zip | (Optional) For manual extraction |

## 📥 Installation Methods

**Download NATIV-ER-INSTALL.exe**: [install](https://raw.githubusercontent.com/Ian7672/nativefier-windows/main/NATIV-ER-INSTALL.exe)

### Method 1: Double-Click Install
1. Download both files:
   - `NATIV-ER-INSTALL.exe`
   - Your app `.7z` package
2. Place them in the same folder
3. Double-click `NATIV-ER-INSTALL.exe`

### Method 2: Drag & Drop (Recommended)
1. Download both files
2. Simply drag the `.7z` file onto `NATIV-ER-INSTALL.exe`
3. Follow the on-screen instructions


## Demo Drag Drop

[Drag and Drop Demo](https://github.com/user-attachments/assets/5885c8c9-e63a-42dd-9260-08795bd214e3)

## 📂 File Structure After Installation
```
YourInstallPath/
└── AppName/
    ├── app.exe          # Main application
    ├── resources/      # All required files
    └── uninstall.json  # Uninstallation info
```

## 🔄 Updating Apps
1. Download the new `.7z` package
2. Run the installer again
3. Choose the same installation folder

The installer will automatically:
- Preserve your settings
- Update the application
- Keep existing shortcuts

## ❓ Frequently Asked Questions

### Installation
**Q: Why don't I need admin rights?**  
A: The installer works entirely in your user space, installing to your personal folders.

**Q: What if I don't have 7-Zip installed?**  
A: The installer includes built-in extraction capabilities - no additional software needed.

### Usage
**Q: How do I create additional shortcuts?**  
A: Right-click the app.exe and select "Create shortcut"

**Q: Can I move the installed app?**  
A: Yes! Just move the entire folder and update shortcuts manually.

## ⚠️ Troubleshooting

| Issue | Solution |
|-------|----------|
| Installer won't start | Check your antivirus isn't blocking it |
| Missing shortcuts | Run installer again and recreate shortcuts |
| App won't launch | Ensure all files are in the same folder |

## 📜 License
MIT License - [Full License Text](https://github.com/Ian7672/nativefier-windows/blob/main/LICENSE)

---

## 📦 Release Info

🔗 **Nativefier Project**: [github.com/nativefier/nativefier](https://github.com/nativefier/nativefier)  
🚀 **Download Rilis Windows**: [Releases – Ian7672/nativefier-windows](https://github.com/Ian7672/nativefier-windows/releases)  
🐛 **Laporkan Masalah / Bug**: [GitHub Issues](https://github.com/Ian7672/nativefier-windows/issues)  
📬 **Kontak Developer**: [@Ian7672](https://github.com/Ian7672)
