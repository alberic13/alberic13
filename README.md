<div align="center">

# 👋 Hi, I'm Muchammad Zalde Zahwa Putra
### **Frontend & Fullstack Software Engineer**
**Building high-performance, type-safe web applications with clean architecture and modern UX**

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1000&color=10B981&center=true&vCenter=true&width=580&lines=Frontend+Developer+(React+19+%2B+TypeScript);Fullstack+Developer+(Next.js+%2B+Go+%2B+Bun);Exploring+AI+%26+Vector+Search+(pgvector);Clean+Code+%2B+Modern+UI+%2B+Continuous+Learning)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/muchammad-zalde-zahwa-putra-20a83b2a7/">
    <img src="https://img.shields.io/badge/Status-Open_for_Opportunities-10B981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" />
  </a>
  <a href="mailto:zaldealberic@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/muchammad-zalde-zahwa-putra-20a83b2a7/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

</div>

---

### 🧑‍💻 About Me

Saya adalah seorang **Software Engineer** yang berfokus pada pengembangan antarmuka modern yang responsif serta sistem backend yang terstruktur dan andal. Selalu mengedepankan **clean architecture**, **type safety**, dan **validasi data defensif** untuk membangun produk yang mudah dirawat dalam jangka panjang:

- 🌐 **Frontend Development:** Mengembangkan SPA & SSR interaktif berperforma tinggi dengan React 19, Next.js (App Router), TypeScript, dan Tailwind CSS.
- ⚙️ **Backend Engineering:** Membangun RESTful API berlatensi rendah dengan Golang (Gin), Bun + Elysia.js, serta arsitektur MVC/Livewire dengan Laravel.
- 🗄️ **Database, Cache & AI:** Mendesain skema relasional (PostgreSQL, MySQL), caching memori (Upstash Redis), dan pencarian semantik AI menggunakan `pgvector`.
- 🧪 **Disiplin Kualitas (QA):** Menerapkan validasi skema ketat (Zod), typecheck statis (`tsc`), automated integration testing, serta E2E browser testing (Playwright).

---

### 🛠️ Core Competencies

| Bidang | Spesialisasi & Teknologi Utama |
| :--- | :--- |
| **Frontend Engineering** | React 19, Next.js 16 (App Router), TypeScript, Tailwind CSS v4, Vanilla CSS Modules, React Hook Form, Recharts, Three.js dasar |
| **Backend & Microservices** | Golang (Gin), Bun, Elysia.js, Laravel 11, Node.js, RESTful API Design, JWT Auth (Argon2id/Bcrypt), Zod Validation |
| **Database, Cache & AI** | PostgreSQL, MySQL, MariaDB, Upstash Redis (Caching & Rate Limiting), Prisma ORM, Drizzle ORM, pgvector (Semantic Search) |
| **Testing, CI/CD & DevOps** | Playwright (E2E Browser Testing), Bun Test Suite, GitHub Actions CI/CD Pipeline, Oxlint / ESLint, Vercel Serverless |

---

### 🌟 Featured Projects

