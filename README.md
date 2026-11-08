# Paket Claude Code — Website Safari Holiday

Paket kerja ini menyiapkan Claude Code untuk membangun website bertahap dari demo dummy, staging, hingga go-live. Sumber faktualnya adalah **Formulir Data Website Safari Holiday.docx.pdf** yang dibagikan dalam percakapan. Informasi yang belum dibuktikan atau disetujui ditandai `[GAP]`, `[VERIFIKASI]`, atau `[PERSETUJUAN]`.

## Isi paket

- `.claude/skills/safari-holiday-website/SKILL.md` — skill proyek untuk Claude Code.
- `prompts/master-prompt.md` — prompt awal untuk ditempel di Claude Code.
- `prompts/phase-prompts.md` — prompt terpisah untuk fase dummy, staging, dan go-live.
- `panduan-pengisian.md` — panduan mengisi formulir, status, bukti, dan keputusan.
- `checklist-qa-seo-cms-leads-security-deployment.md` — checklist persiapan rilis.
- `decision-log.md` — daftar fakta terverifikasi dan hal yang harus diputuskan.

## Cara memakai

1. Salin folder `.claude/skills/safari-holiday-website/` ke root repo website Anda. Claude Code biasanya memuat skill proyek dari `.claude/skills/`.
2. Isi formulir PDF sumber dan kumpulkan bukti di folder bersama. Jangan menaruh kredensial, data pelanggan, atau nomor kartu di repo.
3. Buka repo di Claude Code, tempel `prompts/master-prompt.md`, dan minta Claude memeriksa repo serta membuat **rencana dan demo dummy**. Tinjau perubahan sebelum lanjut.
4. Setelah data paket, konten, kontak, kebijakan privasi, domain, dan hosting diverifikasi, gunakan prompt fase staging.
5. Gunakan prompt go-live hanya setelah pemilik bisnis memberi persetujuan tertulis atas semua item rilis. Go-live mencakup tindakan publik, jadi lakukan langkah akhir dengan akses dan persetujuan operator yang berwenang.

Prompt tetap mewajibkan Claude Code memeriksa struktur proyek dan dokumentasi yang ada sebelum memilih stack. Tidak ada asumsi bahwa framework, CMS, vendor, domain, atau hosting sudah dipilih.

## Fakta yang sudah ada

Safari Holiday bergerak di leisure travel dan umrah; destinasi prioritas liburan China, Uni Emirat Arab, dan Turki. Situs direncanakan berbahasa Indonesia dengan keberangkatan dari Jakarta (CGK). Target tayang yang tercantum adalah 1 Januari 2027. Satu paket yang dicantumkan ialah Xinjiang 10D9N Maret/April, rute Urumqi–Turpan–Kashgar–Urumqi, target grup 25 pax, dengan tiket Air China, hotel bintang 4, shuttle bus, dan makanan halal sesuai itinerary.

Tanggal target bukan bukti bahwa kesiapan atau persetujuan go-live sudah terpenuhi. Lihat `decision-log.md` untuk gap dan pemeriksaan klaim.
