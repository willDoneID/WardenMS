# WardenMS
### Implementasi Server Minecraft Berbasis Rust dengan Bevy ECS

[![Language: Rust](https://img.shields.io/badge/Language-Rust-orange.svg?logo=rust)](https://www.rust-lang.org/)
[![License: MIT](https://img.shields.io/badge/Lisensi-MIT-yellow.svg)](LICENSE)
[![Owner: Wildan Erly](https://img.shields.io/badge/Owner-Wildan_Erly-emerald.svg)](https://github.com/willDoneID)

---

**WardenMS** adalah proyek pembuatan server custom Minecraft Java/Bedrock Edition dari nol menggunakan bahasa **Rust**. Dirancang dengan fokus pada efisiensi memori ekstrem, pemrosesan multi-core lockless menggunakan **Bevy ECS**, serta struktur arsitektur modular yang bersih.

---

## Latar Belakang & Visi Proyek
Terinspirasi dari performa tinggi server custom modern seperti FerrumC dan PumpkinMC, WardenMS dibangun untuk membuktikan bahwa server Minecraft dapat berjalan dengan konsumsi memori idle yang sangat minim serta memanfaatkan seluruh inti CPU (multi-core) secara optimal tanpa batasan overhead bahasa yang berat.

---

## Fitur Utama & Keunggulan
- **Ultra-Efficient ECS Memory:** Memanfaatkan Bevy ECS sebagai fondasi utama untuk manajemen komponen entitas yang terisolasi, cepat, dan ramah memori.
- **Async Multi-Core World Generation:** Memisahkan proses *world generation*, *lighting*, dan *network I/O* dari *main tick loop* utama agar server tidak mengalami lag atau *stuttering*.
- **Konfigurasi Vanilla:** Kompatibel penuh dengan file `server.properties` standar Minecraft untuk kemudahan pengaturan server.
- **Jaringan Asinkron:** Dibangun di atas *Tokio* untuk menangani ribuan koneksi TCP secara asinkron, aman, dan berkapasitas tinggi.
- **Format Modern 1.20.1:** Mendukung struktur *chunk* 1.18+ (Paletted Container), sinkronisasi registri data wajib, dan protokol status modern.

---

## Persyaratan Sistem & Instalasi
Pastikan Anda sudah menginstal (*Rust toolchain*)[(https://www.rust-lang.org/)] terbaru di komputer Anda.

1. Clone repositori ini melalui terminal:
   ```text
   git clone https://github.com/username-kamu/WardenMS.git
   cd WardenMS
   ```

3. Jalankan server dalam mode development:
   ```text
   cargo run --bin wardenms
   ```

---

## Kontribusi & Kolaborasi
Proyek ini dikembangkan secara mandiri dengan bantuan kecerdasan buatan(AI). Kontribusi, kritik, maupun saran sangat terbuka melalui Pull Requests atau Issues di GitHub!

---

## Lisensi
Proyek ini dilisensikan di bawah (MIT License)[LICENSE].
Copyright (c) 2026 Wildan Erly (Will Done Project).
