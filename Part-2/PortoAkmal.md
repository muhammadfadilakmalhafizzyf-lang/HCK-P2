Saya ingin Anda membuatkan sebuah website portofolio modern dan profesional untuk "Akmal Dev", seorang Full-Stack & Front-End Developer. Website ini dirancang dengan gaya "Modern Tech Minimalist" berbasis Dark Mode.

Berikut adalah spesifikasi detail teknis, desain UI/UX, tata letak responsif, dan konten yang harus diimplementasikan:

---

### 1. TECH STACK & ARSITEKTUR
- **Framework:** Next.js (React) / Vite React (Single-page app atau multi-section SPA).
- **Styling:** Tailwind CSS (menggunakan arsitektur Dark Mode default).
- **Icons:** Lucide React / React Icons.
- **Animations:** Framer Motion (interaksi dan transisi halus).
- **Typography:** Inter / Plus Jakarta Sans (Body & Headings) dan JetBrains Mono (Code/Badges).

---

### 2. DESAIN UI/UX & SKEMA WARNA
- **Tema:** Dark Mode First (Modern Tech Minimalist).
- **Warna Utama:**
  - Background: Deep Dark Slate/Charcoal (`#0f172a` atau `#090d16`).
  - Card / Surface: Dark Slate dengan transparansi/glassmorphism (`#1e293b` dengan opacity atau `backdrop-blur`).
  - Text Primary: Neutral White (`#f8fafc`).
  - Text Secondary: Muted Slate (`#94a3b8`).
  - Accent Colors: Neon Cyan (`#06b6d4`), Emerald Green (`#10b981`), atau Electric Violet (`#8b5cf6`).
- **Interaksi:**
  - Hover effect glow pada kartu proyek dan tombol.
  - Micro-interactions (misal: tombol "Copy Email" yang menampilkan toast/notifikasi singkat).
  - Smooth scrolling untuk navigasi antar section.

---

### 3. DOKUMENTASI STRUKTUR LAYOUT & RESPONSIVITAS

#### A. Breakpoints Strategy:
- **Mobile (< 640px):** Layout 1 kolom murni, touch-friendly CTA (minimal tinggi 48px), navigasi hamburger menu atau floating bar di bawah.
- **Tablet (640px - 1024px):** Layout 2 kolom untuk grid proyek dan tech stack.
- **Desktop (> 1024px):** Sticky/Glassmorphism navbar di atas, 2 kolom pada Hero section (Text & Visual), grid 2-3 kolom pada kartu proyek.

#### B. Rincian Komponen & Layout:

1. **Header / Navbar:**
   - Brand Logo: **Akmal.dev** (dengan font mono & aksen titik berwarna cyan).
   - Menu Navigasi: Home, About, Skills, Projects, Experience, Contact.
   - Dark/Light Mode toggle (opsional, default ke Dark Mode).

2. **Hero Section:**
   - Left Side (Mobile: Top): Title ("Hi, I'm Akmal"), Tagline ("Full-Stack & Front-End Developer building fast, scalable, and offline-first web experiences"), Tombol CTA ("View Projects", "Contact Me").
   - Right Side (Mobile: Bottom): Terminal Interaktif Mockup atau animasi visual kode modern yang relevan.

3. **About Me Section:**
   - Ringkasan profesional tentang filosofi koding (bersih, efisien, performa tinggi, dan berorientasi pada pengguna).
   - Tampilan statistik ringkas (misal: "X+ Years Experience", "X+ Projects Completed").

4. **Tech Stack & Skills Section:**
   - Dikategorikan secara rapi (Frontend, Backend, Database/Tools).
   - Menggunakan ikon SVG/Lucide + label nama teknologi.
   - Responsive Grid: 3 kolom di mobile, 6-8 kolom di desktop.

5. **Featured Projects Section:**
   - Kartu proyek interaktif dengan atribut: Gambar preview, Judul, Deskripsi singkat, Tag teknologi (Badges), Tautan ke Live Demo & Repositori GitHub.
   - Grid System: 1 kolom di mobile, 2 kolom di desktop.

6. **Experience / Timeline Section:**
   - Tampilan timeline vertikal untuk riwayat kerja/freelance dan kontribusi proyek.

7. **Contact & Footer Section:**
   - Form kontak (Nama, Email, Pesan) dengan validasi.
   - Tautan langsung sosial media (GitHub, LinkedIn, Email, WhatsApp).
   - Footer copyright: "© 2026 Akmal Dev. Built with passion and precision."

---

### 4. TUGAS ANDA
Buatkan struktur kode bersih (bersifat Single File React/PWA komponen atau terstruktur rapi jika dalam Next.js), sertakan styling Tailwind CSS yang siap jalan, dan pastikan responsive di mobile serta desktop!
