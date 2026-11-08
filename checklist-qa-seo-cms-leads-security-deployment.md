# Checklist QA dan kesiapan rilis

Tandai `[ ]` belum, `[x]` selesai, `[N/A]` dengan alasan. Catat PIC, bukti, tanggal, dan blocker. Checklist ini tidak menggantikan pemeriksaan profesional atau persetujuan bisnis yang relevan.

## Konten dan persetujuan

- [ ] Nama/operator, badan hukum, alamat, kontak, jam, NIB/izin yang ditampilkan telah diverifikasi.
- [ ] Setiap paket memiliki itinerary, durasi, tanggal/tahun, harga/mata uang/masa berlaku, minimum peserta dan status ketersediaan yang disetujui.
- [ ] Penerbangan, akomodasi, makanan, visa, termasuk/tidak, perubahan, pembatalan, refund telah diselaraskan dengan penawaran final dan ditinjau Finance/manajemen.
- [ ] Durasi Xinjiang 10D9N versus dokumen 11D sudah diselesaikan.
- [ ] Klaim halal, waktu salat, visa, keamanan dan testimoni didukung bukti, disetujui, dan tidak menjanjikan di luar kendali operator.
- [ ] Umrah hanya ditampilkan sebagai layanan aktif bila operator, peran merek, izin PPIU dan produk sudah diverifikasi.
- [ ] Foto, logo, font, video, testimoni memiliki sumber dan izin penggunaan yang terdokumentasi.
- [ ] Setiap halaman/konten memiliki approver, tanggal, dan versi bukti.

## QA produk dan konten

- [ ] Beranda, destinasi, detail paket, tentang, FAQ, kontak, privasi dan syarat memiliki navigasi jelas.
- [ ] Tidak ada teks demo, `[GAP]`, konten lorem, tautan mati, atau data contoh yang tampak sebagai penawaran aktual.
- [ ] Harga, tanggal, mata uang, zona waktu, ejaan, CTA, nomor telepon dan alamat konsisten di semua halaman.
- [ ] Form error, sukses, validasi, label, keyboard, pembaca layar, spam dan batas input diperiksa.
- [ ] WhatsApp membuka nomor resmi yang telah dikonfirmasi dan pesan awal tidak membawa data sensitif.
- [ ] Pengalaman diuji di ponsel, tablet, desktop, beberapa browser, koneksi lambat dan kondisi gagal.
- [ ] Kontras, fokus keyboard, heading, alt text, label form dan ukuran target sentuh ditinjau.
- [ ] Tidak ada form produksi atau transaksi nyata di dummy.

## SEO

- [ ] Riset istilah dan tujuan pencarian disetujui; halaman tidak membuat klaim ranking.
- [ ] Judul/meta unik, canonical, URL manusiawi, heading semantik, Open Graph dan favicon.
- [ ] Sitemap XML hanya memuat URL kanonis yang layak indeks; robots.txt dan aturan noindex benar per lingkungan.
- [ ] Structured data hanya memuat data yang benar, tampak di halaman, dan sesuai jenis yang valid.
- [ ] Gambar dikompresi, ukuran/responsif dan alt text deskriptif; tidak menambahkan kata kunci berlebihan.
- [ ] Redirect dari URL lama dipetakan; 404 dan halaman error membantu pengguna.
- [ ] Google Search Console/alat webmaster dan analytics hanya dihubungkan dengan akun serta persetujuan yang benar.
- [ ] Staging tidak terindeks (auth/noindex dan proteksi yang sesuai); tidak mengandalkan robots.txt saja untuk informasi privat.

## CMS dan alur editorial

