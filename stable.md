# 3.2.3

## Pembaruan ShiroA v3.2.3

- Penambahan sumber streaming anime built-in (ShiroA - OtakuDesu, ShiroA - Kuronime, ShiroA - Kuramanime, ShiroA - Samehadaku, ShiroA - Oploverz, ShiroA - NimeGami)
- Perbaikan menyeluruh resolver video streaming: integrasi native built-in parser untuk 6 sumber ShiroA (OtakuDesu, Kuronime AES v9, Kuramanime QuickJS leviathan auth, Samehadaku nonce AJAX, Oploverz Filedon/Upbolt, NimeGami Berkasdrive), injeksi header Referer otomatis, serta perbaikan OkHttpClient dan Cloudflare HTTP 200 challenge pada ExoPlayer
- Sistem Auto-Switch domain otomatis untuk melewati pemblokiran domain
- Integrasi proteksi Cloudflare dan header modern
- Pengaturan bahasa aplikasi mengikuti konfigurasi sistem Android serta dapat diubah manual di Common settings (`System Default`, `English`, `Indonesia`, `日本語`, `Русский`, `Español`, `中文`)
- Keamanan aplikasi: penghapusan dialog konfigurasi server/VPS & Discord webhook dari UI APK; laporan crash/kendala dirutekan aman melalui backend server
- Sistem moderasi komentar berhierarki & Developer Controls: identifikasi permanen akun Developer by AniList User ID, aksi Ban/Unban komentar & Ban/Unban pengguna (24 jam, 7 hari, 30 hari, permanen), panel Developer Controls, perbaikan sinkronisasi endpoint & penolakan host HTML 404/non-JSON, re-autentikasi otomatis saat moderasi, pemetaan pesan error multibahasa mengikuti bahasa sistem/aplikasi, serta penyempurnaan tata letak dialog moderasi
- Integrasi repository extension default yuzono anime-repo
- Perbaikan sistem komentar dan endpoint update resmi ShiroA-Nime
