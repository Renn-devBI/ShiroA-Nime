# ShiroA シ

Aplikasi media agregator serbaguna untuk streaming Anime, membaca Manga dan Novel, pemutaran Torrent, serta interaksi komunitas dengan sistem pelaporan langsung dan pembaruan otomatis.

---

## Daftar Berkas Rilis

Paket APK terkompilasi tersedia berdasarkan arsitektur CPU perangkat:

- **ShiroA-arm64-v8a-release.apk**: Direkomendasikan untuk sebagian besar smartphone Android modern (64-bit).
- **ShiroA-armeabi-v7a-release.apk**: Untuk perangkat Android lama (32-bit).
- **ShiroA-x86_64-release.apk**: Untuk emulator Android 64-bit atau perangkat berbasis prosesor Intel/AMD.
- **ShiroA-x86-release.apk**: Untuk emulator Android 32-bit.

---

## Fitur Utama

1. **Pembaruan Otomatis Terintegrasi**
   Aplikasi secara otomatis mendeteksi rilis versi terbaru melalui repositori GitHub resmi ini dan menyediakan dialog pembaruan serta unduhan langsung di dalam aplikasi.

2. **Dukungan Multi-Media Lengkap**
   - **Anime**: Streaming resolusi tinggi dengan dukungan server internal, external resolvers, dan torrent client terintegrasi.
   - **Manga**: Reader dengan dukungan Webtoon, paginated mode, cache gambar berkecepatan tinggi, dan offline downloads.
   - **Novel**: Web scraper novel multifumber (Noveldex, dll.), parsing teks bersih tanpa entitas JSON/HTML bocor, pre-buffering 5 bab otomatis, dan Text-To-Speech (TTS) multibahasa yang sinkron dengan preferensi pengguna.

3. **Sinkronisasi Gateway & Failover Otomatis**
   Menggunakan arsitektur multi-gateway VPS (Port 2223 dan reverse proxy HTTPS) yang tahan gangguan. Jika domain utama bermasalah, aplikasi beralih secara dinamis ke gateway cadangan.

4. **Komunitas, Komentar & Forum Diskusi Pribadi**
   Dukungan sistem komentar terpusat dengan otentikasi AniList, thread balasan berjenjang, voting, dan notifikasi real-time.

5. **Live Broadcast Notice**
   Pemberitahuan darurat atau pemeliharaan server dapat disiarkan langsung oleh pengembang melalui bot Discord dan muncul seketika sebagai notifikasi heads-up di seluruh perangkat pengguna.

---

## Persyaratan Sistem

- Sistem Operasi: Android 8.0 (Oreo / API Level 26) atau versi lebih tinggi.
- Arsitektur CPU: ARMv8-A (64-bit), ARMv7-A (32-bit), x86, atau x86_64.
- Izin Penyimpanan: Diperlukan untuk menyimpan unduhan offline.
- Izin Notifikasi: Diperlukan untuk menerima Live Broadcast Notice dan status pengunduhan.

---

## Ketentuan Penggunaan

Penggunaan aplikasi ini tunduk pada ketentuan dan kebijakan yang tercantum pada dokumen [TERMS.md](TERMS.md).
