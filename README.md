# money-tracker-sederhana
Aplikasi web sederhana untuk mencatat pemasukan dan pengeluaran pribadi. Dilengkapi ringkasan per bulan dan ekspor ke Excel (.xlsx). Data disimpan otomatis di browser (LocalStorage).
# 💰 Aplikasi Catatan Keuangan Pribadi

Aplikasi web sederhana untuk mencatat pemasukan dan pengeluaran harian. Dilengkapi dengan ringkasan saldo, rekap per bulan, serta fitur ekspor ke Microsoft Excel (.xlsx). Data tersimpan aman di localStorage browser sehingga tidak hilang meskipun halaman di-refresh.

[Screenshot Aplikasi] <img width="1280" height="720" alt="Screenshot 2026-07-05 205050" src="https://github.com/user-attachments/assets/ab74b495-7fe4-4995-8610-e0bbdca84a49" />
---

## ✨ Fitur Unggulan

- ✅ **Tambah Transaksi** – Input dengan tanggal, keterangan, jumlah, dan pilih jenis (Pemasukan / Pengeluaran).
- 📊 **Ringkasan Saldo Real-time** – Total saldo, total pemasukan, dan total pengeluaran langsung berubah setiap kali data bertambah.
- 📅 **Rekap per Bulan** – Menampilkan total pemasukan, pengeluaran, dan saldo untuk setiap bulan secara otomatis.
- 🔍 **Filter Data** – Tampilkan semua, hanya pemasukan, atau hanya pengeluaran.
- 💾 **Penyimpanan Lokal (LocalStorage)** – Data tetap tersimpan di browser, tidak hilang meskipun kamu menutup tab atau mematikan komputer.
- 📁 **Ekspor ke Excel (.xlsx)** – Download laporan keuangan dalam format tabel dengan kolom: Tanggal, Keterangan, Pemasukan, Pengeluaran (lengkap dengan baris TOTAL).

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** – Struktur halaman.
- **CSS3** – Styling modern dengan tampilan responsif (Grid & Flexbox).
- **JavaScript (Vanilla)** – Logika CRUD, filter, dan perhitungan.
- **SheetJS (xlsx)** – Library untuk mengekspor data ke format Excel.
- **LocalStorage** – Penyimpanan data sisi klien.

---

## 🚀 Cara Menjalankan Aplikasi

Karena ini adalah aplikasi web statis (Client-side), kamu bisa menjalankannya dengan 2 cara mudah:

### 1. Buka Langsung di Browser
- Download semua file (atau copy-paste kode) ke dalam satu folder.
- Klik 2 kali pada file `index.html`, maka akan terbuka otomatis di browser favoritmu.

### 2. Menggunakan Live Server (Direkomendasikan untuk Development)
Jika kamu pakai VS Code:
```bash
# Install ekstensi "Live Server" lalu klik kanan pada index.html > Open with Live Server
