# ARTISYS — System Management & Asset Tracking

**ARTISYS** (Asset Recovery Tracking Integrated System) adalah sistem manajemen internal yang dikembangkan untuk **Divisi Aset dan Pemulihan, Kejaksaan Tinggi Lampung**. Aplikasi ini dirancang untuk mempermudah pengelolaan, pemantauan, dan *routing* berkas perkara serta pencatatan barang bukti/sitaan secara terintegrasi dan presisi per item.

---

## 🔑 Fitur Utama

- **Management & Routing Akses Perkara**: Pengaturan alur kerja dan proteksi berkas perkara sesuai kewenangan.
- **Item-Level Asset Tracking**: Pencatatan barang bukti/sitaan secara mendetail per individu barang.
- **Automated QR Code Generator**: Pembuatan kode QR otomatis untuk kemudahan pencatatan, tagging, dan verifikasi fisik barang rampasan.
- **Excel Report Exporter**: Fitur cetak/ekspor rekapitulasi data barang rampasan ke format `.xlsx`.
- **Role-Based Access Control (RBAC)**: Proteksi multi-level pengguna (Superadmin, Admin, User) menggunakan kustom *middleware* (`roleAccess`).
- **API Integration & Sanctum Auth**: Antarmuka API yang aman menggunakan Laravel Sanctum.

---

## 🛠️ Tech Stack

- **Back-End**: PHP 8.2, Laravel 12 Framework
- **Front-End**: Laravel Blade, Tailwind CSS v4, Axios
- **Build Tool**: Vite 6
- **Database**: MySQL
- **Libraries**:
  - `maatwebsite/excel` — Ekspor & impor laporan Excel
  - `simplesoftwareio/simple-qrcode` — Penjana kode QR
  - `laravel/sanctum` — Autentikasi API
- **Deployment**: Vercel / Web Server
