📇 Contact Extractor (TXT + Image → VCF / CSV / Excel)

A powerful web-based tool to extract phone numbers from TXT files and images (OCR) and export them into VCF, CSV, or Excel formats.

---

🚀 Features

- 📄 Extract numbers from TXT files
- 📷 Extract numbers from images using OCR (Tesseract)
- 📇 Export as VCF (Contacts)
- 📊 Export as CSV / Excel
- ⚡ Fast & lightweight
- 📱 Mobile-friendly UI

---

🛠️ Tech Stack

- Flask (Backend)
- HTML / CSS (Frontend)
- Tesseract OCR
- Pandas (for CSV/Excel)

---

⚙️ Installation (Termux)

1. Update packages

pkg update && pkg upgrade

2. Install dependencies

pkg install python tesseract clang make cmake ninja pkg-config libopenblas

3. Setup environment

pip install --upgrade pip setuptools wheel cython

4. Install Python packages

pip install -r requirements.txt

---

▶️ Run the App

python newapp.py

Open in browser:

http://localhost:5000

---

📁 Supported Inputs

- ".txt"
- ".png", ".jpg", ".jpeg"

---

📤 Export Formats

- VCF (for mobile contacts)
- CSV (Excel compatible)
- Excel (.xlsx)

---

🧠 How it Works

- Regex extracts Indian phone numbers
- OCR reads text from images
- Cleaned data is exported into structured formats

---

🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

💡 Future Ideas

- Contact name detection
- Bulk image upload
- Contact preview/edit before download
- Android APK version

---

📜 License

MIT License

---

👨‍💻 Developer

RTK
Instagram: https://instagram.com/tyagirtk

---
