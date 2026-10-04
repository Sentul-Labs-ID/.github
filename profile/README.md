<div align="center">

# 🛡️ SENTUL LABS

### Cyber Defense Engineering · Universitas Pertahanan Republik Indonesia

***Kami membangun sistem yang tidak hanya berjalan, tetapi dapat dipercaya.***

![Lokasi](https://img.shields.io/badge/Sentul%2C%20Bogor-Indonesia-2D6A4F?style=for-the-badge)
![Fokus](https://img.shields.io/badge/Focus-Secure%20Systems%20%26%20Data%20Integrity-1D3557?style=for-the-badge)
![Bidang](https://img.shields.io/badge/Rekayasa%20Pertahanan%20Siber-S2%20Unhan-7209B7?style=for-the-badge)

</div>

---

## Tentang Kami

**Sentul Labs** adalah tim riset dan pengembangan yang berisi mahasiswa Magister Rekayasa Pertahanan Siber (RPS) Universitas Pertahanan Republik Indonesia. Kami menggabungkan kemampuan rekayasa perangkat lunak penuh (full-stack) dengan disiplin keamanan siber dan kriptografi untuk membangun sistem yang integritasnya dapat dibuktikan, bukan sekadar diklaim.

Latar belakang kami di bidang pertahanan siber membuat kami terbiasa berpikir tentang ancaman, manipulasi data, dan ketahanan sistem sejak baris kode pertama. Cara pandang itulah yang kami bawa untuk menyelesaikan persoalan nyata, dari sistem akademik berskala enterprise, platform logistik berbasis AI, rantai pasok ekonomi rakyat, hingga integritas klaim jaminan kesehatan nasional.

---

## 🚀 Proyek

### 1. JKN-Sentinel · *Unggulan Terkini*

> **Deteksi Klaim Fiktif, Berulang, dan Tidak Wajar dalam Program JKN**
> Dikembangkan untuk *BPJS Kesehatan Healthkathon 2026*, kategori Efisiensi Risiko pada Fasilitas Kesehatan.

JKN-Sentinel memeriksa setiap tagihan rumah sakit ke BPJS Kesehatan dengan dua pertanyaan: mungkinkah layanan ini terjadi dengan kapasitas nyata rumah sakit, dan wajarkah tagihannya menurut aturan. Pengecekan otomatis yang dapat dijelaskan menyusun daftar prioritas pemeriksaan. Sensor IoT dengan Edge AI memastikan mesin benar-benar dipakai untuk terapi, dan setiap pesan sensor ditandatangani secara digital serta dirantai *hash*. Keputusan akhir tetap di tangan petugas dan tercatat dalam rantai audit yang tidak bisa diubah diam-diam.

**Sorotan (data uji tersembunyi, data tiruan):** 83 dari 86 kejadian kecurangan terdeteksi · 0 tuduhan keliru dari 26 periode yang diprioritaskan · Edge AI 97,8% · Hasil dapat direproduksi persis dari repositori.

`Python` · `FastAPI` · `PostgreSQL` · `Next.js` · `scikit-learn` · `Ed25519` · `Docker`

🔗 [Repositori prototipe](https://github.com/Sentul-Labs-ID/JKN-Sentinel-Prototype)

---

### 2. RANTAI

> **Platform Penelusuran Rantai Pasok Komoditas Koperasi Desa dengan Jejak Asal-Usul Tahan-Rusak**
> Dikembangkan untuk *Hackathon Digital Cooperatives Expo 2026* — Kementerian Koperasi RI × PEBS FEB UI.

Program Koperasi Desa/Kelurahan Merah Putih menempatkan koperasi sebagai simpul utama rantai pasok komoditas desa, namun alur ini berjalan nyaris tanpa penelusuran. RANTAI merekam perjalanan komoditas pada setiap titik, dari setoran panen anggota hingga penyaluran ke pembeli dan BUMN, lalu mengunci setiap catatan secara kriptografis dengan fungsi *hash* yang dirantai. Begitu ada data yang diubah diam-diam di titik mana pun, rantai integritasnya putus dan langsung terdeteksi. Asal-usul serta keaslian komoditas menjadi sesuatu yang dapat diverifikasi secara matematis.

**Sorotan:** Penelusuran rantai pasok *real-time* · Jejak asal-usul tahan-rusak · Transparansi terverifikasi bagi anggota dan pembeli · Skema kriptografi siap migrasi ke *Post-Quantum Cryptography*.

`Next.js` · `FastAPI` · `PostgreSQL` · `Docker` · `Cryptographic Hash Chain`

---

### 3. SENTINEL Logistik

> **Cyber-Resilient AI Logistics Intelligence Platform**
> Dibangun untuk *AI Open Innovation Challenge 2026 — Logistics Sector*. Proyek terpisah dari JKN-Sentinel.

SENTINEL adalah platform inteligensi logistik yang melampaui optimasi rute konvensional. Ia menambahkan lapisan kepercayaan, integritas, dan ketahanan di atas operasi pengiriman standar untuk pengambilan keputusan logistik yang prediktif dan tepercaya bagi e-commerce Indonesia. Prototipe interaktif platform ini mendemonstrasikan proses bisnis dan pengalaman pengguna pada delapan modul intinya.

**Sorotan:** Akuntansi karbon yang dapat diverifikasi · Deteksi kecurangan multi-vektor · Simulasi kegagalan berantai (*cascading-failure*) · Delapan modul inti dalam satu prototipe.

`AI / Predictive Analytics` · `Logistics Intelligence` · `Interactive Frontend Prototype`

---

### 4. CDE Portal · *Enterprise SaaS Blueprint*

> **Portal Akademik Terintegrasi** untuk Pusat Studi, pengelolaan jurnal ilmiah, Tracer Study, dan *Cyber Security Tracking*.

CDE Portal berjalan di atas arsitektur *microservices* berbasis kontainer yang terisolasi untuk memastikan modularitas dan keamanan data setingkat enterprise. Setiap layanan berjalan independen dan terhubung melalui satu gerbang terpusat.

| Layanan | Teknologi | Port |
|---|---|---|
| Frontend | Next.js | 3000 |
| Backend API | FastAPI | 8000 |
| Database | PostgreSQL 15 | 5432 |
| Object Storage | MinIO | 9000 / 9001 |
| Journal Engine | Open Journal Systems (OJS) 3.4 | — |
| Reverse Proxy & Gateway | Nginx | 80 |

`Microservices` · `Containerized` · `Next.js` · `FastAPI` · `PostgreSQL` · `MinIO` · `OJS` · `Nginx`

---

## 👥 Tim

| Anggota | Peran | Fokus Kontribusi |
|---|---|---|
| **Joesavat Donovan** | Project Manager & Product Lead | Perencanaan produk, pemahaman domain, perancangan alur pengguna, dan koordinasi tim |
| **Rifandi Indrayudha Prawira** | Technical Architect & Security Engineer | Arsitektur sistem hulu ke hilir, mesin integritas jejak audit, dan rancang keamanan kriptografis |
| **Syaddad Aulia** | Fullstack Developer | Pengembangan antarmuka dan layanan, pemetaan pelaporan, serta pengujian dan penjaminan mutu |
| **Akbar Farizky** | Health Domain Analyst | Analisis proses layanan dan klaim rumah sakit, serta validasi kebutuhan pengguna |

<sub>Tim BPJS Kesehatan Healthkathon 2026 (JKN-Sentinel): Rifandi, Joesavat, dan Akbar.</sub>

<sub>📧 sentul.labs@gmail.com · joesavat.donovan@tp.idu.ac.id · rifandi.prawira@tp.idu.ac.id · syaddad.rahman@tp.idu.ac.id</sub>

---

## 🧰 Tech Stack

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

</div>

**Keahlian khusus:** Keamanan Siber · Integritas & Forensik Data · Deteksi Anomali & Kecurangan · Kriptografi (termasuk *Post-Quantum Cryptography*) · Arsitektur *Microservices* · Tata Kelola Sistem Informasi

---

## 📫 Kontak

Untuk kolaborasi atau pertanyaan, hubungi kami melalui sentul.labs@gmail.com atau email institusi di atas, atau buka *issue* pada repositori proyek kami.

<div align="center">

<sub>© 2026 Sentul Labs — Universitas Pertahanan Republik Indonesia</sub>

</div>
Sedang diperbarui.
