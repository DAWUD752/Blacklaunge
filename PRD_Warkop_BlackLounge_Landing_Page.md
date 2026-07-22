# 📄 Product Requirements Document (PRD)

## Warkop BlackLounge — Landing Page

---

### 1. Informasi Dokumen

| Field | Detail |
|-------|--------|
| **Project Title** | Warkop BlackLounge Landing Page |
| **Document Version** | v1.0 (Draft) |
| **Creation Date** | 22 Juli 2026 |
| **Status** | Draft — Menunggu Review |
| **Author** | — |
| **Stakeholders** | Owner BlackLounge, Web Developer, UI/UX Designer, Content Writer |

---

### 2. Overview / Ringkasan

**Warkop BlackLounge** adalah warkop 24 jam di kawasan Mojolangu, Malang yang membutuhkan sebuah **landing page** untuk memperkenalkan brand, menampilkan menu, galeri suasana, dan lokasi kepada calon pengunjung. Landing page ini menjadi **single source of truth** digital yang menggantikan atau melengkapi presence di media sosial.

**Elevator Pitch:**  
*"Sebuah landing page dark & modern untuk warkop 24 jam di Malang yang menampilkan identitas brand, menu preview, galeri suasana, dan arah lokasi — dengan nuansa hangat yang mengajak pengunjung datang kapan pun."*

---

### 3. Problem Statement / Masalah yang Diselesaikan

| Masalah | Dampak |
|---------|--------|
| BlackLounge tidak memiliki website resmi | Calon pengunjung sulit menemukan informasi lengkap (menu, lokasi, jam buka) dalam satu tempat |
| Informasi tersebar di media sosial saja | Tidak ada platform yang menampilkan brand identity secara konsisten dan profesional |
| Tidak ada tempat untuk menampilkan menu & galeri | Pengunjung potensial tidak bisa melihat suasana dan pilihan menu sebelum datang |
| Lokasi sulit dibagikan | Tidak ada link/shareable direction yang rapi untuk dibagikan ke teman |

---

### 4. Objectives & Success Metrics

#### 🎯 Objectives
1. **Brand Presence:** Membangun identitas digital profesional untuk Warkop BlackLounge
2. **Informasi:** Menyediakan informasi lengkap (menu, lokasi, jam buka, suasana) dalam satu halaman
3. **Konversi:** Mengarahkan pengunjung untuk datang ke lokasi fisik atau menghubungi via WhatsApp

#### 📊 Success Metrics

| Metric | Target | Timeline |
|--------|--------|----------|
| Page Load Time | < 2 detik | Launch |
| Mobile Responsiveness | 100% functional di semua screen size | Launch |
| Google Maps Clicks | >50 klik/bulan | 1 bulan post-launch |
| WhatsApp/Contact Clicks | >30 klik/bulan | 1 bulan post-launch |
| Bounce Rate | < 60% | 1 bulan post-launch |
| SEO Indexing | Muncul di pencarian "warkop 24 jam mojolangu malang" | 2 bulan post-launch |

---

### 5. Target Audience / Personas

| Persona | Deskripsi | Kebutuhan |
|---------|-----------|-----------|
| **Mahasiswa** | Tinggal di sekitar Mojolangu/Lowokwaru, sering nugas malam | Tempat nugas nyaman, buka 24 jam, WiFi, harga terjangkau |
| **Pekerja/Remote Worker** | Butuh tempat kerja di luar rumah | Suasana tenang, kopi, makanan ringan, buka kapan saja |
| **Komunitas/Teman** | Grup yang ingin nongkrong santai | Tempat nongkrong asyik, harga ramah kantong, lokasi strategis |
| **Pengunjung Malam** | Orang yang butuh tempat setelah aktivitas malam | Tempat buka larut malam, suasana nyaman, makanan tersedia |

---

### 6. Use Cases / Skenario Penggunaan

