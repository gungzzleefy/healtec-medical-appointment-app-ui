# Healtec — Medical Appointment App UI

> A modern, elegant, and cross-platform Medical Appointment Application UI built with Flutter. Designed to provide a seamless user experience for finding doctors and booking medical appointments.

---

## Table of Contents

- [English Version](#english-version)
  - [Overview](#overview)
  - [Features](#features)
  - [Application Flow](#application-flow)
  - [Tech Stack](#tech-stack)
  - [Project Structure](#project-structure)
  - [Getting Started](#getting-started)
- [Versi Indonesia](#versi-indonesia)
  - [Gambaran Umum](#gambaran-umum)
  - [Fitur Utama](#fitur-utama)
  - [Alur Aplikasi](#alur-aplikasi)
  - [Teknologi yang Digunakan](#teknologi-yang-digunakan)
  - [Struktur Proyek](#struktur-proyek)
  - [Cara Memulai](#cara-memulai)

---

## English Version

### Overview

**Healtec** is a beautifully designed UI template for a Healthcare and Medical Appointment application. Built entirely with Flutter, it showcases a clean, responsive, and intuitive interface suitable for modern medical services. The application utilizes **Flutter Riverpod** for lightweight state management (e.g., handling system UI overlays dynamically) and supports multiple platforms including Android, iOS, Windows, macOS, Linux, and Web.

### Features

- **Onboarding Experience:** Engaging initial screens to welcome and guide users.
- **Interactive Dashboard (Home Screen):** 
  - Personalized user greeting.
  - Dynamic search bar with custom styling.
  - Filter categories for quick navigation.
  - "Favourite Doctor" grid and "Top Doctor" list sections.
- **Detailed Doctor Profiles:** A dedicated interface to view doctor details, ratings, reviews, and clinic information.
- **Appointment Booking UI:** Clean layout for scheduling consultations.
- **Responsive Design:** Adapts smoothly across mobile devices and desktop windows.

### Application Flow

```text
App Launch
    └── Onboarding Screen (Welcome & Introduction)
            └── Home Screen (Dashboard)
                    ├── Top App Bar: User Profile & Notifications
                    ├── Search & Filter Widgets
                    ├── Favourite Doctors Grid View
                    └── Top Doctors List View
                            └── Appointment Detail Screen (Doctor Profile & Booking)
```

### Tech Stack

| Component | Technology |
|---|---|
| Framework | Flutter |
| State Management | Flutter Riverpod (`flutter_riverpod`) |
| Typography | Google Fonts (`google_fonts`) |
| Icons | Font Awesome (`font_awesome_flutter`) |

### Project Structure

```text
healtec-medical-appointment-app/
├── lib/
│   ├── main.dart                         # Entry point & System UI config
│   ├── screens/                          # Main Application Screens
│   │   ├── onboarding_screen.dart        # Welcome screen
│   │   ├── home_screen.dart              # Dashboard & Doctor listing
│   │   └── appointment_detail_screen.dart# Doctor detail & booking view
│   └── widgets/                          # Reusable UI Components
│       ├── favourite_doctor_widget.dart  # Grid item widget
│       ├── top_doctor_widget.dart        # List item widget
│       └── home_filter_widget.dart       # Category filter chips
├── assets/                               # Local images, icons, and textures
├── android/                              # Android native configurations
├── ios/                                  # iOS native configurations
└── windows/ linux/ macos/ web/           # Desktop & Web configurations
```

### Getting Started

#### Prerequisites
- Flutter SDK (latest stable version recommended)
- Dart SDK
- Android Studio / VS Code with Flutter extensions

#### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/healtec-medical-appointment-app-ui.git
   cd healtec-medical-appointment-app-ui
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   # Run on an active emulator or connected device
   flutter run
   ```

---

## Versi Indonesia

### Gambaran Umum

**Healtec** adalah template *User Interface* (UI) yang dirancang dengan indah untuk aplikasi Kesehatan dan Pemesanan Janji Temu Medis. Dibangun sepenuhnya menggunakan Flutter, aplikasi ini menampilkan antarmuka yang bersih, responsif, dan intuitif, sangat cocok untuk layanan medis modern. Aplikasi ini menggunakan **Flutter Riverpod** untuk manajemen *state* yang ringan (misalnya, menangani perubahan warna ikon *status bar* secara dinamis) dan mendukung berbagai platform termasuk Android, iOS, Windows, macOS, Linux, dan Web.

### Fitur Utama

- **Pengalaman Onboarding:** Layar perkenalan awal yang menarik untuk menyambut dan memandu pengguna.
- **Dashboard Interaktif (Beranda):**
  - Sapaan pengguna yang dipersonalisasi.
  - Bilah pencarian dinamis dengan gaya kustom.
  - Kategori filter untuk navigasi cepat.
  - Bagian *grid* "Dokter Favorit" (*Favourite Doctor*) dan daftar "Dokter Teratas" (*Top Doctor*).
- **Profil Dokter Detail:** Antarmuka khusus untuk melihat detail dokter, peringkat, ulasan, dan informasi klinik.
- **UI Pemesanan Janji Temu:** Tata letak yang rapi untuk menjadwalkan konsultasi medis.
- **Desain Responsif:** Menyesuaikan dengan mulus di berbagai perangkat seluler maupun jendela desktop.

### Alur Aplikasi

```text
Buka Aplikasi
    └── Layar Onboarding (Selamat Datang & Pengenalan)
            └── Layar Beranda (Dashboard)
                    ├── App Bar Atas: Profil Pengguna & Notifikasi
                    ├── Widget Pencarian & Filter
                    ├── Tampilan Grid Dokter Favorit
                    └── Tampilan Daftar Dokter Teratas
                            └── Layar Detail Janji Temu (Profil Dokter & Pemesanan)
```

### Teknologi yang Digunakan

| Komponen | Teknologi |
|---|---|
| Framework | Flutter |
| State Management | Flutter Riverpod (`flutter_riverpod`) |
| Tipografi | Google Fonts (`google_fonts`) |
| Ikon | Font Awesome (`font_awesome_flutter`) |

### Struktur Proyek

```text
healtec-medical-appointment-app/
├── lib/
│   ├── main.dart                         # Titik masuk & konfigurasi System UI
│   ├── screens/                          # Layar Aplikasi Utama
│   │   ├── onboarding_screen.dart        # Layar selamat datang
│   │   ├── home_screen.dart              # Beranda & Daftar dokter
│   │   └── appointment_detail_screen.dart# Tampilan detail & pemesanan
│   └── widgets/                          # Komponen UI yang dapat digunakan kembali
│       ├── favourite_doctor_widget.dart  # Widget item grid
│       ├── top_doctor_widget.dart        # Widget item daftar (list)
│       └── home_filter_widget.dart       # Chip filter kategori
├── assets/                               # Gambar, ikon, dan tekstur lokal
├── android/                              # Konfigurasi native Android
├── ios/                                  # Konfigurasi native iOS
└── windows/ linux/ macos/ web/           # Konfigurasi Desktop & Web
```

### Cara Memulai

#### Prasyarat
- Flutter SDK (disarankan versi stabil terbaru)
- Dart SDK
- Android Studio / VS Code dengan ekstensi Flutter

#### Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/your-username/healtec-medical-appointment-app-ui.git
   cd healtec-medical-appointment-app-ui
   ```

2. **Instal dependensi**
   ```bash
   flutter pub get
   ```

3. **Jalankan aplikasi**
   ```bash
   # Jalankan di emulator yang aktif atau perangkat fisik
   flutter run
   ```
