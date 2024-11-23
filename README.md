# ci-cd-161-elektro

# CI/CD dengan GitHub Actions

## Deskripsi
Proyek ini menggunakan GitHub Actions untuk mengotomatiskan proses Continuous Integration (CI) dan Continuous Deployment (CD). Dengan menggunakan CI/CD, kita dapat memastikan bahwa setiap perubahan kode diuji dan diterapkan secara otomatis.

## Fitur
- **Automated Testing**: Menjalankan pengujian otomatis setiap kali ada perubahan pada repositori.
- **Deployment**: Mengotomatiskan proses penyebaran ke lingkungan produksi setelah pengujian berhasil.
- **Notifikasi**: Mengirimkan notifikasi tentang status build dan deployment.

## Struktur Proyek

.
├── .github
│   └── workflows
│       └── ci-cd.yml
└── tests
    └── app.test.js

