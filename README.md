# QR Code Generator in Python

This project is a simple QR Code Generator built using Python. It allows users to create QR codes from text or URLs, which can be saved as image files.

---

## Features

- Generate QR codes from any URL.
- Save QR codes as image files (PNG)
- Lightweight and easy to use

---

## Getting Started

### Prerequisites

Make sure you have Python installed. Then, install the required library:

```bash
!pip install pyqrcode pypng

import pyqrcode

data = "https://www.linkedin.com/in/ramneek-kaur-a62485359/"

qr = pyqrcode.create(data)

qr.png("QR.png", scale= 5)

