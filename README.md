# MyIntress Mobile Dashboard & Early Warning System (EWS)

Proyek ini merupakan visualisasi perbaikan layout antarmuka **MyIntress** (Kementerian Keuangan RI) versi mobile yang responsif, terstruktur, serta dilengkapi dengan fitur **Early Warning System (EWS)** yang didesain senada (*cohesive style*) dengan sistem desain aplikasi.

---

## 🚀 Cara Mengunggah (Deploy) ke GitHub Pages

### Langkah 1: Push ke Repositori GitHub
1. Buat repositori baru di GitHub (misalnya: `myintress-dashboard`).
2. Extract file ZIP ini di komputer Anda.
3. Upload seluruh file (`index.html`, `README.md`) ke repositori GitHub tersebut.

### Langkah 2: Aktifkan GitHub Pages
1. Buka repositori Anda di **GitHub.com**.
2. Masuk ke menu **Settings** > **Pages** (di sidebar kiri).
3. Pada bagian **Build and deployment**:
   - **Source**: Pilih `Deploy from a branch`.
   - **Branch**: Pilih `main` (atau `master`) dan folder `/ (root)`.
4. Klik **Save**.
5. Tunggu sekitar 1-2 menit. Halaman web Anda akan aktif dan siap diakses publik di URL:  
   `https://<username-github>.github.io/<nama-repo>/`

---

## 🎨 Fitur Perbaikan Layout
1. **Fully Responsive:** Layout menyesuaikan secara dinamis pada layar smartphone hingga desktop.
2. **Proporsional Chart:** *Bar chart* dan *Donut chart* menggunakan kontainer `aspect-ratio` responsif Chart.js agar tidak pernah meluap (*overflow*) atau terpotong.
3. **Cohesive EWS Design:** Pop-up peringatan dini dirancang dengan aksen *UI/UX enterprise* khas Kementerian Keuangan (gabungan warna *Navy Blue*, *Crimson Warning*, dan *Amber Accent*).