- [ ] CMS dipilih berdasarkan kebutuhan dan biaya yang disetujui; kepemilikan akun tetap perusahaan.
- [ ] Jenis konten destinasi/paket memiliki field terstruktur, validasi, status dan riwayat perubahan.
- [ ] Workflow draft → review → publish; harga, tanggal, syarat, privasi dan klaim perlu reviewer yang sesuai.
- [ ] Role mengikuti akses minimum; akun individual, MFA, pencabutan akses dan audit aktivitas tersedia.
- [ ] Preview aman; draf tidak bisa diakses publik; ada cara rollback konten.
- [ ] Pengelola, pelatihan, jadwal update paket dan PIC darurat ditetapkan.

## Prospek WhatsApp / CRM

- [ ] Nomor resmi, pesan awal, email penerima, PIC utama/pengganti dan jam layanan diuji.
- [ ] Data form minimal, tujuan jelas, notice privasi dan consent terpisah bila pemasaran digunakan.
- [ ] Respons sukses/gagal, anti-spam, validasi, rate limit dan proteksi abuse diuji.
- [ ] Prospek masuk ke akun/CRM yang disetujui dengan akses, retensi, ekspor, audit dan penghapusan yang jelas.
- [ ] SLA 1×24 jam kerja dapat dipenuhi; definisi hari kerja dan eskalasi disetujui.
- [ ] Data uji dihapus setelah QA; tidak ada data pelanggan di log, analitik, screenshot atau repo.
- [ ] Alur keluhan mencatat penerimaan, pemilik, eskalasi dan penyelesaian.

## Privasi dan keamanan

- [ ] Kebijakan privasi dan syarat telah disetujui dan cocok dengan proses nyata.
- [ ] PIC pengendali data, tujuan/dasar, penerima/vendor, retensi, penghapusan dan jalur permintaan ditetapkan.
- [ ] Inventaris data dan aliran data dibuat; pixel/analytics/CRM tidak aktif sebelum persetujuan.
- [ ] HTTPS/TLS, header keamanan, validasi server, sanitasi, proteksi CSRF/XSS/SQLi dan dependensi ditinjau.
- [ ] Rahasia hanya di secret manager; `.env` diabaikan; log tidak memuat rahasia/PII.
- [ ] MFA, least privilege, pembaruan dependensi, backup terenkripsi dan pemulihan diuji.
- [ ] Proteksi admin/CMS, rate limit, anti-bot, alerting dan respons insiden/PIC disiapkan.
- [ ] Tidak ada database staging/produksi terbuka atau akses default.

## Deployment dan operasi

- [ ] Domain dan akun registrar/hosting dimiliki perusahaan; akses PIC dan pemulihan akun diuji.
- [ ] Build produksi dapat direproduksi; konfigurasi environment diperiksa; tidak ada secret pada artefak.
- [ ] Backup sebelum rilis dan rollback ke versi sebelumnya telah diuji/tercatat.
- [ ] DNS, TLS, redirect HTTPS, domain kanonis, email/DMARC bila relevan diperiksa.
- [ ] Cache/CDN, error page, uptime/error monitoring, log dan notifikasi memiliki pemilik.
- [ ] Smoke test homepage, detail paket, CTA, form, email/CRM, analytics yang disetujui selesai.
- [ ] Sitemap/robots/canonical, noindex staging, redirect, favicon, metadata dan sosial diperiksa pada domain final.
- [ ] Rencana rilis, jendela, PIC, persetujuan tertulis, rollback dan komunikasi internal dicatat.
- [ ] Setelah rilis, ada pemilik pembaruan harga/jadwal dan pemeriksaan berkala.

## Gerbang persetujuan akhir

- [ ] Pak Kusuma Halim/penyetuju berwenang menyetujui versi konten dan daftar fitur yang akan tayang.
- [ ] Setiap paket/harga memiliki bukti persetujuan tersendiri.
- [ ] Form, privasi, CRM, pembayaran, umrah, analitik dan iklan disetujui atau tetap dinonaktifkan.
- [ ] Target tayang dan operator deployment dikonfirmasi.
- [ ] Operator memberi instruksi eksplisit untuk menjalankan deployment publik setelah meninjau rencana final.
