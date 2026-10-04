# PDF Tools

A modular, all-in-one PDF toolkit for Windows with a modern GUI (Python + CustomTkinter).

> **Download:** grab the latest `PDFTools.exe` from the [Releases](https://github.com/eazyfixgr/pdf-tools/releases) page. No installation required.

## Features

- **Compress** PDFs to reduce file size
- **Merge** and **Split** documents
- **Rearrange**, **Rotate** and **Remove duplicates**
- **Images → PDF** and **Text → PDF**
- **Word → PDF**
- **PDF → Images** and **PDF → Text**
- **Sign PDF** (draw or place a signature)
- Clean sidebar navigation with a settings panel

## Screenshots

_Add screenshots in `docs/` and reference them here._

## Getting started (run from source)

```bash
python -m pip install -r requirements.txt
python main.py
```

## Build a standalone EXE

```bash
python -m pip install pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed ^
  --collect-all customtkinter --collect-all tkinterdnd2 ^
  --name PDFTools main.py
```

The executable is created in `dist/PDFTools.exe`.

## Tech stack

- Python 3
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) for the UI
- [PyMuPDF](https://github.com/pymupdf/PyMuPDF) for PDF processing
- [Pillow](https://python-pillow.org/) and [reportlab](https://www.reportlab.com/) for images and generation
- [tkinterdnd2](https://github.com/Eliav2/tkinterDnD2) for drag & drop

## License

Released under the [MIT License](LICENSE).

---

# PDF Tools (Ελληνικά)

Ένα ολοκληρωμένο, αρθρωτό εργαλείο PDF για Windows με σύγχρονο περιβάλλον (Python + CustomTkinter).

> **Λήψη:** κατεβάστε το `PDFTools.exe` από τη σελίδα [Releases](https://github.com/eazyfixgr/pdf-tools/releases). Δεν απαιτείται εγκατάσταση.

## Δυνατότητες

- **Συμπίεση** PDF
- **Συγχώνευση** και **Διαχωρισμός**
- **Αναδιάταξη**, **Περιστροφή** και **Αφαίρεση διπλότυπων**
- **Εικόνες → PDF** και **Κείμενο → PDF**
- **Word → PDF**
- **PDF → Εικόνες** και **PDF → Κείμενο**
- **Υπογραφή PDF**
