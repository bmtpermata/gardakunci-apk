# Cara Build APK GardaKunci Secara Online (Tanpa Instal Android Studio)

Proyek ini sudah dilengkapi folder **`android-native/`** (aplikasi Android Kotlin asli dengan `BiometricPrompt` sidik jari dan sandi pola SHA-256) serta workflow otomatis **`.github/workflows/build-apk.yml`** agar Anda bisa menghasilkan file `.apk` langsung di cloud secara gratis.

## Langkah-Langkah Build APK di GitHub Actions

1. **Unduh / Ekspor Proyek Ini**
   - Gunakan fitur unduh/ekspor proyek atau hubungkan repositori ini ke akun **GitHub** Anda.
2. **Unggah ke Repositori GitHub**
   - Buat repositori baru di GitHub (bisa Private atau Public), lalu unggah/push seluruh isi proyek ini termasuk folder `.github/` dan `android-native/`.
3. **Jalankan Build APK Online**
   - Buka tab **Actions** di repositori GitHub Anda.
   - Pilih workflow **`Build Android APK (GardaKunci)`**.
   - Jika belum berjalan otomatis setelah push, klik tombol **`Run workflow`**.
4. **Unduh File `.apk`**
   - Setelah status centang hijau selesai (sekitar 2–3 menit), buka hasil run workflow tersebut.
   - Gulir ke bagian **Artifacts** di bawah halaman dan klik **`GardaKunci-Android-APK`**.
   - Ekstrak file ZIP-nya dan instal **`app-debug.apk`** di HP Android Anda (izinkan *Instal aplikasi dari sumber tidak dikenal*).

## Catatan Penggunaan di HP Android
- Pola awal saat pertama kali dibuka adalah bentuk huruf **L** (titik 1-4-7-8-9) — segera ubah melalui tombol **Ubah Pola** di layar utama.
- Aktifkan **Izin Akses** (*Usage Access*) dan **Izin Tampil Atas** (*Display over other apps*) lalu tekan **Aktifkan Proteksi** agar GardaKunci dapat mengunci aplikasi lain secara nyata di HP Anda.
