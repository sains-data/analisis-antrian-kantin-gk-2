# 🎉 Analisis Sistem Antrian Kantin GKU‑2 (ITERA)
---

## 🔥 Tentang Proyek

Proyek ini menganalisis **kinerja sistem antrian di Kantin GKU‑2 ITERA** menggunakan pendekatan **teori antrian (M/M/1 & M/M/2)** untuk memahami pola kedatangan pelanggan, waktu pelayanan, dan dampaknya terhadap durasi tunggu. 🚀

Tujuannya? **Memberikan rekomendasi operasional berbasis data** untuk mengurangi penumpukan antrian dan meningkatkan kenyamanan pelanggan.

---

## 🌟 Ringkasan Temuan Utama

| Temuan                     | Detail                                                            |
| -------------------------- | ----------------------------------------------------------------- |
| Total pelanggan            | **398 pelanggan** 👥                                              |
| Kedatangan rata‑rata       | **39.8 pelanggan/jam** ⏱️                                         |
| Kecepatan pelayanan        | **33.7 pelanggan/jam** per kasir 🍽️                              |
| Hasil skenario **1 kasir** | ❌ **Overload (ρ = 118.1%)** — antrian tambah tanpa batas          |
| Hasil skenario **2 kasir** | ✅ **Stabil (ρ = 59.05%)** — rata-rata waktu tunggu **≈ 57 detik** |

📌 **Kesimpulan singkat:** Menambah jumlah kasir dari 1 → 2 menghasilkan peningkatan performa drastis.

---

## 🧠 Metodologi

🔹 Observasi langsung 10 jam pada jam operasional kantin (07:00 – 16:59)
🔹 Pencatatan data menggunakan tally counter & spreadsheet
🔹 Pemodelan matematis menggunakan **M/M/1 & M/M/2**
🔹 Evaluasi performa sistem menggunakan parameter antrian: `ρ`, `P0`, `Wq`, `Ws`, `Lq`, `Ls`

---

## 💡 Rekomendasi Operasional

| Strategi                                    | Dampak                              |
| ------------------------------------------- | ----------------------------------- |
| Menjalankan **2 kasir pada jam sibuk**      | ⏳ Waktu tunggu < 1 menit            |
| Memisahkan **jalur express** (minuman roti) | ⚡ Mempercepat transaksi sederhana   |
| Memisahkan **pembayaran digital vs tunai**  | 💳 Mengurangi bottleneck pembayaran |
| Evaluasi berkala                            | 📈 Menjaga efisiensi jangka panjang |

---

## 🗂️ Struktur Berkas Proyek

```
📦 Analisis-Antrian-GKU2
 ├─ Poster_8_RA
 ├─ Video_8_RA
 ├─ Laporan_8_RA
 ├─ codeR_8_RA
 └─ Dataset/
      ├─ data_observasi.csv
      └─ ...
```

Setiap artefak berfungsi sebagai bukti validasi dan pelengkap analisis.

---

## 🚀 Quick Access

| Resource        | Tipe     | Keterangan                  |
| --------------- | -------- | --------------------------- |
| 📄 Poster_8_RA  | Poster   | Ringkasan visual penelitian |
| 🎬 Video_8_RA   | Video    | Presentasi hasil analisis   |
| 📘 Laporan_8_RA | PDF      | Dokumen laporan lengkap     |
| 🔢 codeR_8_RA   | R Script | Kode analisis statistik     |
| 📂 Dataset      | Folder   | Data mentah observasi       |

> Semua berkas tersedia di repository ini. Kamu tinggal klik pada nama file untuk membuka. ✨

---

## 🏆 Mengapa Proyek Ini Penting?

✔ Meningkatkan kenyamanan pelanggan kantin 💺
✔ Mengurangi penumpukan antrian saat jam sibuk 🔄
✔ Memberikan dasar keputusan berbasis data untuk manajemen 🙌
✔ Contoh nyata penerapan **Sains Data + Pemodelan Stokastik** di lingkungan kampus 📚

---

## 👥 Tim Proyek

📌 Disusun untuk Tugas Besar **Pemodelan Stokastik** — Program Studi Sains Data, Institut Teknologi Sumatera (ITERA)
📅 Tahun 2025

---

## ❤️ Penutup

Terima kasih telah mengunjungi repository ini! Jika proyek ini bermanfaat:
⭐ **Berikan star di GitHub** — sangat berarti!
💬 Kritik & saran selalu diterima untuk pengembangan lanjutan.

---