Berikut adalah proyek-proyek terpilih yang mencerminkan kemampuan arsitektur, penyelesaian masalah bisnis, dan kedalaman teknis nyata:

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 01. [Todo List + AI RAG Suite](https://todo-list-zalde.vercel.app/)
**React 19 · TypeScript · Bun · Elysia.js · Upstash Redis · pgvector · Playwright**

Aplikasi task management dengan Kanban board terintegrasi pencarian semantik (RAG) dan sinkronisasi kalender live.
- **Arsitektur Modular Monorepo:** Terpisah antara frontend (`Vite + React 19`) dan backend (`Bun + Elysia.js`) dengan middleware otorisasi terpusat (`requireAuth`) pada 15+ endpoint.
- **Semantic Vector Search (RAG):** Integrasi `pgvector` & Google Gemini embedding (768-dim) untuk pencarian tugas kontekstual bahasa alami dan auto task breakdown.
- **In-Memory Caching & Rate Limiting:** Integrasi REST **Upstash Redis** untuk optimasi caching data dan perlindungan rate limiting pada endpoint AI.
- **Live Webcal Calendar (RFC 5545):** Sinkronisasi jadwal otomatis 2 arah ke Google Calendar, Apple Calendar, & Outlook dengan token reset keamanan.
- **Otomasi Cron & Email Notifikasi:** Background cron Vercel terproteksi `CRON_SECRET` untuk pengingat deadline H-3 dan tugas overdue via email HTML responsif.
- **Kolaborasi & Testing Teruji:** Real-time task sharing via invite code, 100% type-safe (`tsc`), unit test `bun test` (10/10), serta E2E browser testing dengan Playwright di GitHub Actions CI.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://todo-list-zalde.vercel.app/) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/todo-list-zalde)

</td>
<td width="50%" valign="top">

#### 💳 02. [POS Web Zalde](https://pos-web-zalde.vercel.app)
**React 18 · TypeScript · Tailwind CSS · Prisma ORM · Elysia API · PostgreSQL**

Sistem Point of Sale (POS) kasir dan manajemen inventaris multi-gudang siap pakai untuk operasional ritel.
- **Multi-Warehouse Stock Tracking:** Manajemen inventaris dual-stok (Stok Etalase toko vs Stok Cadangan Gudang), kalkulasi transaksi real-time, dan alert stok menipis (≤ 5 unit).
- **Otomasi Purchase Order (PO) Supplier:** Modul restock cerdas yang mengonversi kebutuhan pasokan ke format PO terstruktur dan mengirimkannya langsung ke WhatsApp vendor dalam 1 klik.
- **Kompresi Gambar WebP di Browser:** Utility client-side (`imageCompressor.ts`) yang otomatis me-resize & mengompres foto produk (JPG/PNG) menjadi WebP (15–30 KB) sebelum diunggah ke cloud.
- **Komunikasi Internal Toko:** Floating chat widget berbasis peran (Kasir Toko Depan & Tim Gudang) dengan template pesan cepat permintaan restok etalase.
- **Sinkronisasi Data Cloud & Testing:** Script sinkronisasi bi-directional database (`syncFromCloud`/`syncToCloud`) antara PostgreSQL lokal dan Neon Cloud, teruji via 7 test suite Bun Test.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://pos-web-zalde.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/pos-web-zalde)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏢 03. [CRM Web Platform](https://crm-web-zalde.vercel.app)
**Next.js 16 · React 19 · TypeScript · Zod · Prisma ORM · Neon PostgreSQL**

Platform CRM komprehensif untuk otomatisasi pipeline penjualan, direktori B2B, dan customer support ticketing.
- **Defensive API Validation:** Validasi skema runtime dan sanitasi input form secara ketat menggunakan **Zod** pada seluruh boundary API route handler, mencegah SQL injection bersama Prisma ORM.
- **Sales Deal Pipeline:** Manajemen opportunity penjualan multi-tahap (*Pending, Won, In Progress, Lost*) dengan tracking estimasi nilai closing dan histori interaksi tim sales.
- **Service Desk & SLA Countdown:** Sistem tiket pengaduan dengan severity (*Critical, Major, Minor*), timer countdown sisa SLA resolusi secara real-time, dan agregasi skor kepuasan pelanggan (CSAT review).
- **Knowledge Base Terintegrasi:** Pusat dokumentasi solusi internal berbasis Markdown dengan indexing kategori dan view counter untuk menekan tiket berulang.
- **Zero Lint & Type-Safe Architecture:** Next.js App Router dengan Server Components, Vanilla CSS Modules bebas konflik styling, dan 100% lolos verifikasi TypeScript (`tsc --noEmit`).

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://crm-web-zalde.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/CRM-web)

</td>
<td width="50%" valign="top">

#### 🏘️ 04. [System RT (Administrasi & Kas)](https://system-rt-zalde.vercel.app/)
**React 19 · Vite 8 · React Router v7 · Tailwind v4 · Recharts 3 · Oxlint**

Aplikasi web SPA manajemen administrasi kependudukan dan transparansi pembukuan kas warga RT.
- **Kependudukan & Audit Trail Hunian:** Manajemen data 20 unit rumah (Blok A & B), verifikasi KTP warga, status huni (Tetap vs Kontrak), dan log histori mutasi masuk/keluar otomatis (`RiwayatPenghuni`).
- **Logika Billing Iuran Fleksibel:** Penagihan iuran Satpam (Rp 100k) & Kebersihan (Rp 15k) bersyarat (hanya ditagih bila rumah kontrak berpenghuni), dengan opsi bayar bulanan atau 1 tahun lunas.
- **Buku Kas & Visualisasi Keuangan:** Pencatatan pengeluaran rutin (gaji satpam, listrik pos) dan insidental (perbaikan jalan) dengan grafik tren kas Recharts serta fitur cetak laporan keuangan.
- **Modern Tooling & Kualitas Kode:** Dibangun di atas Vite 8, React 19, React Router v7, styling Tailwind CSS v4, dan terverifikasi bersih menggunakan linter Rust performa tinggi **Oxlint** (0 errors, 92 rules) pada GitHub Actions CI.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://system-rt-zalde.vercel.app/) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/system-rt)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧠 05. [Personality & Career Assessment](https://personality-test-omega-three.vercel.app)
**Next.js 16 · React 19 · NextAuth v5 · React Hook Form · Zod · Dynamic SVG**

Platform asesmen psikometri interaktif multi-dimensi untuk pemetaan potensi diri, karir, dan gaya belajar.
- **Tiga Model Psikometri Terstandar:** Mengimplementasikan teori Kecerdasan Majemuk Howard Gardner (80 soal, 8 domain), Minat Karir RIASEC John Holland (42 soal, 6 tipe), dan Modalitas Belajar VAK (27 soal).
- **Dynamic Polar SVG Radar Chart:** Visualisasi skor psikometri dirender langsung menggunakan kalkulasi matematika polar SVG kustom (segitiga VAK, heksagon RIASEC, oktagon Gardner) tanpa dependensi chart berat.
- **Arsitektur Form Skala Besar:** Pengelolaan 80+ input pertanyaan menggunakan `react-hook-form` untuk performa render optimal tanpa lag, divalidasi ketat dengan skema `Zod`.
- **Integrasi Cloud & NextAuth v5:** Penyimpanan otomatis hasil tes pengguna ke database Google Sheets via API webhook, dilengkapi manajemen sesi autentikasi modern NextAuth v5 (Auth.js).

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://personality-test-omega-three.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/personality-test)

</td>
<td width="50%" valign="top">

#### 🏫 06. [Sistem Keuangan Sekolah (SPP)](https://github.com/alberic13/keuangan-app)
**Laravel 11 · Livewire 4 · MariaDB · Spatie Permission · DomPDF · Excel**

Sistem informasi tata kelola administrasi keuangan dan penagihan biaya pendidikan institusi madrasah.
- **Keamanan RBAC 5-Level:** Kontrol hak akses berbasis peran menggunakan `spatie/laravel-permission` memisahkan otorisasi: `admin_keuangan`, `bendahara`, `kepala_madrasah`, `waka`, dan `admin_tu`.
- **Billing SPP & Kebijakan Tunggakan:** Pengelolaan SPP reguler, dana kegiatan (Full Day), uang makan (Boarding), dengan pencatatan tunggakan tahun ajaran lalu sebagai invoice terbuka yang terstruktur.
- **Pelaporan & Cetak Dokumen Resmi:** Pembukuan Buku Kas Umum (BKU), cetak bukti kuitansi pembayaran format PDF via `laravel-dompdf`, dan ekspor rekapitulasi data keuangan ke Excel via `laravel-excel`.
- **Migrasi Data & Backup Cloud:** Dilengkapi command konsol khusus (`php artisan legacy:import-transaksi`) untuk migrasi skema database lama, serta integrasi backup file ke Google Drive Filesystem.
- **Antarmuka Reaktif Livewire:** UI dinamis tanpa reload halaman menggunakan komponen reaktif Livewire 4, didukung background queue worker untuk proses data intensif.

[![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/keuangan-app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ✨ 07. [LKP Exotic](https://belajar-nextjs-taupe.vercel.app)
**Next.js 16 · React 19 · Three.js · GSAP · Drizzle ORM · MySQL2 · Zod**

Web portal profil komersial lembaga kursus kecantikan dan fondasi sistem manajemen kursus (LMS).
- **Interaktivitas 3D WebGL (Three.js):** Viewport 3D interaktif kustom (`ThreeDSlider.js`) dan efek kursor yang dioptimasi untuk berjalan stabil di 60 FPS pada perangkat mobile maupun desktop.
- **Arsitektur Autentikasi Mandiri:** Sistem autentikasi stateless berbasis token JWT menggunakan library `jose` dan enkripsi `bcryptjs` yang berjalan aman melalui Next.js Server Actions dan secure cookie.
- **Type-Safe ORM & Skema Data:** Pengelolaan model data pendaftaran kursus menggunakan `Drizzle ORM` + driver `mysql2`, dengan validasi skema data defensif menggunakan `Zod`.
- **Koreografi Animasi Halus:** Transisi antar bagian halaman yang mulus menggunakan `@gsap/react` dan Framer Motion tanpa menyebabkan Cumulative Layout Shift (CLS: 0).

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://belajar-nextjs-taupe.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/LKP-EXOTIC)

</td>
<td width="50%" valign="top">

#### ⚡ 08. [WhatsApp Auto-Reply Bot](https://github.com/alberic13/whatsap-auto-reply-Golang)
**Golang 1.26 · Gin · Whatsmeow · Telegram API · Gemini AI SDK · GORM**

Service backend otomasi perpesanan berkecepatan tinggi dengan integrasi AI dan protokol multi-channel.
- **Konkurensi Tinggi & Efisiensi Memori:** Memanfaatkan Goroutine dan Go Channels untuk memproses lalu lintas pesan masuk secara paralel dengan latensi sangat rendah dan alokasi memori minimal.
- **Protokol Socket WhatsApp Murni:** Terhubung langsung ke level WebSocket protokol WhatsApp via `whatsmeow` (pairing QR terminal), tanpa membutuhkan browser headless (Puppeteer) yang berat.
- **Router Pesan Multi-Channel:** Arsitektur terpadu yang menjembatani event socket WhatsApp dan polling Telegram Bot API ke satu sistem pengendali terpusat.
- **Integrasi LLM & Pemesanan Katalog:** Terkoneksi ke SDK resmi `google-generative-ai-go` untuk respons percakapan cerdas, pencocokan kata kunci database untuk order katalog (`controllers/pesanan.go`), dan arsip dokumen ke Google Drive.
- **Monitoring Sensor & Alerting IoT:** Modul controller suhu (`controllers/suhu.go`) yang mampu menerima telemetri sensor dan memicu peringatan otomatis ke chat saat mendeteksi anomali.

[![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/whatsap-auto-reply-Golang)

</td>
</tr>
</table>

---

### 🎯 Nilai Tambah untuk Tim Engineering

- **Pragmatis & Berorientasi Solusi:** Memilih teknologi berdasarkan kebutuhan nyata sistem (misal: Go untuk concurrency bot socket, Next.js/React 19 untuk UI/SEO, Laravel untuk sistem finansial institusional ber-RBAC).
- **Disiplin Kode & Type Safety:** Menerapkan validasi data defensif (Zod), type safety (TypeScript/Go), dan automated testing (Playwright, Bun Test, Oxlint) untuk mencegah regresi bug di produksi.
- **Siap Kolaborasi & Adaptif:** Terbiasa dengan workflow Git standar (branching, commit terstruktur, pull request), pemisahan arsitektur modular, dan penulisan dokumentasi teknis yang komprehensif.

---

### 🛠️ Tech Stack & Tools

<div align="center">

| Kategori | Teknologi |
| :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Backend** | ![Golang](https://img.shields.io/badge/Golang-00ADD8?style=flat-square&logo=go&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) ![Elysia](https://img.shields.io/badge/ElysiaJS-8B5CF6?style=flat-square&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Database & Cache** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logoColor=black) |
| **Testing & Tools** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

</div>

---

### 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=alberic13&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alberic13&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=alberic13&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

### 📬 Get In Touch

Saya terbuka untuk peluang karier sebagai **Frontend Developer**, **Backend Engineer**, atau **Fullstack Software Engineer** (Full-time / Remote / Hybrid).

<div align="center">

<a href="https://www.linkedin.com/in/muchammad-zalde-zahwa-putra-20a83b2a7/">
  <img src="https://img.shields.io/badge/LinkedIn-Muchammad_Zalde-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="38" alt="LinkedIn" />
</a>
&nbsp;&nbsp;
<a href="mailto:zaldealberic@gmail.com?subject=Job%20Opportunity%20-%20Software%20Engineer">
  <img src="https://img.shields.io/badge/Email-zaldealberic@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="38" alt="Email" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/alberic13">
  <img src="https://img.shields.io/badge/GitHub-alberic13-181717?style=for-the-badge&logo=github&logoColor=white" height="38" alt="GitHub" />
</a>

</div>
