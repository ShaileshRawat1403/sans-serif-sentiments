# 🧰 Reaper v7.0 Installation Guide

*A practical guide for installing Reaper 7.0 and getting set up in minutes (not migraines).*

---

## 1. 🎯 Who This Guide Is For

If you're installing **Reaper 7.0** for the first time (or upgrading from v6), this guide is for you.

We'll cover:
- Clean installation for Windows & macOS
- Setting up audio devices
- First-time theme/layout surprises in Reaper 7
- What to do if something breaks

---

## 2. 💻 System Requirements

### ✅ Windows:
- Windows 7/8/10/11 (32 or 64-bit)
- ~20 MB disk space
- Optional: ASIO-compatible audio interface

### ✅ macOS:
- macOS 10.5 to Ventura
- Intel or M1/M2 chips supported
- CoreAudio handles most devices automatically

> 🔍 Reaper is insanely lightweight. Even a potato with speakers can run it.

---

## 3. ⬇️ Downloading Reaper 7.0

1. Visit the official download page:  
   [https://www.reaper.fm/download.php](https://www.reaper.fm/download.php)

2. Choose your version:
   - `REAPER 7.xx Windows (64-bit)` — recommended for modern systems  
   - `REAPER 7.xx macOS (Universal)` — works for Intel & M1/M2 chips

3. Save the installer to your Downloads folder.

---

## 4. 🧭 Installation Steps

### 💽 Windows:

1. Run the `.exe` file  
2. Click **Next**, accept the license  
3. Choose install location (default is fine)  
4. Optional: Select "Portable" install if you don’t want to modify system settings  
5. Click **Install**

### 🍏 macOS:

1. Open the `.dmg` file  
2. Drag the Reaper icon into your `Applications` folder  
3. Open it from Launchpad or Spotlight  
4. macOS may prompt you with a security warning → Click **"Open Anyway"**

> ⚠️ Don’t freak out if it looks different—Reaper 7’s theme and layout are new.

---

## 5. 🔊 First-Time Audio Setup

1. Open Reaper  
2. Go to **Options → Preferences → Audio → Device**

### For Windows:
- Audio system: **ASIO** (recommended)  
- Device: Select your audio interface (Focusrite, Behringer, etc.)

> No interface? Choose **WASAPI** → Output: built-in speakers

### For macOS:
- CoreAudio will auto-select your device  
- You can change inputs/outputs here

---

## 6. 🎨 First-Time Theme/Layout Notes

Reaper 7 comes with a **completely redesigned theme** and visual layout.

If you’ve used v6 before:
- Track control panels now float with flexible alignment  
- Some toolbar icons and routing defaults have shifted

> 💡 You can still switch back to the old v6 theme from `Options → Themes`.

---

## 7. 🛠️ If Something Breaks

| Problem                           | Solution                                  |
|----------------------------------|-------------------------------------------|
| Reaper won’t open                | Right-click and run as Administrator (Win) |
| No sound output                  | Check audio device in Preferences         |
| Glitches or pops                 | Increase buffer size / sample rate        |
| Track lanes are missing          | Right-click TCP → Enable Track Lanes      |

---

## ✅ You're Ready

You’re now set up and ready to record, mix, and create chaos.  
Start with **Track → Insert new track** or drag in an audio file.

---

> “The only DAW that doesn’t get in your way... once you get past the install.” 🎯
