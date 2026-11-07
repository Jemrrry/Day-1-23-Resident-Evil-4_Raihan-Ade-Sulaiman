# 📚 Dokumentasi Kegiatan Workshop - EXPECTIK 2026
### Jurusan Teknik Informatika dan Komputer (TIK) — Politeknik Negeri Jakarta

![GitHub repo size](https://img.shields.io/github/repo-size/username/repository?color=blue&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/username/repository?style=flat-square)
![Visibility Public](https://img.shields.io/badge/Visibility-Public-green?style=flat-square)

---

## 👤 Identitas Peserta

| Keterangan | Data Peserta |
| :--- | :--- |
| **Nama Lengkap** | Raihan Ade Sulaiman |
| **NIM** | 2607441044 |
| **Program Studi** | Rekayasa Keamanan Siber |
| **Kelompok** | 23 Resident Evil 4 |
| **Mentor Kelompok** | Kak Awa & Bang Nizar |
| **Akun GitHub** | [@Jemrrry]https://github.com/Jemrrry |

---

## 📖 Deskripsi Singkat Repository

Repository ini dibuat sebagai wadah penyimpanan publik (*public repository*) dan pusat dokumentasi resmi selama mengikuti kegiatan **Workshop EXPECTIK 2026** yang diselenggarakan oleh Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) Politeknik Negeri Jakarta.

Di dalam repository ini tersimpan seluruh rangkuman materi pembelajaran, catatan penting, file pendukung/praktik, serta dokumentasi kegiatan workshop yang telah disusun secara sistematis, rapi, dan terstruktur.

---

## 🎯 Tujuan & Kegunaan Repository

Berdasarkan ketentuan Misi Proyek Workshop EXPECTIK 2026, repository ini memiliki tujuan dan kegunaan sebagai berikut:

1. **Sarana Penyimpanan & Pengelolaan Daring**: Memanfaatkan platform GitHub sebagai media penyimpanan berbasis *cloud* dan pengelolaan dokumentasi proyek secara daring.
2. **Pengelolaan Repository Public**: Melatih kemampuan membuat, mengonfigurasi, dan mengelola repository dengan visibilitas *Public* agar dapat diakses serta dinilai secara terbuka.
3. **Membiasakan Dokumentasi Teknis**: Membiasakan peserta untuk selalu mencatat dan mendokumentasikan setiap proses kegiatan, materi pembelajaran, serta hasil eksperimen teknis.
4. **Manajemen Berkas Terstruktur**: Meningkatkan keahlian dalam menyusun file, aset, dan catatan materi secara rapi dan hierarkis.
5. **Pemanfaatan `README.md`**: Mengasah keterampilan dalam menyusun berkas `README.md` dengan format Markdown yang profesional dan informatif sebagai wajah utama proyek.

---

## ℹ️ Informasi Kegiatan Workshop

- **Nama Misi**: Day 1 - Proyek Workshop-26 (Week 1)
- **Kegiatan**: Workshop EXPECTIK 2026
- **Penyelenggara**: Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) PNJ
- **Waktu Pelaksanaan**: Sabtu, 7 November 2026
- **Tenggat Pengumpulan**: Sabtu, 7 November 2026, Pukul 23.59 WIB
- **Platform Pengumpulan**: Website Resmi GULTIK / EXPECTIK HIMATIK PNJ

---

## 📝 Dokumentasi Kegiatan & Rangkuman Materi

### 1. Materi / Topik yang Disampaikan
Selama kegiatan workshop berlangsung, materi yang dipelajari mencakup:
* **Pengenalan Version Control System (VCS) & Git**:
  - Konsep dasar *version control* dan alasan pentingnya pelacakan perubahan kode.
  - Perbedaan Git (*local tool*) dan GitHub (*cloud hosting platform*).
* **Konfigurasi dan Perintah Dasar Git**:
  - Inisialisasi repositori (`git init`).
  - Menyiapkan *staging area* (`git add .`).
  - Menyimpan *snapshot* riwayat perubahan (`git commit -m "pesan"`).
  - Menghubungkan repositori lokal ke GitHub (`git remote add origin <URL>`).
  - Melakukan sinkronisasi ke server (`git push -u origin main`).
