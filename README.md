# GEO-LINK — Platform Simulasi Panas Bumi Terintegrasi

**GEO-LINK** (*Geothermal Energy Optimization and Local Integration Network*) adalah platform simulasi interaktif berbasis peramban (10 modul terintegrasi) untuk pemodelan terpadu **Simulasi Alur 3D WebGL**, pembangkitan listrik **Organic Rankine Cycle (ORC)**, pemanfaatan panas bertingkat (**Heat Cascade**), evaluasi ekonomi arus kas 25 tahun, simulasi ketidakpastian **Monte Carlo**, matriks risiko, telemetri pemantauan air, dan analisis **peta spasial** untuk studi kasus panas bumi Ungaran.

## Fitur Utama

- **Beranda Dasbor Interaktif**: Lanskap panas bumi animatif, meteran kriteria rekomendasi 40 segmen, kartu ringkasan Bento, dan pita profil penurunan suhu brine.
- **Simulasi Alur 3D (`simulasi-3d.html`)**: Visualisasi 3D WebGL interaktif dari sumur produksi, separator V-101, PLTP flash & ORC penutup, pemanfaatan bertingkat 3 tahap (140 → 60 °C), penampang lapisan bawah tanah, dan sumur reinjeksi—lengkap dengan tur kamera otomatis 75 detik, mode tembus pandang (X-Ray), sinkronisasi parameter dari Simulator ORC, gestur sentuh/cubit (pinch-zoom), serta layar penuh untuk perangkat seluler.
- **Spasial (Peta Interaktif)**: Pemilihan tapak kandidat secara interaktif, zonasi termal 2 cincin, pemeriksaan zona penyangga 2 km cagar budaya Candi Gedong Songo, serta jarak otomatis ke kelompok tani kopi dan sentra hortikultura.
- **Mesin Skenario ORC**: Skema SVG interaktif dengan rotor turbin dinamis, 4 preset skenario (`Skenario A 20 MW`, `Skenario B 10 MW`, `RUPTL 55 MW`, `Replikasi WKP 15 MW`), serta slider suhu dan debit waktu nyata.
- **Neraca Panas Bertingkat (*Heat Cascade*)**: Profil suhu 3 tahap (gula aren & teh, ruang dingin absorpsi, pengeringan kopi) beserta batas aman *scaling* silika.
- **Penapisan Keekonomian & Skenario**: Kurva arus kas kumulatif 25 tahun dengan titik impas, sensitivitas tambahan daya ORC terhadap NPV, serta komparasi otomatis skenario S0–S3.
- **Rekomendasi, Risiko & Komunitas**: Evaluasi berbasis ambang batas transparan (siap cetak PDF), simulasi Monte Carlo hingga 50.000 iterasi, diagram tornado, matriks risiko 5×5, analisis manfaat petani/BUMDes, dan catatan telemetri mata air warga.

## Cara Menggunakan

Buka langsung melalui tautan **GitHub Pages** repositori ini, atau jalankan berkas `index.html` secara lokal di peramban modern (Chrome, Edge, Firefox, Safari) tanpa memerlukan instalasi server atau login.

> **Catatan:** Seluruh angka teknis dan ekonomi pada platform ini merupakan skenario simulasi ilustratif untuk penapisan awal dan tidak dimaksudkan sebagai studi kelayakan final.