#### Use Case 1: Mencari Tempat Nugas Malam
> **Sebagai** mahasiswa yang sedang mengerjakan tugas deadline, **saya ingin** menemukan tempat ngopi yang buka 24 jam di dekat kampus, **sehingga** saya bisa nugas dengan nyaman sampai larut malam.

**Flow:** Google Search → Landing Page → Lihat section "Kenapa BlackLounge?" → Cek lokasi → Klik "Arah ke BlackLounge" → Datang.

#### Use Case 2: Melihat Menu Sebelum Datang
> **Sebagai** pengunjung pertama kali, **saya ingin** melihat pilihan menu dan kisaran harga, **sehingga** saya bisa menyiapkan budget sebelum datang.

**Flow:** Buka website → Scroll ke Section Menu → Lihat preview kategori → (Opsional) Klik "Lihat Semua Menu" → Datang dengan ekspektasi jelas.

#### Use Case 3: Membagikan Lokasi ke Teman
> **Sebagai** pengunjung yang ingin ajak teman nongkrong, **saya ingin** membagikan lokasi BlackLounge dengan mudah, **sehingga** teman saya bisa langsung navigasi.

**Flow:** Buka website → Section Lokasi → Klik "Bagikan Lokasi" → Share via WhatsApp/Instagram → Teman klik link → Buka Google Maps.

---

### 7. Functional Requirements

#### 7.1 Navbar (Sticky Navigation)

| ID | Requirement | Priority |
|----|-------------|----------|
| F-01 | Navbar sticky di top, efek glassmorphism semi-transparent dark | Must Have |
| F-02 | Logo "BLACKLOUNGE" di kiri | Must Have |
| F-03 | Menu navigasi: Home, Menu, Tentang, Galeri, Lokasi | Must Have |
| F-04 | CTA "Lihat Lokasi" di kanan | Must Have |
| F-05 | Hamburger menu untuk mobile (<768px) | Must Have |
| F-06 | Smooth scroll ke section saat menu diklik | Must Have |
| F-07 | Navbar berubah style saat scroll (lebih opaque) | Should Have |

#### 7.2 Hero Section

| ID | Requirement | Priority |
|----|-------------|----------|
| F-08 | Full-screen background image: interior warkop malam hari, nuansa gelap, lampu warm | Must Have |
| F-09 | Overlay gelap (black, ~60% opacity) untuk readability teks | Must Have |
| F-10 | Badge: "OPEN 24 HOURS • MOJOLANGU, MALANG" | Must Have |
| F-11 | Heading besar: "Tempat Nongkrong, Kapan Pun." | Must Have |
| F-12 | Subheading deskriptif | Must Have |
| F-13 | CTA Primary: "Lihat Menu" (scroll ke section menu) | Must Have |
| F-14 | CTA Secondary: "Datang ke BlackLounge" (scroll ke lokasi) | Must Have |
| F-15 | Info bar bawah: OPEN 24 HOURS / Mojolangu, Malang / Coffee • Food • Hangout | Must Have |
| F-16 | Efek grain subtle pada background | Should Have |
| F-17 | Animasi fade-in & slide-up saat load | Should Have |

#### 7.3 Section "Kenapa BlackLounge?"

| ID | Requirement | Priority |
|----|-------------|----------|
| F-18 | Judul: "Lebih dari Sekadar Warkop." | Must Have |
| F-19 | Subheading deskriptif | Must Have |
| F-20 | 4 card dengan icon: 24 Jam, Kopi & Minuman, Tempat Nugas, Nongkrong Bareng | Must Have |
| F-21 | Setiap card: icon, judul, deskripsi singkat | Must Have |
| F-22 | Layout responsive: 4 kolom (desktop) → 2 kolom (tablet) → 1 kolom (mobile) | Must Have |
| F-23 | Hover effect: subtle lift + glow | Should Have |

#### 7.4 Section Menu (Preview)

