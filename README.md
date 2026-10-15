# Dashboard Pemetaan Intervensi Mitra · Konsorsium Nasional 1000 HPK

Dashboard statis interaktif, siap dipublikasikan menggunakan GitHub Pages. Tidak membutuhkan Superset atau server database.

## Publikasi GitHub Pages
1. Login ke GitHub dengan akun `yonamayrahayu`.
2. Buat repository publik bernama `konsorsium-1000hpk-dashboard`.
3. Upload `index.html` dan `data.json` ke root repository (README opsional).
4. Di **Settings → Pages**, pilih **Deploy from a branch**, branch **main**, folder **/(root)**, lalu **Save**.
5. Buka `https://yonamayrahayu.github.io/konsorsium-1000hpk-dashboard/` setelah deployment selesai.

## Catatan data
- Data utama diambil dari sheet `Summary` pada Excel yang diunggah.
- Dua paparan Tanoto Foundation dan ASRI ditambahkan sebagai empat entri pelengkap, dengan sumber jelas.
- Entri adalah baris ringkasan, bukan otomatis proyek unik. Data naratif dapat memuat lebih dari satu aktivitas.
- Detail dan stakeholder hanya ditampilkan bila tercantum dalam sumber. Data kosong tidak diimputasi.
- Hindari publikasi bila ada data yang belum mendapat izin untuk disebarkan secara publik. Jika data sensitif, gunakan repository/hosting privat dengan kontrol akses.
