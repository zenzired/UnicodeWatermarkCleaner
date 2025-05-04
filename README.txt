Unicode Watermark Cleaner
==========================

This Windows desktop application detects and removes hidden Unicode characters (like zero-width spaces or watermarks)
from text-based files. These invisible characters are often used for tracking or formatting and may cause issues
in document processing or distribution.

-------------------------
📂 Supported Input Formats
-------------------------
- .txt
- .docx
- .pdf
- .rtf
- Pasted text

-------------------------
💡 Features
-------------------------
- Drag-and-drop file support
- Paste and clean custom text
- Side-by-side view of original vs cleaned
- Highlight zero-width characters like ZWSP, ZWNJ, ZWJ, etc.
- Toggle highlight on/off
- Navigate to next watermark
- Stats report on removal
- Export to .txt or .docx
- Diff view (optional enhancement)
- Keyboard shortcuts (Ctrl+H, Ctrl+N, Ctrl+S, Ctrl+L)

-------------------------
🚀 How to Use
-------------------------
1. Double-click `unicode_cleaner.exe` inside the /dist folder
2. Drag and drop a file or paste text into the interface
3. View highlights, toggle highlight visibility, scroll to markers
4. Click "Save Cleaned File" to export result

-------------------------
🔧 Developer Notes
-------------------------
To build the executable manually, use:
> build_exe.bat

Ensure you have Python 3.8+ and run:
> pip install -r requirements.txt
> pyinstaller --noconfirm --windowed --onefile unicode_cleaner.py

-------------------------
📋 License
-------------------------
This is a demo tool created for educational and professional use. Please ensure documents scanned or cleaned do not violate confidentiality or distribution rights.