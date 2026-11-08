# Prompt fase dummy → staging → go-live

Jalankan satu fase per sesi. Sertakan konteks repo dan jawaban keputusan yang sudah disetujui. Jangan lanjut otomatis ke fase berikutnya.

## 1. Dummy / prototype

> Ikuti master prompt dan skill Safari Holiday. Kerjakan fase **dummy saja**. Audit repo dan instruksi lokal dahulu, lalu buat pengalaman website responsif berbahasa Indonesia dengan halaman Beranda, Destinasi, Detail Paket, Tentang, FAQ, dan Kontak. Gunakan fakta terverifikasi yang tersedia; tandai konten yang belum disetujui dengan `[DRAFT — PERLU VERIFIKASI]` atau `[DEMO — BUKAN PENAWARAN AKTUAL]`. Jangan tampilkan harga/tanggal/ketersediaan rekaan. Jangan aktifkan form produksi, pembayaran, analytics/pixel, atau integrasi yang mengirim data. Tautan WhatsApp boleh menggunakan pesan generik ke nomor resmi. Setelah implementasi, laporkan perubahan, cara menjalankan lokal, pemeriksaan yang dijalankan, gap, dan pilihan keputusan untuk staging.

## 2. Staging

> Ikuti master prompt dan skill. Kerjakan persiapan **staging**, bukan produksi. Konfirmasikan bahwa data konten dan bukti persetujuan tersedia. Siapkan lingkungan staging terpisah, cegah indeks mesin pencari, terapkan HTTPS dan rahasia melalui environment/secret manager, akses CMS sesuai peran, backup/restore, draft-review-publish, logging minimum, validasi formulir, anti-spam, dan integrasi CRM hanya sesuai vendor/akun yang telah diputuskan. Uji alur menggunakan data uji, bukan data pelanggan. Jalankan dan laporkan QA fungsional, responsif, aksesibilitas, SEO teknis, performa, keamanan aplikasi, dan privasi; jangan mengklaim lulus tanpa hasil. Jangan mengubah DNS publik atau menerbitkan situs produksi. Tutup dengan daftar blocker dan persetujuan go-live yang dibutuhkan.

## 3. Persiapan go-live

> Ikuti master prompt dan skill. Lakukan **persiapan rilis produksi** berdasarkan daftar persetujuan tertulis yang saya berikan. Verifikasi domain, hosting, TLS, secrets, hak CMS, backup dan uji restore, monitoring, robots/sitemap/canonical/redirect, metadata, formulir/WhatsApp/CRM, kebijakan privasi, izin media, klaim dan harga setiap paket. Buat checklist final, rencana deploy dan rollback, smoke-test, PIC dan langkah pascarilis. Laporkan blocker secara eksplisit. Jangan melakukan deploy, mengubah DNS, atau membuat perubahan publik sampai saya memberi instruksi eksplisit setelah meninjau rencana tindakan final.

## 4. Setelah deploy berizin

> Saya mengotorisasi tindakan deploy berikut: `[jelaskan lingkungan, versi/commit, domain, jendela waktu, dan pemilik akses]`. Jalankan hanya rencana yang telah disetujui. Catat tindakan, hasil tiap langkah, URL, smoke test, monitoring awal, dan cara rollback. Hentikan jika ada perbedaan pada domain, build, data, rahasia, atau status persetujuan dibandingkan rencana.
