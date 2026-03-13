# 🪙 PengLon — Aplikasi Keuangan Pribadi

> **⚠️ Status: Masa Percobaan (Beta)**
> Aplikasi ini sedang dalam tahap pengembangan aktif. Fitur dapat berubah sewaktu-waktu dan mungkin terdapat bug. Gunakan dengan bijak — jangan gunakan sebagai satu-satunya catatan keuangan utama Anda.

---

## Tentang PengLon

**PengLon** adalah aplikasi pencatat keuangan pribadi berbasis web yang ringan, cepat, dan berjalan sepenuhnya di browser — tanpa server, tanpa login, tanpa berlangganan. Semua data tersimpan langsung di perangkat Anda melalui `localStorage`.

Dirancang dengan tampilan minimalis premium dan mobile-first, PengLon cocok untuk siapapun yang ingin memantau pemasukan, pengeluaran, tabungan, dan hutang dalam satu tempat yang rapi.

---

## Fitur Utama

### 📊 Dashboard
- Ringkasan saldo, pemasukan, dan pengeluaran per periode
- Widget hari ini — transaksi & saldo real-time
- Insight otomatis berdasarkan pola pengeluaran
- Filter periode fleksibel (bulan ini, bulan lalu, custom range)

### 💸 Transaksi
- Catat pemasukan & pengeluaran dengan cepat
- Kategori lengkap dengan emoji
- Pengelompokan berdasarkan hari
- Pencarian & filter berdasarkan tipe, dompet, kategori
- Numpad input cepat
- Label tagihan berulang (recurring)

### 💼 Multi-Dompet
- Buat dompet tak terbatas (Bank, E-Wallet, Tunai, Investasi, dll)
- Transfer antar dompet dengan pencatatan otomatis
- Saldo real-time per dompet

### 🎯 Tabungan & Wish List
- Buat goals tabungan dengan target & deadline
- Top up dari dompet manapun
- Wish list belanja dengan sistem alokasi dana
- Progress bar visual per goal

### 🤝 Hutang & Piutang
- Catat hutang (yang kamu pinjam) dan piutang (yang kamu pinjamkan)
- Cicil sebagian dengan riwayat pembayaran
- Status lunas otomatis

### 🔄 Tagihan Berulang (Recurring)
- Daftarkan tagihan rutin bulanan
- Pengingat transaksi yang belum dicatat
- Log langsung dari halaman recurring

### 📈 Laporan
- Grafik pemasukan vs pengeluaran (bar & pie chart)
- Analisis budget 50/30/20 (Kebutuhan / Keinginan / Investasi)
- Perbandingan antar bulan
- Heatmap kalender pengeluaran
- Histori tren net worth

### 🔐 Backup & Restore
- Export semua data ke file `.json`
- Import / restore dari file backup
- Share backup via aplikasi lain (mobile)
- Reset data lengkap

---

## Teknologi

| Komponen | Detail |
|---|---|
| **Bahasa** | HTML, CSS, Vanilla JavaScript |
| **Chart** | Chart.js 4.4 |
| **Font** | DM Sans + DM Serif Display (Google Fonts) |
| **Storage** | Browser `localStorage` |
| **Dependencies** | Tidak ada (zero npm/node) |
| **Bundle size** | ~280 KB (single file) |

---

## Cara Pakai

### Buka Langsung
Cukup download file `index.html` dan buka di browser — tidak perlu instalasi apapun.

### Self-host di GitHub Pages
1. Fork repository ini
2. Masuk ke **Settings → Pages**
3. Set source ke branch `main`, folder `/ (root)`
4. Akses via `https://username.github.io/penglon`

### Netlify Drop (paling cepat)
1. Buka [netlify.com/drop](https://netlify.com/drop)
2. Drag & drop file `index.html`
3. Langsung online dalam hitungan detik

---

## ⚠️ Penting: Soal Data

Semua data disimpan di **`localStorage` browser**. Artinya:

- ✅ Data tersimpan permanen di browser yang sama
- ❌ Data **tidak sinkron** antar device (HP ≠ laptop)
- ❌ Data akan **hilang** jika clear cache / ganti browser
- 💡 **Selalu backup** secara rutin via Settings → Backup & Restore

---

## Testing & Development

Untuk keperluan testing, tersedia tombol **🧪 Load Dummy Data** di halaman **Settings → Backup & Restore**. Tombol ini akan mengisi aplikasi dengan data contoh lengkap (transaksi 3 bulan, 4 dompet, goals, hutang, dll). Data lama akan ditimpa.

Untuk mereset semua data ke kondisi kosong, gunakan tombol **🗑️ Reset Semua Data** di halaman yang sama.

---

## Status Pengembangan

| Fitur | Status |
|---|---|
| Dashboard & ringkasan | ✅ Selesai |
| Catat transaksi | ✅ Selesai |
| Multi-dompet & transfer | ✅ Selesai |
| Tabungan & Wish List | ✅ Selesai |
| Hutang & Piutang | ✅ Selesai |
| Tagihan berulang | ✅ Selesai |
| Laporan & grafik | ✅ Selesai |
| Backup & restore | ✅ Selesai |
| Mode gelap / terang | ✅ Selesai |
| Sinkronisasi cloud | 🔜 Belum tersedia |
| Versi PWA (install ke HP) | 🔜 Direncanakan |
| Multi-user / akun | 🔜 Direncanakan |
| Export ke PDF / Excel | 🔜 Direncanakan |

---

## Kontribusi

Proyek ini masih dalam masa percobaan. Jika menemukan bug atau punya saran fitur, silakan buka **Issue** di repository ini.

---

## Lisensi

Proyek ini bersifat terbuka untuk digunakan secara pribadi. Dilarang mendistribusikan ulang untuk keperluan komersial tanpa izin.

---

<div align="center">
  <sub>Dibuat dengan ☕ — PengLon v0.1 Beta</sub>
</div>
