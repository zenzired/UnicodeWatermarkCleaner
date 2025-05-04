# 🧼 Unicode Watermark Cleaner

Detect and remove invisible Unicode watermark characters from text and documents

A lightweight desktop app that detects, highlights, and removes **invisible Unicode watermark characters** from documents or pasted text.  
Built with Python and PyQt5 — supports `.txt`, `.docx`, `.pdf`, `.rtf`, and raw pasted text.

![app-preview](https://raw.githubusercontent.com/YOUR_USERNAME/UnicodeWatermarkCleaner/main/screenshots/app-ui.png)

---

## ✨ Features

- ✅ Drag & drop `.txt`, `.docx`, `.pdf`, `.rtf` files
- ✅ Paste raw text directly
- ✅ Detects zero-width Unicode characters:
  - `U+200B` Zero Width Space
  - `U+200C` Zero Width Non-Joiner
  - `U+200D` Zero Width Joiner
  - `U+2060` Word Joiner
  - `U+FEFF` Zero Width No-Break Space
- ✅ Highlights watermarks with `[ZWSP]`, `[ZWNJ]`, etc.
- ✅ Toggle highlighting on/off
- ✅ Navigate to next detected watermark
- ✅ Clean and save output as `.txt` or `.docx`
- ✅ View cleaning statistics (count, % of document)
- ✅ Keyboard shortcuts:
  - `Ctrl+H`: Toggle highlight
  - `Ctrl+N`: Next watermark
  - `Ctrl+S`: Save cleaned text

---

## 📦 Downloads

> 🔐 **SmartScreen Warning?**  
This app is unsigned. If Windows warns you:
1. Click **More Info**
2. Click **Run Anyway**

| Version | File | Link |
|--------|------|------|
| v1.0.0 | Standalone EXE | [Download unicode_cleaner.exe](https://github.com/YOUR_USERNAME/UnicodeWatermarkCleaner/releases/download/v1.0.0/unicode_cleaner.exe) |
|        | Installer EXE  | [Download Installer](https://github.com/YOUR_USERNAME/UnicodeWatermarkCleaner/releases/download/v1.0.0/UnicodeWatermarkCleaner_Installer.exe) |

---

## 🛠 Developer Setup

```bash
git clone https://github.com/YOUR_USERNAME/UnicodeWatermarkCleaner.git
cd UnicodeWatermarkCleaner
pip install -r requirements.txt
python unicode_cleaner.py
```

---

## 🧪 Build Your Own Executable

```bash
pip install pyinstaller
pyinstaller --noconfirm --windowed --onefile unicode_cleaner.py
```

Output: `dist/unicode_cleaner.exe`

---

## 📜 License

This project is licensed under the MIT License.

---

## 🧠 Credits

Created by [Your Name]  
Inspired by privacy-first tooling and secure document practices.