| ID | Requirement | Priority |
|----|-------------|----------|
| F-24 | Judul: "Teman Nongkrongmu" | Must Have |
| F-25 | Tab/Kategori: Coffee, Non-Coffee, Makanan, Snack | Must Have |
| F-26 | Card per item: nama, deskripsi singkat, harga (format Rp xx.xxx) | Must Have |
| F-27 | Grid layout: 2-4 kolom tergantung screen | Must Have |
| F-28 | CTA: "Lihat Semua Menu" | Must Have |
| F-29 | **Catatan:** Harga asli ditampilkan "Rp xx.xxx" sebagai placeholder sampai data terverifikasi | Must Have |
| F-30 | Filter/tab aktif menunjukkan kategori yang dipilih | Should Have |

#### 7.5 Section "BlackLounge 24/7" (Signature Section)

| ID | Requirement | Priority |
|----|-------------|----------|
| F-31 | Full-width background: foto suasana malam | Must Have |
| F-32 | Heading besar: "Malam Belum Selesai. BlackLounge tetap buka." | Must Have |
| F-33 | Body text: copy persuasif tentang buka 24 jam | Must Have |
| F-34 | CTA: "Datang Sekarang" (arah ke lokasi) | Must Have |
| F-35 | Dark overlay untuk kontras teks | Must Have |
| F-36 | Parallax effect saat scroll | Could Have |

#### 7.6 Section Galeri

| ID | Requirement | Priority |
|----|-------------|----------|
| F-37 | Judul: "Suasana BlackLounge" | Must Have |
| F-38 | Layout masonry/grid: 1 large image + 5 smaller images | Must Have |
| F-39 | Kategori foto: eksterior, interior, meja nongkrong, makanan, minuman, suasana malam | Must Have |
| F-40 | Hover effect: image zoom + dark overlay + icon ↗ | Must Have |
| F-41 | Lightbox modal saat gambar diklik (opsional) | Should Have |
| F-42 | Lazy loading untuk performa | Should Have |

#### 7.7 Section Lokasi

| ID | Requirement | Priority |
|----|-------------|----------|
| F-43 | Judul: "Temukan Kami" | Must Have |
| F-44 | Alamat lengkap: Jl. Manunggal Jl. Sudimoro Utara No.6, Mojolangu, Kec. Lowokwaru, Kota Malang, Jawa Timur 65142 | Must Have |
| F-45 | Info: "Buka 24 Jam" dengan icon jam | Must Have |
| F-46 | Tombol Primary: "Buka Google Maps" (link ke Google Maps) | Must Have |
| F-47 | Tombol Secondary: "Bagikan Lokasi" (shareable link/copy) | Must Have |
| F-48 | Google Maps embed (iframe) | Should Have |
| F-49 | Icon/ilustrasi peta atau pin lokasi | Could Have |

#### 7.8 CTA Section (Pre-Footer)

| ID | Requirement | Priority |
|----|-------------|----------|
| F-50 | Heading: "Lapar? Ngopi? Atau Cuma Butuh Tempat Nongkrong?" | Must Have |
| F-51 | Subheading: "Jangan terlalu banyak mikir. Datang aja ke BlackLounge." | Must Have |
| F-52 | CTA: "Arah ke BlackLounge" | Must Have |

#### 7.9 Footer

| ID | Requirement | Priority |
|----|-------------|----------|
| F-53 | Logo "BLACK LOUNGE" | Must Have |
| F-54 | Tagline: "Tempat Nongkrong, Kapan Pun." | Must Have |
| F-55 | Info: 📍 Mojolangu, Malang / 🕐 Open 24 Hours | Must Have |
| F-56 | Social links: Instagram, WhatsApp, Google Maps | Must Have |
| F-57 | Copyright: © 2026 Warkop BlackLounge | Must Have |

---

### 8. Non-Functional Requirements

