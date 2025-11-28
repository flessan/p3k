# Panduan P3K untuk Pemula & PMR

Sebuah website statis yang komprehensif dan mudah dipahami, menyediakan panduan Pertolongan Pertama pada Kecelakaan (P3K) yang andal untuk pemula, khususnya anggota Palang Merah Remaja (PMR).

![Screenshot](https://i.imgur.com/your-screenshot-link.png) <!-- Ganti dengan link screenshot Anda -->

## ✨ Fitur-Fitur

-   **📱 Responsif & Aksesibel:** Tampilan optimal di desktop, tablet, dan ponsel.
-   **🌙 Mode Gelap/Terang:** Sesuaikan tampilan agar nyaman di mata.
-   **🔍 Pencarian Cepat:** Temukan informasi yang Anda butuhkan dengan mudah.
-   **📚 Konten Lengkap & Terpercaya:**
    -   Panduan persiapan mental dan fisik.
    -   Prinsip dasar keselamatan (DRSABCD/5B).
    -   Panduan langkah demi langkah untuk kondisi umum (luka, mimisan, luka bakar, tersedak).
    -   Peringatan jelas tentang "Apa yang TIDAK boleh dilakukan".
-   **✅ Checklist Kotak P3K Interaktif:** Dengan progress bar untuk memastikan kotak P3K Anda lengkap.
-   **🧠 Kuis Interaktif:** Uji pemahaman Anda dengan feedback edukatif.
-   **📞 Daftar Kontak Darurat:** Nomor-nomor penting siap pakai.
-   **🖨️ Cetak-Friendly:** CSS khusus untuk mencetak panduan dengan rapi.
-   **📴 Akses Offline:** Dapat diakses tanpa koneksi internet (menggunakan Service Worker).
-   **⚡ Performa Cepat:** Dibangun dengan HTML, CSS, dan JavaScript vanilla murni.

## 🚀 Cara Menjalankan

1.  **Clone repositori ini:**
    ```bash
    git clone https://github.com/username/panduan-p3k.git
    ```
2.  **Masuk ke direktori proyek:**
    ```bash
    cd panduan-p3k
    ```
3.  **Jalankan server lokal (opsional, tapi direkomendasikan):**
    Anda bisa menggunakan ekstensi `Live Server` di VS Code atau menjalankan server sederhana dengan Python:
    ```bash
    # Python 3
    python -m http.server
    # Python 2
    python -m SimpleHTTPServer
    ```
4.  **Buka di browser:**
    Buka `http://localhost:8000` (atau port yang ditampilkan) di browser web Anda.

Anda juga bisa langsung membuka file `index.html` di browser, tetapi beberapa fitur (seperti Service Worker) mungkin tidak berjalan sempurna tanpa server lokal.

## 🛠️ Teknologi yang Digunakan

-   **HTML5**
-   **CSS3** (dengan CSS Variables dan Grid/Flexbox)
-   **Vanilla JavaScript (ES6+)**
-   **Service Worker API** (untuk offline support)

## 🤝 Kontribusi

Kontribusi sangat terbuka! Jika Anda menemukan bug, memiliki saran, atau ingin menambah konten, silakan:

1.  Fork repositori ini.
2.  Buat branch baru (`git checkout -b fitur-baru`).
3.  Commit perubahan Anda (`git commit -am 'Menambah panduan gigitan ular'`).
4.  Push ke branch (`git push origin fitur-baru`).
5.  Buat Pull Request.

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detailnya.

## ⚠️ Disclaimer

Panduan ini dibuat untuk tujuan edukasi dan bukan pengganti pelatihan medis profesional atau saran dokter. Dalam situasi darurat, selalu prioritaskan keselamatan dan segera hubungi layanan darurat medis.
