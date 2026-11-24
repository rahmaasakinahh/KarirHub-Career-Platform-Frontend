
# **KarirHub – Career Platform Frontend**

---

KarirHub merupakan platform rekrutmen digital berbasis web yang menghubungkan pencari kerja dengan perusahaan melalui sistem pengelolaan lowongan, lamaran, dan proses rekrutmen yang terintegrasi.

Project ini dikembangkan sebagai Final Project mata kuliah Manajemen Basis Data di Institut Teknologi Sepuluh Nopember (ITS).

## **Project Overview**

---

KarirHub dirancang untuk mendukung proses rekrutmen melalui tiga peran utama:

| Role | Description |
| --- | --- |
| **Job Seeker** | Mencari lowongan, mengajukan lamaran, dan memantau proses rekrutmen. |
| **Company** | Mengelola lowongan, pelamar, dan tahapan seleksi. |
| **Admin** | Melakukan verifikasi perusahaan, mengelola master data, dan memantau aktivitas platform. |

## **Key Features**

---

### **1. Job Seeker**

---

- Pencarian dan filter lowongan pekerjaan.
- Pengajuan lamaran dengan cover letter.
- Dashboard dan riwayat lamaran.
- Pelacakan tahapan dan status rekrutmen.
- Pengelolaan profil, pendidikan, pengalaman kerja, dan skill.
- Notifikasi status lamaran.

### **2. Company**

---

- Pembuatan dan pengelolaan lowongan pekerjaan.
- Pengelolaan data pelamar.
- Seleksi pelamar berdasarkan tahapan rekrutmen.
- Penjadwalan wawancara online dan onsite.
- Dashboard rekrutmen dan notifikasi pelamar.

### **3. Admin**

---

- Dashboard statistik platform.
- Verifikasi akun perusahaan.
- Pengelolaan master data skill.
- Pemantauan aktivitas platform.

## **Tech Stack**

---

| Category | Technology |
| --- | --- |
| Frontend | React 18 |
| Routing | React Router v7 |
| Styling | Tailwind CSS v3 |
| Programming Language | JavaScript, TypeScript |
| Icons | Lucide React |
| Build Tool | Vite 6 |
| Server Framework | Hono |
| Database Configuration | Neon PostgreSQL |
| Authentication Configuration | Auth.js |
| Testing | Vitest, Testing Library, jsdom |
| Package Manager | npm |

## **Project Structure**

---

```text
KarirHub-Career-Platform-Frontend/
├── src/
│   ├── app/
│   │   ├── admin/
│   │   ├── company/
│   │   ├── companies/
│   │   ├── seeker/
│   │   ├── jobs/
│   │   ├── login/
│   │   ├── register/
│   │   └── api/
│   ├── components/
│   ├── context/
│   ├── data/
│   ├── lib/
│   └── utils/
├── __create/
├── plugins/
├── public/
├── test/
├── package.json
├── vite.config.ts
├── tailwind.config.js
├── react-router.config.ts
├── tsconfig.json
└── README.md
```

## **How to Run**

---

### **1. Prerequisites**

---

- Node.js 20 atau lebih baru.
- npm 10 atau lebih baru.

### **2. Clone Repository**

---

```bash
git clone https://github.com/rahmaasakinahh/KarirHub-Career-Platform-Frontend.git

cd KarirHub-Career-Platform-Frontend
```

### **3. Install Dependencies**

---

```bash
npm install
```

### **4. Run Development Server**

---

```bash
npm run dev
```

Akses aplikasi melalui:

http://localhost:4000

### **5. Build Project**

---

```bash
npm run build
```

## **Testing and Type Checking**

---

```bash
# Type checking
npm run typecheck

# Testing
npx vitest run
```

## **Notes**

---

- Repository ini berfokus pada implementasi frontend KarirHub.
- Aplikasi merupakan prototype yang menggunakan mock data untuk mendemonstrasikan alur rekrutmen berdasarkan peran pengguna.
- Pengelolaan sesi pengguna pada prototype menggunakan React Context dan Local Storage.
- Konfigurasi Hono, Neon PostgreSQL, dan Auth.js telah tersedia dalam project, tetapi fitur frontend belum sepenuhnya terintegrasi dengan database dan autentikasi backend.
