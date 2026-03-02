# ✨ Asisten Lamaran Kerja Shakira ✨

Website *single-page application* (SPA) sederhana yang dirancang khusus untuk membantu **Shakira Aulia Najma** mengotomatiskan pembuatan draf email dan surat lamaran kerja. Dibuat agar proses *apply* kerja menjadi lebih cepat, rapi, tanpa harus pusing memikirkan *formatting* berulang kali.

🌐 **Live Demo:** [Tulis Link GitHub Pages Anda Di Sini, misal: https://username.github.io/asisten-shakira]

---

## 🚀 Fitur Utama

- **📝 Auto-Draft Email:** Membuat *body* email lamaran kerja yang formal dan profesional secara otomatis berdasarkan input (Nama Perusahaan, Posisi, dll).
- **📋 Smart Copy (Rich Text):** Tombol copy yang mempertahankan format *styling* (huruf tebal/bold dan *bullet points*) untuk di-*paste* langsung ke Gmail.
- **✉️ Integrasi Gmail:** Tombol untuk membuka tab baru yang langsung mengarah ke halaman *draft* (Tulis Pesan) Gmail dengan Tujuan dan Subjek yang sudah terisi otomatis.
- **📄 Download Surat Lamaran (.docx):** Mengonversi input secara instan menjadi dokumen Microsoft Word (Surat Lamaran Kerja) yang siap dilampirkan.
- **💖 Generator Motivasi:** Menampilkan kalimat penyemangat acak setiap kali halaman dimuat untuk menjaga semangat melamar kerja.

---

## 💻 Cara Penggunaan

1. Buka tautan website Asisten Lamaran Kerja.
2. Lengkapi form yang tersedia:
   - Nama Perusahaan Tujuan
   - Posisi Impian
   - Email HRD/Perusahaan
   - Subjek Email
3. **Untuk Email:**
   - Klik tombol **"📋 Copy Teks Email"**.
   - Buka tab Gmail baru atau klik **"✉️ Buka langsung di Gmail"**.
   - *Paste* (Ctrl+V) teks yang sudah disalin tadi ke kotak pesan Gmail agar format rapinya tetap terjaga.
4. **Untuk Dokumen:**
   - Klik tombol **"📥 Download Surat Lamaran (.docx)"**.
   - File Word akan otomatis terunduh dengan format nama file yang rapi.
5. **Finalisasi:** Jangan lupa *attach* (lampirkan) file `.docx` tadi beserta CV dan portofolio ke dalam email sebelum menekan tombol "Kirim"!

---

## 🛠️ Tech Stack & Library

Proyek ini dibangun tanpa *framework* berat agar cepat dimuat dan mudah dimodifikasi:
- **HTML5 & CSS3:** Struktur dan antarmuka (*styling* menggunakan CSS murni/Vanilla).
- **Vanilla JavaScript:** Logika pemrosesan teks, manipulasi DOM, dan generator *random quotes*.
- **[html-docx-js](https://github.com/evidenceprime/html-docx-js):** Library untuk mengonversi HTML *string* menjadi dokumen `.docx` asli.
- **[FileSaver.js](https://github.com/eligrey/FileSaver.js/):** Library untuk memicu proses unduhan file di sisi *client* (*browser*).

---

## 💡 Catatan Tambahan

Proyek ini dijalankan sepenuhnya di sisi klien (*client-side*). Tidak ada data pribadi (nama, email, no HP, atau perusahaan tujuan) yang dikirim atau disimpan di server/database mana pun. Semua proses *generate* teks dan dokumen dilakukan langsung di *browser* pengguna sehingga privasi sangat terjamin.

---
*Dibuat dengan ❤️ untuk mendukung langkah menuju karir impian.*
