# HASA 🏥

HASA adalah aplikasi *mobile* berbasis **Flutter** yang dirancang untuk memudahkan manajemen data pasien, memantau *reward* (poin), serta menyediakan sistem notifikasi yang terintegrasi. Aplikasi ini dikembangkan untuk memberikan pengalaman yang efisien dan *user-friendly* dalam ekosistem kesehatan.

## 🚀 Fitur Utama

* **Sistem Autentikasi:** Dilengkapi dengan fitur Sign Up dan Sign In yang aman.
* **Manajemen Pasien:** Memudahkan pencatatan, pemantauan, dan pengelolaan data pasien.
* **Sistem Poin & Reward:** Fitur gamifikasi/insentif berupa poin yang terintegrasi dengan sistem penarikan (*withdrawal*).
* **Dashboard Interaktif:** Menyajikan ringkasan informasi penting secara cepat.
* **Notifikasi:** Pemberitahuan aktivitas atau pembaruan status langsung di dalam aplikasi.
* **Manajemen Profil:** Pengaturan akun pengguna secara personal.

## 🛠️ Tech Stack & Alat

* **Framework:** [Flutter](https://flutter.dev/)
* **Bahasa Pemrograman:** Dart
* **Arsitektur:** Pemisahan struktur yang jelas antara `models`, `pages` (UI), dan `services` (Logika Bisnis).
* **Manajemen Database:** Lokal/Service terintegrasi (`db_helper.dart`).

## 📂 Struktur Proyek

Kumpulan kode sumber utama berada di dalam folder `lib/` dengan pembagian sebagai berikut:

```text
lib/
├── models/       # Struktur data (Patient, Withdrawal, dll)
├── pages/        # Tampilan layar (Home, Dashboard, Patient, Reward, dll)
├── services/     # Logika bisnis dan pengelolaan data (Auth, Patient, Poin, Notifikasi)
└── main.dart     # Titik masuk (entry point) utama aplikasi
