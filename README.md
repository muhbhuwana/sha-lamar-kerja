# ✨ Asisten Lamaran Kerja Shakira ✨

Website *single-page application* (SPA) sederhana yang dirancang khusus dengan penuh cinta untuk membantu **Shakira Aulia Najma** mengotomatiskan pembuatan draf email dan surat lamaran kerja. Sekarang dilengkapi dengan Kecerdasan Buatan (AI) untuk mempercepat proses *apply* kerja!

🌐 **Live Demo:** [Tulis Link GitHub Pages Anda Di Sini, misal: https://username.github.io/asisten-shakira]

---

## 🌟 Fitur Unggulan Terbaru

- **🤖 Auto-Isi dari Poster Loker (AI Gemini):** Cukup upload screenshot/foto lowongan kerja, AI akan otomatis membaca dan mengekstrak Nama Perusahaan, Posisi, dan Email HRD dengan format *Title Case* yang rapi.
- **🖼️ Preview & Zoom Gambar:** Gambar poster yang diupload bisa langsung dilihat dan diklik untuk di-*zoom* (layar penuh) agar mudah melakukan kroscek data.
- **📋 Tombol Quick Paste:** Tombol tempel (paste) cerdas di sebelah kolom input untuk mempercepat pengisian data tanpa harus tahan layar HP lama-lama.
- **💖 Motivasi Spesial:** Penambah semangat dengan desain *soft pink* dan kalimat-kalimat manis (dengan panggilan sayang secara acak) setiap kali web dibuka.
- **⚙️ Input Personal Dinamis:** Nomor HP dan Email pengirim kini bisa diedit langsung dari tampilan web, tidak lagi terkunci di dalam kode.

## 🚀 Fitur Utama

- **📝 Auto-Draft Email:** Membuat *body* email lamaran kerja formal secara otomatis.
- **📋 Smart Copy (Rich Text):** Tombol copy yang mempertahankan format *styling* (huruf tebal/bold dan *bullet points*) untuk di-*paste* langsung ke Gmail.
- **✉️ Integrasi Gmail Cerdas:** Tombol yang langsung membuka aplikasi Gmail (di HP/iOS) atau tab Gmail baru (di PC) dengan Tujuan, Subjek, dan Body yang sudah terisi.
- **📄 Download Surat Lamaran (.docx):** Mengonversi input secara instan menjadi dokumen Microsoft Word siap pakai.

---

## 💻 Cara Penggunaan

### A. Menggunakan Fitur AI (Sangat Disarankan)
1. Buka website Asisten Lamaran Kerja.
2. Masukkan **Gemini API Key** rahasia ke dalam kolom yang tersedia. *(Kunci ini hanya perlu dimasukkan satu kali seumur hidup karena akan tersimpan otomatis di browser HP/Laptop)*.
3. Klik "Choose File" dan pilih foto/screenshot poster lowongan kerja.
4. Klik **✨ Ekstrak Data** dan tunggu beberapa detik.
5. *Voila!* Kolom Perusahaan, Posisi, dan Email HRD akan terisi otomatis. (Kamu bisa klik gambar poster yang muncul untuk memperbesar dan kroscek ulang).

### B. Cara Manual
1. Ketik manual atau gunakan tombol **📋** untuk menempelkan teks *copy-paste* ke kolom Perusahaan, Posisi, dan Email HRD.
2. Subjek akan otomatis terbuat dengan format `Posisi_Nama`. (Bisa diedit manual jika perusahaan meminta format khusus).

### C. Mengirim Lamaran
1. Klik tombol **"📋 Copy Teks Email"**.
2. Klik **"✉️ Buka langsung di Gmail"**.
3. *Paste* (Tempel) teks yang sudah disalin tadi ke kotak isi pesan Gmail agar tulisan tebalnya (bold) tetap rapi.
4. **JANGAN LUPA:** *Attach* (lampirkan) file CV dan Surat Lamaran (.docx) yang sudah di-download sebelum klik Kirim!

---

## 🤖 Panduan Mendapatkan Gemini API Key

Karena fitur AI membaca gambar membutuhkan akses ke model Google Gemini, kamu memerlukan API Key gratis:
1. Buka [Google AI Studio](https://aistudio.google.com/app/apikey) dan login dengan akun Google.
2. Klik **Create API Key** (pilih di *new project*).
3. Salin kode kunci tersebut (berawalan `AIzaSy...`).
4. Paste ke dalam kolom API Key di website asisten ini.

---

## 🛠️ Tech Stack & Library

- **HTML5, CSS3, Vanilla JavaScript**
- **Google Gemini API (`gemini-1.5-flash`)** untuk ekstrasi teks multimodal (OCR + LLM).
- **[html-docx-js](https://github.com/evidenceprime/html-docx-js):** Untuk konversi HTML ke `.docx`.
- **[FileSaver.js](https://github.com/eligrey/FileSaver.js/):** Untuk memicu unduhan file secara lokal.

---

## 🔒 Privasi & Keamanan Terjamin

Website ini berjalan 100% di sisi klien (*client-side*). Data pribadi (Nama, No HP, Email) maupun dokumen lamaran **TIDAK PERNAH** dikirim atau disimpan ke server manapun.
Gemini API Key disimpan menggunakan `localStorage` langsung di dalam browser pengguna demi keamanan maksimal dan mencegah eksploitasi kunci publik di GitHub.

---
*Dibuat dengan ❤️ untuk mendukung langkah menuju karir impian.*