| ID | Requirement | Target |
|----|-------------|--------|
| NF-01 | **Performance:** Page load < 2 detik di koneksi 3G | < 2s |
| NF-02 | **Performance:** Lighthouse Performance Score > 90 | > 90 |
| NF-03 | **Responsive:** Mobile-first, breakpoint 320px - 1920px+ | All sizes |
| NF-04 | **SEO:** Semantic HTML, meta tags, Open Graph, structured data | Standard |
| NF-05 | **SEO:** Title: "Warkop BlackLounge | Tempat Nongkrong 24 Jam Mojolangu Malang" | Must Have |
| NF-06 | **SEO:** Meta description mengandung keyword utama | Must Have |
| NF-07 | **Accessibility:** WCAG 2.1 AA minimum (kontras teks, alt text, keyboard nav) | AA |
| NF-08 | **Accessibility:** Alt text untuk semua gambar | Must Have |
| NF-09 | **Security:** HTTPS only | Must Have |
| NF-10 | **Analytics:** Google Analytics 4 + Google Tag Manager setup | Should Have |
| NF-11 | **Hosting:** Static hosting (Vercel/Netlify/GitHub Pages) | Recommended |
| NF-12 | **Domain:** Custom domain (opsional) | Could Have |

---

### 9. Design Requirements

#### 9.1 Color Palette

| Token | Hex | Usage |
|-------|-----|-------|
| **BLACK** | `#0D0D0D` | Background utama |
| **CHARCOAL** | `#171717` | Card background, navbar |
| **WARM AMBER** | `#D99A3D` | Primary accent, CTA, badge, hover |
| **CREAM** | `#F4EBDD` | Heading teks, teks terang |
| **GRAY** | `#8A8A8A` | Body text secondary, border |
| **WHITE** | `#FFFFFF` | Teks primary, icon |

#### 9.2 Typography

| Elemen | Font | Weight | Size (Desktop) |
|--------|------|--------|----------------|
| Heading Hero | Bold Sans Serif (Inter/Poppins/Montserrat) | 700-900 | 48-64px |
| Heading Section | Bold Sans Serif | 700 | 32-40px |
| Body | Modern Sans Serif (Inter) | 400 | 16-18px |
| Badge/Label | Sans Serif | 500 | 12-14px |

#### 9.3 UI Components

| Komponen | Spesifikasi |
|----------|-------------|
| **Button Primary** | Background Warm Amber, text Black, rounded-full (pill), padding 12px 32px |
| **Button Secondary** | Border Warm Amber, text Warm Amber, transparent bg, rounded-full |
| **Card** | Background Charcoal, border subtle gray, radius 16px, padding 24px |
| **Navbar** | Sticky, glassmorphism (backdrop-blur), semi-transparent dark |
| **Border Radius** | 12-20px untuk card, rounded-full untuk button |

#### 9.4 Visual Style

| Aspek | Konsep |
|-------|--------|
| **Style** | Dark Urban / Modern Warkop |
| **Photography** | Dark cinematic, warm lighting, interior malam hari |
| **Effects** | Subtle grain, glow on hover, smooth blur |
| **Animation** | Fade-in, slide-up, smooth scroll |
| **Layout** | Modern editorial, generous whitespace |

---

### 10. Technical Considerations

| Aspek | Rekomendasi |
|-------|-------------|
| **Tech Stack** | HTML + CSS + Vanilla JS (atau framework: Next.js/React + Tailwind) |
| **CSS Framework** | Tailwind CSS (recommended) |
| **Animation** | CSS transitions + Intersection Observer API / GSAP (opsional) |
| **Images** | WebP format, lazy loading, responsive images |
| **Icons** | Lucide React / Font Awesome / SVG inline |
| **Maps** | Google Maps Embed API atau static link |
| **Hosting** | Vercel / Netlify / Cloudflare Pages (free tier) |

---

### 11. Timeline & Milestones