* **Pengelolaan Repository GitHub**:
  - Pembuatan repositori baru dengan visibilitas *Public*.
  - Pembuatan dan formatting berkas `README.md` menggunakan sintaks Markdown.
* **Manajemen Proyek dan Kolaborasi Digital**:
  - Struktur direktori proyek yang rapi.
  - Dokumentasi pembelajaran yang berkelanjutan (*continuous learning*).

---

### 2. Catatan & Rangkuman Materi Pembelajaran

#### A. Alur Kerja Git (Git Workflow)
```
Working Directory  --->  Staging Area  --->  Local Repository  --->  Remote (GitHub)
   (Edit File)             (git add)           (git commit)             (git push)
```

#### B. Cheatsheet Perintah Dasar Git
```bash
# 1. Konfigurasi identitas (jika baru pertama kali)
git config --global user.name "Nama Lengkap"
git config --global user.email "email@mahasiswa.pnj.ac.id"

# 2. Inisialisasi repository baru di folder lokal
git init

# 3. Menambahkan file ke staging area
git add .

# 4. Melakukan commit perubahan
git commit -m "feat: inisialisasi dokumentasi workshop expectik day 1"

# 5. Mengarahkan ke branch utama (main)
git branch -M main

# 6. Menghubungkan remote GitHub
git remote add origin https://github.com/[username]/[nama-repo].git

# 7. Mengunggah file ke GitHub
git push -u origin main
```

---

### 3. Poin-Poin Penting & Pengetahuan Baru yang Dipelajari

* **Pentingnya Visibilitas Publik**: Memahami bahwa repository publik memudahkan proses kolaborasi terbuka, penilaian tugas oleh panitia/dosen, serta membangun portofolio digital yang kredibel sejak awal masa perkuliahan.
* **Standar Penulisan `README.md`**: File `README.md` adalah dokumen pertama yang dilihat oleh pengunjung repository. Menggunakan format Markdown yang terstruktur (heading, list, table, blockquote, code blocks) membuat dokumentasi mudah dipahami dan profesional.
* **Disiplin Pencatatan**: Mendokumentasikan materi segera setelah sesi pembelajaran sangat membantu retensi materi dan memudahkan referensi di masa depan.
* **Pencegahan Human Error**: Memastikan URL repository yang dikumpulkan valid dan dapat dibuka dalam mode penyamaran (*incognito*) untuk memverifikasi hak akses publik.

---

## 📁 Struktur Direktori Repository

```text
.
├── README.md                  # Dokumentasi utama repository (Identitas, tujuan, rangkuman materi)
├── catatan/                   # Kumpulan catatan detail dan ringkasan per sesi
│   └── catatan-workshop.md    # Catatan mendalam materi workshop
├── materi/                    # File materi pendukung, slide, atau modul workshop
│   └── .gitkeep
└── dokumentasi/               # Bukti visual kegiatan (screenshot sesi workshop / hasil praktik)
    └── .gitkeep
```

---

## 📷 Dokumentasi Visual / Bukti Pelaksanaan

> *Catatan: Tambahkan screenshot bukti keikutsertaan workshop atau hasil praktik di bawah ini.*

| Dokumentasi Sesi Workshop | Dokumentasi Day 1 |
| :---: | :---: |
| <img width="900" height="1600" alt="WhatsApp Image 2026-11-07 at 18 07 49" src="https://github.com/user-attachments/assets/f504d3fd-1df4-4383-933f-662d397b2f7d" /> | <img width="960" height="1280" alt="WhatsApp Image 2026-11-07 at 17 30 05" src="https://github.com/user-attachments/assets/eef74cf4-5261-4e9b-a77a-69d2a2acea90" /> |

---
---

<p align="center">
  Dibuat dengan dedikasi untuk kegiatan <strong>EXPECTIK 2026</strong><br>
  <strong>HIMATIK PNJ — Politeknik Negeri Jakarta</strong>
</p>
