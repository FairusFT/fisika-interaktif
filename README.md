# Fisika Interaktif — Dua Balok & Katrol

Simulasi fisika interaktif dalam **satu file HTML** (HTML + CSS + JS vanilla, tanpa framework, tanpa build step): balok di bidang miring terhubung tali melalui katrol dengan balok yang menggantung.

## Fitur
- **Mesin fisika benar**: gesek statis vs kinetis, deteksi kondisi diam/bergerak, tegangan tali, fixed timestep 1/120 s (stabil di layar 60Hz maupun 120Hz, anti jitter)
- **Parameter real-time**: m₁, m₂, sudut θ, μs, μk, dan gravitasi (Bumi / Bulan / Mars / Jupiter / kustom)
- **Interaksi langsung**: seret balok 1 sepanjang bidang miring, balok 2 naik-turun otomatis mengikuti tali, atau ubah sudut θ dengan menyeret titik sudutnya
- **Vektor gaya**: W, N, T, f, W sinθ, W cosθ — skala otomatis + nilai dalam newton
- **Panel Pembahasan** (update instan): status sistem, hukum Newton yang berlaku, rumus 3 langkah (umum → substitusi angka → hasil), mode Pemula/Lengkap, tabel ringkasan
- **5 preset skenario**: Seimbang, Balok 2 turun, Balok 1 turun, Tanpa gesek, dan gravitasi Bulan
- Optimasi: offscreen canvas untuk elemen statis, render hanya saat ada perubahan, ramah HP & laptop, dark mode otomatis

## Cara pakai
Buka `fisika-interaktif.html` langsung di browser — tidak butuh server. Tekan tombol `D` untuk menampilkan FPS.