| Phase | Deliverable | Estimasi |
|-------|-------------|----------|
| **Phase 1** | Finalisasi PRD & Asset Gathering (foto, logo, copy) | 2-3 hari |
| **Phase 2** | Wireframe & Design Mockup (Figma) | 3-5 hari |
| **Phase 3** | Development (HTML/CSS/JS) | 5-7 hari |
| **Phase 4** | Content Integration (teks, foto, menu) | 2-3 hari |
| **Phase 5** | Testing (responsive, performa, SEO) | 2 hari |
| **Phase 6** | Deployment & Launch | 1 hari |
| **Total** | | **~15-21 hari** |

---

### 12. Assets Checklist

| Asset | Status | Keterangan |
|-------|--------|------------|
| Logo BlackLounge | ⬜ | Butuh file SVG/PNG high-res |
| Foto Interior (malam) | ⬜ | Minimal 5-7 foto untuk hero & galeri |
| Foto Eksterior | ⬜ | 1-2 foto |
| Foto Makanan/Minuman | ⬜ | 4-6 foto untuk menu & galeri |
| Foto Suasana Nongkrong | ⬜ | 2-3 foto |
| Daftar Menu Lengkap | ⬜ | Nama, deskripsi, harga (bisa placeholder dulu) |
| Link Google Maps | ⬜ | URL shareable |
| Link Instagram | ⬜ | URL profil |
| Link WhatsApp | ⬜ | URL wa.me dengan pesan default |

---

### 13. Open Questions & Risks

| # | Question/Risk | Mitigasi |
|---|---------------|----------|
| 1 | **Harga menu belum final** | Gunakan placeholder "Rp xx.xxx" sementara |
| 2 | **Foto profesional belum tersedia** | Gunakan foto sementara dengan watermark, atau jadwalkan photoshoot |
| 3 | **Belum ada domain & hosting** | Gunakan free tier Vercel/Netlify dulu, domain bisa belakangan |
| 4 | **Siapa yang maintain website?** | Dokumentasikan cara update menu & foto |
| 5 | **Apakah perlu fitur reservasi/pesan online?** | **Out of scope** untuk v1.0, bisa dipertimbangkan v2.0 |
| 6 | **Apakah perlu blog/konten?** | **Out of scope** untuk v1.0 |

---

### 14. Scope: In Scope vs Out of Scope

#### ✅ In Scope (v1.0)
- Single-page landing page (10 sections)
- Informasi statis (tidak ada CMS)
- Link eksternal (Google Maps, WhatsApp, Instagram)
- Responsive design
- SEO dasar

#### ❌ Out of Scope (v1.0)
- Sistem pemesanan/reservasi online
- CMS untuk update menu
- Blog / konten dinamis
- E-commerce / pembayaran online
- Multi-language
- User login / membership
- Review/rating system

---

### 15. Appendix

#### A. Tagline Alternatif
- 24 Jam. Kopi. Cerita.
- Tempat Pulang Sebelum Pulang.
- Ngopi Kapan Aja, Nongkrong Sesuka Hati.
- Your 24/7 Hangout Spot in Malang.

#### B. Menu Preview (Placeholder)

| Kategori | Item | Deskripsi | Harga (Placeholder) |
|----------|------|-----------|---------------------|
| Coffee | Kopi Hitam | Kopi klasik untuk menemani malam panjang | Rp xx.xxx |
| Coffee | Kopi Susu | Perpaduan kopi dan susu yang creamy | Rp xx.xxx |
| Non-Coffee | Es Teh | Sederhana, segar, dan cocok kapan saja | Rp xx.xxx |
| Makanan | Mie / Snack | Teman ngemil saat ngobrol atau nugas | Rp xx.xxx |

#### C. Alamat Lengkap
Jl. Manunggal Jl. Sudimoro Utara No.6, Mojolangu, Kec. Lowokwaru, Kota Malang, Jawa Timur 65142

---

### 16. Change Log

| Version | Date | Changes | By |
|---------|------|---------|-----|
| v1.0 | 22 Juli 2026 | Initial draft | — |

---

**Status Review:** ⬜ Pending Review | ⬜ Approved | ⬜ In Progress | ⬜ Done
