# 🤝 Panduan Kontribusi WardenMS

Terima kasih atas ketertarikan Anda untuk berkontribusi pada **WardenMS**! Proyek ini adalah implementasi server Minecraft berbasis Rust dengan Bevy ECS. Kami menyambut baik segala bentuk kontribusi, baik itu laporan bug, perbaikan kode, maupun penambahan fitur.

## 🛠️ Aturan & Standar Pengembangan
1. **Bahasa Kode & Log:** Seluruh komentar kode (*inline comments*), pesan `tracing` log, dokumentasi, dan output terminal **wajib menggunakan Bahasa Indonesia**.
2. **Standar Rust:** Pastikan kode Anda bersih, mematuhi standar idiomatis Rust, dan lolos uji linter (`cargo fmt` dan `cargo clippy`).
3. **Struktur Workspace:** Pertahankan struktur monorepo di dalam direktori `crates/`.

## 🐛 Melaporkan Bug & Masalah
Jika Anda menemukan *bug*, *crash*, atau ketidaksesuaian protokol:
- Buka tab **Issues** di GitHub.
- Gunakan template *Bug Report* yang tersedia.
- Sertakan langkah-langkah reproduksi, log error lengkap, dan versi klien yang digunakan.

## 🔀 Alur Kerja Pull Request (PR)
1. *Fork* repositori ini dan buat *branch* baru (`git checkout -b fitur/nama-fitur`).
2. Tulis kode Anda dan pastikan uji coba lokal berhasil (`cargo run --bin wardenms`).
3. Buat *commit* dengan pesan yang deskriptif.
4. Kirim *Pull Request* ke branch utama dengan penjelasan ringkas mengenai perubahan yang Anda buat.
