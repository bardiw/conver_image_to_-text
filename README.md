# 🖼️ Convert Image to Text with OCR & Translation

This project extracts text from images using **Tesseract OCR** and optionally translates English text into **Persian (Farsi)** using **Google Translate API**.

---

## 📌 Features

- ✅ Extracts Persian text from images in `per_pics/`
- ✅ Extracts English text from images in `eng_pics/` and optionally translates to Persian
- ✅ Supports **multiple images** in each directory
- ✅ Saves the extracted (and translated) text into a `text.txt` file
- ✅ Easy-to-use command line interface

---

## 🛠️ Requirements

Install dependencies using pip:

```bash
pip install pytesseract pillow googletrans==4.0.0-rc1
```

Also, download and install Tesseract-OCR from:

🔗 https://github.com/tesseract-ocr/tesseract

⚠️ Don't forget to update this line in the script to the correct path of your Tesseract installation:

```
pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
```
