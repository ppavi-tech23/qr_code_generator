# qr-generator 📱

A simple Python QR code generator that creates colorful QR codes from text. Great for beginners learning classes, the `qrcode` library, and image customization in Python.

---

## 🎯 How It Works

- Creates a QR code from a given text (currently hardcoded as an example).  
- Lets you customize:
  - Size (`box_size`)
  - Border padding
  - Foreground color (`fg`)
  - Background color (`bg`)
- Saves the QR code as a PNG image.

Example output:

Successfully created! (sample_qr.png)

text

---

## 🐍 How to Run

1. Install the required packages:
   ```bash
   pip install qrcode[pil]
Run the script:

bash
python qr_generator.py
This will generate a QR code image named sample_qr.png in the same folder.

To customize:

Change file_name, fg, bg, size, and padding in the main() function.

To make it interactive, uncomment the input() line and remove the hardcoded user_input.

📂 Files
qr_generator.py – The main QR code generator script.

🌟 Why This Project?
Great for practicing:

Classes and __init__

Using external libraries (qrcode + Pillow)

Image handling and color customization

Simple error handling with try / except

Easy to extend (e.g., add CLI arguments, a GUI, or batch QR generation).

📜 License
This project is open source and available under the MIT License. Feel free to use, modify, and share it!
