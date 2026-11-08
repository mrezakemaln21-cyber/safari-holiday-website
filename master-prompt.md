# Master prompt — proyek Website Safari Holiday

Anda bekerja di repo website Safari Holiday. Ikuti skill proyek `safari-holiday-website` di `.claude/skills/safari-holiday-website/SKILL.md` jika tersedia. Konteks dan daftar gap ada di paket ini (`decision-log.md`, `panduan-pengisian.md`).

## Tujuan

Bangun website berbahasa Indonesia untuk Safari Holiday secara bertahap dari demo dummy → staging → persiapan go-live. Situs membantu pengunjung memahami paket leisure travel dan layanan umrah, lalu menghubungi tim melalui kanal resmi. Buat pengalaman yang ramah seluler, mudah dipahami, aksesibel, cepat, mudah diperbarui, dan dapat dioptimalkan untuk pencarian.

## Fakta awal dari formulir

- Merek: Safari Holiday. Layanan: leisure travel dan umrah.
- Destinasi liburan prioritas: China, Uni Emirat Arab, Turki. Bahasa: Indonesia. Keberangkatan: Jakarta (CGK).
- Target tayang tertulis: 1 Januari 2027; ini target, bukan persetujuan rilis.
- WhatsApp: 085286276493. Email: safariholiday1@gmail.com. Alamat dan jam operasional tercantum dalam `decision-log.md`; verifikasi sebelum tayang.
- Paket tercatat: Xinjiang 10D9N Maret/April; rute Urumqi–Turpan–Kashgar–Urumqi; Jakarta (CGK); grup 25 pax; tercatat “status approve”. Air China, hotel bintang 4, shuttle bus, makanan halal sesuai itinerary. Itinerary tertaut di formulir, tetapi file/tautan dan detail hariannya perlu diverifikasi. Harga, tanggal pasti, ketersediaan, syarat lengkap, dan bukti izin belum terkonfirmasi.
- Tagline tercatat: “Jelajahi Dunia dengan Tenang, Shalat & Halal Terjamin”; gaya semi-formal. Klaim ini belum otomatis terbukti/disetujui untuk publikasi.

## Cara bekerja

1. Audit repo, instruksi lokal, stack, deployment, dan aset yang tersedia. Jangan mengasumsikan CMS, domain, hosting, desain, integrasi, atau database.
2. Rangkum temuan dan buat rencana singkat. Untuk pertanyaan yang tidak memblokir, lanjutkan dengan asumsi aman yang diberi label. Untuk keputusan yang mengubah arsitektur atau publikasi, sajikan pilihan dan minta keputusan.
3. Implementasikan hanya fase yang diminta. Jika belum ditentukan, mulai dengan audit dan demo dummy yang tidak menerima transaksi atau data pelanggan sungguhan.
4. Jangan mengarang fakta atau mengubah catatan mentah menjadi klaim. Tampilkan placeholder dengan penanda yang jelas dan daftar konten yang perlu disetujui.
5. Jangan melakukan tindakan publik/eksternal (deploy, DNS, kirim pesan, membuat akun, belanja, iklan/pixel, pembayaran) tanpa instruksi eksplisit untuk tindakan tersebut.
6. Laporkan perubahan, hasil pemeriksaan yang benar-benar dijalankan, gap yang masih menghalangi rilis, dan langkah berikutnya.

## Sasaran produk

Usulkan IA sederhana: Beranda, Destinasi, daftar dan detail paket, Tentang, FAQ, Kontak/WhatsApp, serta halaman privasi dan syarat yang hanya tayang setelah disetujui. Prioritaskan paket Xinjiang hanya sebagai draft sampai data lengkap. Sediakan pola konten terstruktur dan workflow review; rekomendasikan CMS setelah audit kebutuhan. Jangan tampilkan umrah sebagai penawaran aktif sebelum operator, peran merek, izin PPIU, dan paketnya diverifikasi.

WhatsApp boleh diarahkan ke nomor resmi dalam mode demo dengan pesan generik seperti “Halo Safari Holiday, saya ingin bertanya tentang paket perjalanan.” Form prospek produksi hanya boleh diaktifkan setelah persetujuan privasi lengkap; gunakan data minimum dan jelaskan tujuan. CRM/spreadsheet yang dicatat dalam formulir adalah referensi internal, bukan izin untuk mengekspos data.

## Kriteria penerimaan per fase

- Dummy: desain responsif dan konsisten; placeholder terlihat jelas; navigasi/CTA berfungsi; tidak ada formulir produksi, pembayaran, analitik/pixel, atau konten yang tampak sebagai penawaran aktual.
- Staging: data dan copy memiliki sumber/persetujuan; CMS dan peran diuji; formulir dan alur prospek diuji dengan data uji; privasi, SEO teknis, aksesibilitas, keamanan, performa dan backup ditinjau; staging tidak terindeks.
- Go-live: semua keputusan rilis ada bukti tertulis; domain/hosting, TLS, secrets, backup/rollback, redirect, sitemap, robots, monitoring, formulir/CRM, pemilik operasional dan smoke test terverifikasi. Tunggu instruksi operator sebelum tindakan publik.

Mulai dengan audit dan laporan status repo, lalu sarankan langkah konkret pertama. Jika pengguna meminta implementasi, kerjakan fase yang disebutkan dan gunakan skill.
