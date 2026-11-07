# Penguatan EWS MyIntress Berbasis Risiko

**Prototipe pendukung peran KPPN sebagai Financial Advisor dalam pembinaan satker**

Repositori ini memuat simulator antarmuka MyIntress untuk menggambarkan penyajian informasi risiko, penentuan prioritas, dan pengaturan notifikasi bagi Kepala KPPN. Ilustrasi penerapan menggunakan wilayah kerja **KPPN Mamuju**.

Penguatan EWS diarahkan agar pimpinan dapat mengetahui satker yang memerlukan perhatian, memahami alasan prioritasnya, dan menentukan kebutuhan verifikasi serta pembinaan. Alur yang diperagakan mencakup **deteksi → verifikasi → prioritas → penugasan → pendampingan → validasi penyelesaian**.

[**Buka simulator**](https://cakgup.github.io/ewsmyintress/)

## 1. Tujuan dan ruang lingkup

Simulator dikembangkan sebagai bahan pembahasan rancangan penguatan Early Warning System (EWS) MyIntress dalam mendukung peran KPPN sebagai Financial Advisor. Pengguna dapat menelusuri ringkasan risiko, membandingkan kondisi satker, dan mencoba pilihan kanal notifikasi.

Nama dan kode satker pada daftar mengikuti bahan referensi yang digunakan dalam pengembangan. Nilai anggaran, proyeksi, kondisi risiko, serta alasan prioritas pada kartu merupakan **data dan skenario ilustratif**. Penggunaan operasional memerlukan validasi data, metode perhitungan, kriteria prioritas, dan kewenangan penerima oleh pemilik proses bisnis.

## 2. Fitur simulator

| Komponen | Fungsi yang dapat dicoba |
| --- | --- |
| Ringkasan EWS | Menampilkan jumlah satker yang dipantau dan akses langsung ke panel analisis. Banner dapat ditutup, sedangkan panel tetap dapat dibuka melalui lonceng di header. |
| Analisis satker | Menyajikan tab Prediksi Penyerapan, Deviasi Hal III, dan Prediksi IKPA, masing-masing dengan enam kartu contoh. |
| Milestone FA | Memperlihatkan contoh risiko keterlambatan belanja modal, ketidakseimbangan belanja dan output, serta keterlambatan program prioritas. |
| Filter satker | Memuat 24 satker KPPN Mamuju yang dikelompokkan menurut bidang layanan. Filter tersedia pada panel EWS dan To-Do List. |
| Pengaturan notifikasi | Menyediakan sakelar MyIntress, email kedinasan, dan WhatsApp, beserta kolom alamat email dan nomor tujuan. |
| General Ledger | Menyajikan ringkasan total pagu, realisasi belanja, sisa pagu, dan proporsinya. |
| Kalender dan jam | Menampilkan tanggal serta jam hingga detik dalam zona waktu Asia/Jakarta (WIB). |
| To-Do List | Memisahkan Non-Pelaporan dan Pelaporan, dengan pilihan periode pelaporan serta ringkasan Aset Tetap dan Persediaan. |
| Grafik dasbor | Menampilkan Capaian IKPA, Pagu vs Realisasi, komposisi pengeluaran, serta SP2D Berhasil dan Void. Legenda grafik komposisi dapat dipilih untuk melihat persentase kategori. |
| Revisi DIPA | Menyediakan tab Proses, Berhasil, dan Ditolak, pencarian, serta daftar contoh yang dapat digulir. |
| Navigasi | Memuat 12 kategori menu dengan 93 submenu dan pencarian berdasarkan nama kategori atau submenu. Tematik memiliki keterangan saat submenu belum tersedia. |

## 3. Indikator yang diperagakan

Kode FA merupakan identitas rancangan kajian. Simulator saat ini memperagakan enam dari delapan kandidat indikator.

| Kode | Indikator | Lokasi tampilan | Arah pembinaan |
| --- | --- | --- | --- |
| FA-01 | Deviasi Halaman III DIPA | Tab Deviasi Hal III | Klarifikasi jadwal kegiatan, rencana penarikan dana, dan penyebab deviasi. |
| FA-02 | Prediksi Penyerapan Anggaran | Tab Prediksi Penyerapan | Pendalaman hambatan pelaksanaan kegiatan, pengadaan, dan kesiapan pembayaran. |
| FA-04 | Keterlambatan Belanja Modal | Milestone FA | Klarifikasi progres pekerjaan serta rencana pemulihan bersama KPA atau PPK. |
| FA-05 | Ketidakseimbangan Belanja dan Output | Milestone FA | Verifikasi perkembangan output dan kesesuaiannya dengan realisasi belanja. |
| FA-06 | Keterlambatan Program Prioritas | Milestone FA | Koordinasi penanganan hambatan berdasarkan milestone dan kewenangan pengampu. |
| FA-08 | Prediksi Penurunan Kinerja IKPA | Tab Prediksi IKPA | Penelaahan komponen penyumbang perubahan proksi kinerja. |

FA-03 mengenai penumpukan belanja akhir tahun dan FA-07 mengenai risiko tidak tercapainya PNBP berada dalam portofolio pengembangan berikutnya. Tampilan Prediksi IKPA menggunakan proksi ilustratif yang perlu dibaca bersama sumber penilaian resmi.

## 4. Kategori prioritas

Kategori mengikuti rancangan prioritas pada Tabel 3.7 dalam makalah penguatan EWS. Setiap kartu memuat alasan prioritas agar pengguna dapat memahami konteks dan tindakan yang perlu dipertimbangkan.

| Prioritas | Pertimbangan dalam skenario | Bentuk tindak lanjut |
| --- | --- | --- |
| **Kritis** | Kondisi signifikan yang, setelah verifikasi, memerlukan keputusan segera. | Verifikasi segera dan pemberitahuan kepada pejabat berwenang. |
| **Tinggi** | Tenggat mendekat atau kejadian berulang dengan konsekuensi relevan. | Penetapan prioritas dan pembinaan terarah. |
| **Sedang** | Perlu tindak lanjut dengan waktu penyelesaian yang masih memadai. | Monitoring dan pengingat berkala. |
| **Pemantauan rutin** | Kondisi cukup dipantau melalui prosedur dan rekap periodik. | Pengawasan rutin sesuai kewenangan. |

Klasifikasi pada 21 kartu ditetapkan berdasarkan skenario ilustratif. Penetapan prioritas mempertimbangkan kedekatan tenggat, konsekuensi, pengulangan, serta kebutuhan keputusan. Ambang numerik, aturan pengecualian, dan hasil klasifikasi masih memerlukan validasi pemilik proses bisnis.

## 5. Cara mencoba

1. Buka simulator dan temukan banner **EWS FA — KPPN Mamuju**.
2. Pilih **Buka EWS** atau ketuk lonceng pada header.
3. Telusuri tab **Prediksi Penyerapan**, **Deviasi Hal III**, dan **Prediksi IKPA**. Gulir daftar untuk melihat kartu satker berikutnya.
4. Gunakan **Filter Satker** untuk menampilkan kasus tertentu. Pilih **Semua Satker** untuk memulihkan daftar.
5. Pilih **Milestone FA** untuk melihat risiko kontrak, output, dan program prioritas. Gunakan **Kembali ke Analisis** untuk membuka tab sebelumnya.
6. Tutup panel, lalu buka profil di kanan atas untuk mengatur kanal notifikasi.
7. Aktifkan kanal yang diinginkan, isi alamat email atau nomor WhatsApp jika diperlukan, lalu pilih **Simpan Pengaturan**.

Pilihan satker yang belum memiliki kasus pada tampilan aktif akan menampilkan pesan ketersediaan data. Tombol Reset pada filter To-Do List mengembalikan cakupan ke semua satker.

## 6. Pengaturan notifikasi

Preferensi kanal disimpan melalui `localStorage` pada browser dengan kunci `myintress.ews.notifications`. Pengaturan akan dimuat kembali ketika simulator dibuka pada browser dan asal situs yang sama.

Email menggunakan validasi format alamat. Nomor WhatsApp menerima 8–15 angka tanpa spasi, dengan awalan `+` sebagai pilihan. Alamat email dan nomor yang diisikan turut tersimpan dalam preferensi, sehingga demonstrasi sebaiknya menggunakan data contoh.

Pengiriman notifikasi otomatis memerlukan integrasi layanan, identitas kedinasan, serta pengaturan akses berdasarkan jabatan dan wilayah kewenangan. WhatsApp resmi ditempatkan sebagai opsi pengembangan yang memerlukan penilaian keamanan informasi, perlindungan data, dan tata kelola.

## 7. Tampilan perangkat

Antarmuka menyesuaikan lebar dan orientasi layar.

- **HP atau layar potret** menggunakan susunan kartu satu kolom dan navigasi melalui ikon pencarian.
- **Desktop lanskap** menggunakan header dengan pencarian, tahun anggaran, dan profil, diikuti menu horizontal. General Ledger membentang di bawah header, sedangkan kartu dan grafik disusun berdampingan.
- **Panel EWS** membatasi tinggi konten agar daftar dapat digulir dan tombol navigasi tetap terjangkau.

Tanggal dan jam mengikuti waktu perangkat yang ditampilkan dalam WIB. Tanggal pemutakhiran pada kartu data menunjukkan tanggal snapshot ilustratif masing-masing.

## 8. Menjalankan secara lokal

Buka `index.html` melalui browser. Untuk akses lokal yang konsisten melalui HTTP, jalankan perintah berikut dari direktori repositori apabila Python tersedia.

```powershell
python -m http.server 8000
```

Kemudian buka [simulator lokal](http://localhost:8000).

Halaman menggunakan HTML, CSS, dan JavaScript tanpa proses build. Tailwind CSS, Chart.js, Font Awesome, serta font dimuat dari layanan eksternal. Akses internet diperlukan untuk memuat seluruh gaya, ikon, dan grafik. Jika Chart.js gagal dimuat, interaksi EWS tetap dapat digunakan dan grafik SP2D memiliki tampilan cadangan berbasis CSS.

## 9. Berkas utama dan publikasi

| Berkas | Kegunaan |
| --- | --- |
| `index.html` | Antarmuka, data ilustratif, gaya, dan logika interaksi simulator. |
| `myintress-logo.svg` | Logo MyIntress yang digunakan pada header dan panel EWS. |
| `README.md` | Penjelasan ruang lingkup, penggunaan, dan pemeliharaan. |
| `LICENSE` | Ketentuan lisensi kode. |

Publikasi GitHub Pages menggunakan berkas statis pada akar repositori. Pastikan `index.html` dan `myintress-logo.svg` tersedia pada cabang serta direktori yang dipilih sebagai sumber publikasi.

Saat memperbarui simulator, periksa konsistensi kode indikator, angka dan proporsi grafik, alasan prioritas, serta hasil filter. Uji kembali tampilan HP dan desktop, akses panel dari banner maupun lonceng, dan pemuatan preferensi notifikasi. Tangkapan layar serta video demonstrasi perlu diperbarui apabila antarmuka atau skenario berubah.

## 10. Pengembang dan lisensi

Dikembangkan oleh **Mukh. Gufron Ikhsan** sebagai visualisasi rancangan penguatan EWS MyIntress dalam mendukung peran KPPN sebagai Financial Advisor.

Kode proyek menggunakan lisensi [MIT](LICENSE).
