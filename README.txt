PAKET INTEGRASI TAUTAN MUTABAAH — RakerGrupUPA

ISI PAKET
1. index.html — aplikasi utama yang ditambahkan panel tautan Firebase. Data JSONBin tetap dipakai.
2. Mutabaah-Binaan.html — form publik yang dibuka melalui tautan token unik tiap binaan.
3. Aturan-Firestore-Mutabaah-Publik.txt — aturan tambahan yang harus digabungkan dengan aturan Firestore yang sudah berjalan.

CARA MEMASANG
1. Cadangkan index.html lama dan simpan salinan aturan Firestore saat ini.
2. Salin isi index.html dari paket ke file index.html pada repositori GitHub 1650afr/RakerGrupUPA (jangan buat repositori aplikasi pengganti).
3. Unggah Mutabaah-Binaan.html ke folder yang sama dengan index.html pada repositori itu.
4. Gabungkan aturan dari Aturan-Firestore-Mutabaah-Publik.txt ke aturan yang sudah ada. Jangan mengganti seluruh rules. Audit aturan lama, lalu Publish.
5. Tunggu GitHub Pages selesai menerbitkan. Buka aplikasi utama, masuk menu Laporan Binaan Saya.
6. Masukkan email dan kata sandi akun admin Firebase dari proyek mutabaah-upa-test, tekan Masuk Firebase.
7. Pastikan daftar binaan tampil di aplikasi, lalu tekan Buat / Perbarui Tautan.
8. Uji satu tautan di browser/ponsel lain dan kirim satu catatan percobaan. Kembali ke aplikasi utama, tekan Ambil Kiriman Santri, lalu Masukkan ke Riwayat.

PENTING
- Jangan hapus atau menimpa konfigurasi JSONBin yang sudah ada. Panel ini hanya menambahkan koneksi Firebase untuk tautan/kiriman.
- File sudah diperiksa sintaks JavaScript-nya, tetapi belum bisa diuji langsung terhadap Firebase proyek Anda atau dipublikasikan ke GitHub dari sesi ini.
- Pengiriman publik tidak akan bekerja sebelum aturan Firestore yang sesuai digabungkan dan dipublikasikan.
- Pastikan akun admin Firebase yang dipakai memiliki dokumen upas/UPA_TEST_001/users/{uid} dengan role admin_upa atau admin dan aktif=true.
