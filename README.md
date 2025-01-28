# 🧵 Panduan Lengkap: Variabel dan Tipe Data di Python  

Selamat datang di **Panduan Variabel dan Tipe Data Python**! 🚀  
Repository ini dirancang untuk membantu Anda memahami salah satu dasar terpenting dalam pemrograman Python: **variabel** dan **tipe data**.  

---

## 🤔 Apa Itu Variabel?  

Variabel adalah cara kita memberi nama pada data yang ingin kita simpan dan gunakan di program. Ibarat laci di lemari, variabel adalah label untuk menyimpan sesuatu agar mudah ditemukan lagi!  

Contoh:  
```python
nama = "Ayu"
umur = 25
tinggi = 160.5

print(f"Halo, nama saya {nama}, umur saya {umur}, dan tinggi saya {tinggi} cm.")
```

---

## 🎨 Jenis-Jenis Tipe Data di Python  

Python memiliki tipe data bawaan yang sangat fleksibel. Berikut adalah yang paling umum:  

### 1. **Tipe Data Dasar**
| Tipe Data   | Contoh              | Penjelasan                                |
|-------------|---------------------|------------------------------------------|
| **String**  | `"Hello, Python!"`  | Teks, diapit tanda kutip (`"` atau `'`).  |
| **Integer** | `42`                | Bilangan bulat (positif atau negatif).   |
| **Float**   | `3.14`              | Bilangan desimal (pecahan).              |
| **Boolean** | `True`, `False`     | Nilai logika (benar/salah).              |

### 2. **Tipe Data Koleksi**
| Tipe Data   | Contoh                       | Penjelasan                                         |
|-------------|------------------------------|---------------------------------------------------|
| **List**    | `[1, 2, 3]`                  | Kumpulan elemen yang dapat diubah (mutable).      |
| **Tuple**   | `(1, 2, 3)`                  | Mirip list, tetapi tidak dapat diubah (immutable).|
| **Set**     | `{1, 2, 3}`                  | Kumpulan elemen unik, tanpa duplikasi.           |
| **Dictionary** | `{"nama": "Ayu", "umur": 25}` | Pasangan kunci-nilai (key-value pair).          |

---

## 🛠️ Contoh Kasus Praktis  

Berikut adalah contoh penggunaan variabel dan tipe data:  

### 🎒 **Menghitung Luas Lingkaran**  
```python
import math

jari_jari = 7
luas = math.pi * jari_jari ** 2
print(f"Luas lingkaran dengan jari-jari {jari_jari} adalah {luas:.2f}")
```

### 📝 **Mengelola Data Siswa**  
```python
siswa = {"nama": "Dika", "kelas": "XII IPA", "nilai": [85, 90, 88]}
rata_rata = sum(siswa["nilai"]) / len(siswa["nilai"])
print(f"Siswa {siswa['nama']} dari {siswa['kelas']} memiliki rata-rata nilai {rata_rata:.2f}.")
```

---

## 🚀 Proyek Mini  

1. **Konverter Suhu**: Ubah suhu dari Celsius ke Fahrenheit atau Kelvin.  
2. **Pengelola Daftar Belanja**: Tambah, hapus, dan tampilkan daftar belanja menggunakan list.  
3. **Sistem Penilaian**: Input nilai, hitung rata-rata, dan tentukan predikat berdasarkan tipe data.  

---

## 💻 Cara Menggunakan Repository  

1. Clone repository ini:  
   ```bash
   git clone https://github.com/username/python-variables-datatypes.git
   ```  
2. Jalankan contoh file Python:  
   ```bash
   python3 examples/nama_file.py
   ```  

---

## 🌟 Kontribusi  

Kami terbuka untuk kontribusi! Jika Anda memiliki ide baru, tambahkan contoh atau perbaiki dokumentasi, silakan buka **Pull Request** atau ajukan **Issue**.  

---

## 📧 Kontak  

📩 Email: [ranggis@gmail.com](ranggis@gmail.com)  
🌐 Website: [rranggis.com](https://ranggis.com)  

---

⭐ **Berikan bintang pada repository ini jika Anda merasa terbantu!** ⭐  

✨ **Selamat belajar Python dan eksplorasi tipe data yang seru!** 😊  
