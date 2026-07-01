# ✌️ Peace Blur

Aplikasi Computer Vision sederhana menggunakan Python, OpenCV, dan MediaPipe yang mendeteksi gestur tangan **Peace (✌️)** secara real-time melalui webcam. Ketika gestur Peace terdeteksi, tampilan kamera akan otomatis diberikan efek **Gaussian Blur**.

---

## 📸 Demo

Saat gestur Peace tidak terdeteksi:
- Kamera normal.

Saat gestur Peace terdeteksi:
- Seluruh tampilan kamera menjadi blur.

---

## ✨ Fitur

- 👋 Deteksi tangan secara real-time menggunakan MediaPipe.
- ✌️ Mendeteksi gestur Peace (dua jari).
- 🌫️ Efek Gaussian Blur otomatis.
- 🎥 Menggunakan webcam.
- ⚡ Ringan dan berjalan secara real-time.

---

## 🛠 Teknologi

- Python 3.10+
- OpenCV
- MediaPipe
- NumPy

---

## 📂 Struktur Project

foto-kita-blur/
│
├── assets/
├── blur.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore

---

## 🚀 Instalasi

Clone repository

git clone https://github.com/eserzet/foto-kita-blur.git

Masuk ke folder project

cd foto-kita-blur

Install dependency

pip install -r requirements.txt

---

## ▶ Menjalankan Program

python blur.py

Tekan tombol **ESC** untuk keluar dari aplikasi.

---

## ⚙️ Cara Kerja

1. Webcam menangkap video secara real-time.
2. Setiap frame dikirim ke MediaPipe Hands.
3. Program mendeteksi posisi landmark jari.
4. Jika gestur Peace terdeteksi:
   - Seluruh frame diberi efek Gaussian Blur.
5. Jika tidak:
   - Kamera tetap tampil normal.

---

## 📚 Dependency

- mediapipe
- opencv-python
- numpy

---

## 👨‍💻 Author

**Miftah Fauzan**

GitHub:
https://github.com/eserzet

---

## 🌐 Repository

https://github.com/eserzet/foto-kita-blur

---

## 📄 License

Project ini menggunakan lisensi **MIT**.
