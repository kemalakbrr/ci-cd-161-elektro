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

## Installation

To set up and run this project locally:

1. **Clone the repository**:
   
   git clone https://github.com/kemalakbrr/ci-cd-project.git
   
2. **Navigate Navigate to the project directory**

   cd ci-cd-project

3. **npm install**

   npm install
4. **Run the application**

   node app.js

5. **Run the tests**

    npm test

## GitHub Actions Workflows
CI Workflow (.github/workflows/ci.yml)
Triggers: Runs on every push or pull_request to the repository.
Steps:
1. Checkout the code.
2. Set up Node.js.
3. Install dependencies.
4. Run the tests.
CD Workflow (.github/workflows/cd.yml)
Triggers: Runs on successful completion of the CI workflow (or manual trigger).
Steps:
1. Build the application.
2. Deploy to the specified environment.

Technologies Used
1. Node.js: Runtime for the main application.
2. Jest: Testing framework for JavaScript.
3. GitHub Actions: Automates CI/CD pipelines.
   
