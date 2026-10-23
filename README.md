# Tugas Pengembangan Aplikasi Web

Kumpulan tugas mata kuliah **Pengembangan Aplikasi Web**, Program Studi Teknik Informatika, Institut Teknologi Sumatera.

| | |
|---|---|
| **Nama** | Aryo Fajar Pratomo |
| **NIM** | 124140012 |
| **Kelas** | RA |

## Daftar Tugas

| Tugas | Topik | Folder |
|---|---|---|
| Tugas 2 | Struktur Semantik HTML5 | [`Task2-PAW`](Task2-PAW) |
| Tugas 3 | Tabel, Formulir, Layout dan Web Media | [`Task3-PAW`](Task3-PAW) |

---

### Tugas 2 – Struktur Semantik HTML5

Website profil **Institut Teknologi Sumatera (ITERA)** yang terdiri dari dua halaman:

- `index.html`: halaman utama berisi hero, tentang ITERA, fakultas, dan kontak kampus.
- `berita.html`: halaman berita kampus berisi berita utama, daftar berita, dan kategori.

Fokus tugas ini adalah memperbaiki struktur HTML agar semantik dan valid:

- menutup tag `<div>` dan `<section>` yang belum tertutup,
- menempatkan `<footer>` sejajar dengan `<main>`,
- menyamakan struktur kedua halaman,
- memvalidasi hasilnya dengan W3C Validator.

📁 [Lihat folder Task2-PAW](Task2-PAW)

---

### Tugas 3 – Tabel, Formulir, Layout dan Web Media

Website pendaftaran **Workshop Web Development 2026** yang terdiri dari dua halaman:

- `index.html`: halaman pendaftaran dengan form `method="GET"`.
- `detail.html`: halaman detail informasi pendaftar berisi data dummy dan desain query string.

Desain kedua halaman menggunakan CSS (Grid, Flexbox, box transparan, tabel, dan form) dengan lebih dari 3 jenis selector.

<img src="Task3-PAW/screenshots/01-halaman-pendaftaran.png" width="600" alt="Tampilan Tugas 3">

📁 [Lihat folder Task3-PAW](Task3-PAW)

---

## Struktur Repository

```
Tugas_PAW/
├── Task2-PAW/
│   ├── Image/
│   ├── index.html
│   ├── berita.html
│   ├── Tugas 2 PemWeb.pdf
│   └── README.md
├── Task3-PAW/
│   ├── screenshots/
│   ├── index.html
│   ├── detail.html
│   ├── style.css
│   ├── Task3-PAW.pdf
│   └── README.md
└── README.md
```

## Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/AryoFajar/Tugas_PAW.git
   ```
2. Masuk ke folder tugas yang ingin dibuka, misalnya `Task3-PAW`.
3. Buka `index.html` di browser, atau gunakan ekstensi **Live Server** di VS Code.

## Teknologi

- HTML5
- CSS3
