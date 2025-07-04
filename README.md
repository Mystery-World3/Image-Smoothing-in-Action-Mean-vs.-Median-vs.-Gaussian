# 🖼️ Perbaikan Citra CCTV dengan Smoothing & Noise Reduction

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/) [![OpenCV](https://img.shields.io/badge/OpenCV-4.x-blue.svg)](https://opencv.org/) [![NumPy](https://img.shields.io/badge/NumPy-1.2x-blue.svg)](https://numpy.org/)

Repositori ini berisi implementasi dari tugas mata kuliah Pengolahan Sinyal Digital. Tujuannya adalah untuk mendemonstrasikan dan membandingkan efektivitas beberapa teknik dasar *smoothing* untuk mengurangi *salt-and-pepper noise* pada citra CCTV.

---

## ✨ Fitur Utama

- **Pemrosesan Multi-Gambar**: Mampu memproses beberapa gambar sekaligus dalam satu eksekusi.
- **Simulasi Noise**: Menambahkan *salt-and-pepper noise* secara buatan untuk simulasi kasus nyata.
- **Perbandingan Filter**: Menerapkan tiga filter populer:
  - **Mean Filter**: Teknik rata-rata sederhana.
  - **Median Filter**: Teknik peredam *noise* yang tangguh.
  - **Gaussian Filter**: Teknik penghalusan dengan hasil yang natural.
- **Visualisasi Komparatif**: Menampilkan hasil perbandingan secara berdampingan untuk analisis yang mudah.

---

## 📸 Demonstrasi Hasil

Berikut adalah contoh hasil perbaikan pada salah satu citra. Terlihat jelas bagaimana **Median Filter** mampu menghilangkan hampir seluruh *noise* sambil tetap menjaga detail gambar.

| Citra Asli | Citra dengan Noise | Hasil Median Filter |
| :----------: |:-------------: | :-------------: |
| <img src="assets/cctv.jpg" width="250"> | <img src="assets/noise.png" width="250"> | <img src="assets/median.png" width="250"> |


---

## 🚀 Instalasi & Persiapan

Untuk menjalankan proyek ini di komputer Anda, ikuti langkah-langkah berikut.

1.  **Kloning repositori ini:**
    ```bash
    git clone https://github.com/Mystery-World3/Image-Smoothing-in-Action-Mean-vs.-Median-vs.-Gaussian.git
    cd Image-Smoothing-in-Action-Mean-vs.-Median-vs.-Gaussian
    ```

2.  **Buat dan aktifkan *virtual environment* (sangat disarankan):**
    ```bash
    python -m venv venv
    # Windows
    .\venv\Scripts\activate
    # macOS / Linux
    source venv/bin/activate
    ```

3.  **Instal semua dependensi yang dibutuhkan:**
    ```bash
    pip install -r requirements.txt
    ```

---

## ▶️ Cara Penggunaan

1.  Letakkan file citra Anda (format `.jpg`, `.png`, dll.) di dalam folder `assets`.
2.  Buka file `cctv.ipynb` menggunakan Jupyter Notebook atau VS Code.
3.  Perbarui daftar `daftar_file` dengan nama-nama file gambar yang ingin Anda proses.
    ```python
    # Contoh di dalam notebook
    daftar_file = [
        'assets/cctv.jpg', 
        'assets/cctv2.jpg',
        # Tambahkan file Anda di sini...
    ]
    ```
4.  Jalankan semua sel di dalam notebook untuk melihat hasilnya secara langsung!

---

## 🧑‍💻 Tim Pengembang

Proyek ini merupakan hasil kolaborasi dari:

* Muhammad Akmal Najib Gunawan
* Mhd Nursdin Al-kahfi
* Hasbi Abdullah
* Ghulam Musthofa
* Muhammad Averoes Irfan
* Muhammad Mishbahul Muflihin

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. 
