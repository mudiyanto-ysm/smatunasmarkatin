# SMA Tunas Markatin

Website SMA Tunas Markatin, Pulo Gadung, Jakarta Timur.
Terarah · Dewasa · Mandiri · Beradab — siap kuliah, siap kerja, siap berwirausaha.

## Panduan SPMB 2027/2028 (untuk admin)

Semua jadwal, biaya, dan video diatur di satu tempat: blok `const SPMB={...}` di bagian atas skrip `index.html`. Ubah lewat editor web GitHub (ikon pensil), lalu tekan **Commit changes**. Situs akan diperbarui sendiri dalam 1–2 menit.

- **Gelombang** (`gelombang`): tanggal mulai dan akhir. Pita pengumuman di bagian atas, tombol di bagian utama, dan hitung mundur menyesuaikan tanggal hari ini secara otomatis.
- **Biaya** (`biaya`): biarkan `null` sampai yayasan mengesahkan harga. Selama `null`, situs menampilkan tombol "Tanyakan via WhatsApp". Setelah disahkan, isi tabelnya sesuai contoh di komentar.
- **Acara** (`acara`): Open House, Pesantren Kilat, Sehari Jadi Murid, Demo Day, dan Posko. Acara yang sudah lewat otomatis diberi tanda "Sudah berlangsung".
- **Video** (`video`): tambahkan tautan YouTube atau Instagram testimoni yang sudah mendapat izin tertulis. Bagian "Cerita dari Markatin" baru muncul jika daftar ini berisi.

### Tautan pelacak sumber pendaftar

Tambahkan `?ref=KODE` di akhir alamat situs. Kode ini ikut terkirim dalam pesan WhatsApp, sehingga panitia tahu pendaftar datang dari sumber mana.

| Untuk | Contoh tautan |
| --- | --- |
| Duta siswa D07 | `https://mudiyanto-ysm.github.io/smatunasmarkatin/?ref=D07` |
| Roadshow SMPN 92 | `https://mudiyanto-ysm.github.io/smatunasmarkatin/?ref=SMPN92` |
| Masjid / RW | `https://mudiyanto-ysm.github.io/smatunasmarkatin/?ref=RW05` |
| Instagram | `https://mudiyanto-ysm.github.io/smatunasmarkatin/?ref=IG` |

Aturan kode:
- Kode yang diawali `D` otomatis memilih sumber "Teman / Duta siswa".
- Kode yang diawali `SMP` atau `MTS` otomatis memilih sumber "Presentasi di SMP".

Ubah tiap tautan menjadi QR, lalu cetak di brosur roadshow dan kartu Duta.
