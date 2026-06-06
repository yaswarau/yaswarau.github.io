# 💒 Digital Wedding Invitation — Jonathan & Elizabeth

Undangan pernikahan digital versi Kristen dengan desain elegan, responsive, dan fitur lengkap. Dibangun menggunakan **HTML**, **Tailwind CSS**, dan **Alpine.js** — single file, tanpa backend.

## 🔗 Demo

Buka `index.html` di browser. Tambahkan parameter `?to=Nama+Tamu` untuk personalisasi nama tamu.

```
index.html?to=John+Smith
```

---

## ✨ Daftar Fitur Utama

### 1. Loading Screen
Splash screen saat halaman dimuat menampilkan foto pasangan, nama pengantin, dan animasi spinner ring. Otomatis hilang setelah 1.8 detik.

### 2. Envelope Opening (Buka Amplop)
Halaman pembuka berbentuk amplop digital yang menampilkan nama pengantin, tanggal pernikahan, dan nama tamu (dari URL parameter). Tamu menekan tombol "Open Invitation" untuk masuk ke undangan. Musik otomatis diputar saat amplop dibuka.

### 3. Guest Name Personalization
Nama tamu ditampilkan secara personal pada amplop pembuka. Diambil dari URL parameter `?to=`, `?guest=`, atau `?name=`. Default: "Honored Guest".

### 4. Cover / Hero Section
Halaman utama dengan foto pasangan, nama pengantin dalam efek shimmer gold, tanggal & lokasi pernikahan, serta dekorasi sudut botanical.

### 5. Bible Verses (Ayat Alkitab)
Menampilkan dua ayat Alkitab yang relevan dengan pernikahan Kristen:
- Kolose 3:14 — tentang kasih yang mempersatukan
- Markus 10:9 — tentang ikatan pernikahan yang kudus

### 6. Couple Profile (Profil Pengantin)
Profil pengantin pria & wanita dengan foto asli, nama lengkap, nama orang tua, dan link media sosial (Instagram & Facebook). Animasi masuk dari kiri dan kanan.

### 7. Countdown Timer
Hitung mundur real-time menuju hari pernikahan (14 Februari 2026) yang menampilkan hari, jam, menit, dan detik. Dilengkapi tombol **Add to Google Calendar** untuk menyimpan jadwal.

### 8. Wedding Events (Jadwal Acara)
Dua acara utama dengan detail lengkap:
- **Holy Matrimony** — Pemberkatan nikah di gereja (10:00 AM – 12:00 PM)
- **Wedding Reception** — Resepsi di ballroom (1:00 PM – 5:00 PM)

Masing-masing dilengkapi alamat, waktu, dan tombol **Google Maps** terpisah.

### 9. Dress Code & Protocol
Informasi dresscode (Semi-Formal) dengan palet warna yang direkomendasikan (Black, Navy, Sage, Blush, Champagne). Tiga kartu protokol: datang 30 menit lebih awal, unplugged ceremony, dan by invitation only.

### 10. Wedding Party (Pengiring Pengantin)
Menampilkan 3 Groomsmen dan 3 Bridesmaids dengan foto avatar, nama, dan peran (Best Man, Maid of Honor, dll).

### 11. Photo Gallery dengan Lightbox
Grid galeri 6 foto dengan layout featured (foto pertama full-width). Klik foto untuk membuka lightbox fullscreen dengan navigasi prev/next dan keyboard support (Arrow Keys + Escape).

### 12. Love Story Timeline
Timeline perjalanan cinta dari 2019 hingga 2026 dengan 6 milestone: First Meeting, Building Friendship, Falling in Love, Growing Together, The Proposal, dan The Wedding.

### 13. Live Streaming
Section untuk tamu yang tidak bisa hadir secara langsung. Menampilkan background foto dengan overlay gelap, indikator live, jadwal ceremony, dan tombol **Watch on YouTube**.

### 14. RSVP Form
Formulir konfirmasi kehadiran dengan field:
- Nama lengkap, email, nomor telepon
- Jumlah tamu (1–5)
- Pilihan kehadiran: "Joyfully Accept" atau "Regretfully Decline"
- Pesan & doa untuk pengantin

Setelah submit, ucapan otomatis muncul di Guest Wishes.

### 15. Guest List — Keluarga Pria & Wanita
Daftar undangan keluarga dengan tab switcher:
- **Groom's Family** (The Mitchell Family) — 15 nama kepala keluarga
- **Bride's Family** (The Anderson Family) — 15 nama kepala keluarga

Setiap nama dilengkapi relasi (Father, Mother, Uncle & Aunt, Grandparents, Cousin, Family Friend). Daftar bisa di-scroll.

### 16. Guest Wishes (Ucapan Tamu)
Dinding ucapan yang menampilkan pesan & doa dari tamu. Ucapan baru dari RSVP otomatis ditambahkan ke daftar secara real-time.

### 17. Gift Registry (Amplop Digital)
Tiga opsi pemberian hadiah dalam accordion yang bisa dibuka/tutup:
- **Chase Bank** — nomor rekening + routing number
- **PayPal** — alamat email
- **Venmo** — username

Setiap opsi dilengkapi tombol **copy to clipboard**. Tersedia juga alamat pengiriman hadiah fisik.

### 18. Share Invitation
Tiga cara membagikan undangan:
- **WhatsApp** — membuka WhatsApp dengan pesan yang sudah diformat
- **Copy Link** — menyalin URL undangan ke clipboard
- **Email** — membuka email client dengan subject dan body yang sudah diisi

### 19. Background Music
Musik latar yang otomatis diputar saat amplop dibuka. Tombol musik (play/pause) mengambang di kanan bawah, di atas navigasi, agar tidak tertutup.

### 20. Bottom Navigation
Navigasi fixed di bagian bawah layar dengan 6 menu: Home, Couple, Events, Gallery, RSVP, Gift. Muncul otomatis setelah scroll melewati cover section.

### 21. Scroll Animations (AOS)
Semua section menggunakan animasi masuk saat di-scroll: fade-up, fade-right, fade-left, zoom-in. Menggunakan library AOS (Animate On Scroll) dengan durasi 800ms.

### 22. Footer & Closing
Penutup dengan ayat 1 Korintus 13:4-8 (Love is patient, love is kind...), hashtag pernikahan **#JonathanAndElizabeth**, link media sosial, dan kredit.

---

## 🛠 Tech Stack

- **HTML5** — single file, tanpa framework
- **Tailwind CSS** (CDN) — utility-first styling
- **Alpine.js** (CDN) — reactivity & interactivity
- **Alpine Collapse Plugin** — animasi accordion
- **AOS** (CDN) — scroll animations
- **Google Fonts** — Cormorant Garamond, EB Garamond, Montserrat
- **DiceBear API** — avatar placeholder untuk wedding party

## 📁 Struktur File

```
202-undangan-digital/
├── index.html              # File utama undangan
├── README.md               # Dokumentasi
└── images/
    ├── pengantin-pasangan.png
    ├── pengantin-pria.png
    ├── pengantin-wanita.png
    ├── Church Retreat Together.png
    ├── Christmas at the Mitchells.png
    ├── Fall Adventures.png
    ├── The Proposal.png
    └── Engagement Photos.png
```

## 📝 Kustomisasi

Semua data (nama, tanggal, lokasi, daftar tamu, rekening, dll) dapat diubah langsung di bagian `<script>` pada fungsi `wedding()` di dalam `index.html`.

---

> Made with ♥ · All Glory to God
