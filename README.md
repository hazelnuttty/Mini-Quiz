# Mini Quiz

Mini Quiz adalah aplikasi kuis berbasis web yang menampilkan pertanyaan secara acak dan mendukung pilihan bahasa Inggris dan Indonesia. Untuk pertanyaan dalam bahasa Indonesia, aplikasi mengambil data dari `database.json` yang ada dalam repository ini.

## Fitur
- Pertanyaan kuis acak dari API (bahasa Inggris) atau database lokal (bahasa Indonesia)
- Tampilan responsif dengan desain modern
- Skor real-time
- Dukungan multi-bahasa (Inggris & Indonesia)

## Cara Menggunakan
1. Clone repository ini ke komputer Anda:
   ```sh
   git clone https://github.com/username/repo-name.git
   ```
2. Buka `index.html` di browser.
3. Pilih bahasa yang diinginkan.
4. Klik tombol **Start Quiz** untuk memulai.

## Struktur File
```
├── index.html        # Halaman utama kuis
├── script.js         # Logika kuis
├── styles.css        # Gaya tampilan
├── database.json     # Kumpulan pertanyaan dalam bahasa Indonesia
└── README.md         # Dokumentasi ini
```

## Cara Menambahkan Pertanyaan
Jika ingin menambahkan lebih banyak pertanyaan dalam bahasa Indonesia:
1. Buka file `database.json`.
2. Tambahkan pertanyaan dalam format berikut:
   ```json
   {
       "question": "Pertanyaan baru di sini",
       "incorrect_answers": ["Pilihan 1", "Pilihan 2", "Pilihan 3"],
       "correct_answer": "Jawaban benar"
   }
   ```
3. Simpan perubahan dan jalankan kembali kuis.

## Kontribusi
Jika ingin berkontribusi:
1. Fork repository ini.
2. Buat branch baru untuk perubahan Anda.
3. Kirim pull request dengan deskripsi perubahan yang dilakukan.

## Lisensi
Proyek ini menggunakan lisensi MIT. Silakan gunakan dan modifikasi sesuai kebutuhan!

---

Jika ada pertanyaan atau saran, jangan ragu untuk membuka issue atau menghubungi saya melalui GitHub.

