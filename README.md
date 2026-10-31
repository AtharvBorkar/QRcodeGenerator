# QR Code Generator

A lightweight, easy-to-use Python CLI tool that converts URLs or plain text into high-quality QR codes and saves them as PNG image files.

---

## 📌 Project Description

**QR Code Generator** is a Python utility designed to quickly convert web links (URLs), text messages, or contact details into standard scannable QR code images. 

It leverages the [`qrcode`](https://pypi.org/project/qrcode/) Python library along with `pillow` to render and export images directly to your local machine. Ideal for sharing links, automating asset generation, or learning basic Python scripting.

---

## 🖼️ Sample QR Code

Here is an example QR code generated using this project:

- **Sample URL:** `https://github.com`
- **Output Image:** `sample.png`

<div align="center">
  <img src="sample.png" alt="Sample QR Code for https://github.com" width="240" />
  <p><i>Scan to visit <b>https://github.com</b></i></p>
</div>

---

## 🚀 Features

- ⚡ **Instant Generation:** Converts any URL or string into a QR code in seconds.
- 📁 **Custom Naming:** Prompts for your desired file name and automatically ensures the `.png` extension is appended.
- 🪶 **Minimal Dependencies:** Built on the trusted and well-supported `qrcode` library.

---

## 🛠️ Prerequisites & Installation

Make sure you have [Python 3.x](https://www.python.org/downloads/) installed on your system.

### 1. Clone the repository
```bash
git clone https://github.com/AtharvBorkar/QRcodeGenerator.git
cd QRcodeGenerator
```

### 2. Install required dependencies
The script requires the `qrcode` library and `pillow` for image rendering:

```bash
pip install qrcode pillow
```

> **Note:** If you install only `qrcode`, make sure to include pillow:
> ```bash
> pip install "qrcode[pil]"
> ```

---

## 💻 How to Use

Run the script using Python:

```bash
python main.py
```

Follow the interactive prompts in your terminal:
1. **Enter your url:** Paste or type your link (e.g., `https://github.com`).
2. **Filename you want to save it as:** Type the name for your file (e.g., `my_qrcode` or `sample.png`).
3. Your QR code image will be generated and saved in the root folder!

---

## 📂 Project Structure

```text
QRcodeGenerator/
├── main.py        # Main Python script for generating QR codes
├── sample.png     # Example generated QR code (https://github.com)
└── README.md      # Project documentation
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to use and adapt it for personal or commercial projects.
