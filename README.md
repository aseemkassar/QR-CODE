# QR Code Generator 🔳

Ek simple aur fast **Python-based QR Code Generator** jo kisi bhi text, URL, ya data ko QR code image me convert kar deta hai.

## ✨ Features

- Text ya URL se QR code generate karna
- QR code ko PNG image ke roop me save karna
- Customizable size aur error correction level
- Easy-to-use command line interface
- Lightweight aur fast

## 🛠️ Requirements

- Python 3.8 ya usse upar
- `qrcode` library
- `Pillow` library (image processing ke liye)

## 📦 Installation

1. Repository ko clone karein:
   ```bash
   git clone https://github.com/your-username/qr-code-generator.git
   cd qr-code-generator
   ```

2. Required dependencies install karein:
   ```bash
   pip install -r requirements.txt
   ```

   Ya manually install karein:
   ```bash
   pip install qrcode[pil]
   ```

## 🚀 Usage

Script run karein aur jo text/URL QR code me convert karna hai wo enter karein:

```bash
python qr_generator.py
```

Ya agar command line argument support hai:

```bash
python qr_generator.py "https://example.com"
```

QR code image current folder me `qrcode.png` naam se save ho jayegi.

### Example

```python
import qrcode

data = "https://example.com"
img = qrcode.make(data)
img.save("qrcode.png")
```

## 📁 Project Structure

```
qr-code-generator/
│
├── qr_generator.py      # Main script
├── requirements.txt     # Dependencies
├── README.md             # Project documentation
└── output/                # Generated QR codes (optional)
```

## 🤝 Contributing

Contributions welcome hain! Agar aapke paas koi suggestion ya improvement hai:

1. Repository fork karein
2. Naya branch banayein (`git checkout -b feature/naya-feature`)
3. Changes commit karein (`git commit -m 'Added naya feature'`)
4. Branch push karein (`git push origin feature/naya-feature`)
5. Pull Request open karein

## 📄 License

Ye project [MIT License](LICENSE) ke under hai.

## 📧 Contact

Koi sawal ya suggestion ho to reach out karein:
- GitHub: [aseemkassar](https://github.com/aseemkassar)

---

⭐ Agar ye project pasand aaya to repository ko star dena na bhoolein!
