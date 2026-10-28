# Proyek Akhir: Program Rekap dan Analisis Nilai Matematika Kelas

**Nama:** Angelita Juliana Siahaan  
**NIM:** 2225250112  
**Kelas:** 3B  
**Mata Kuliah:** Algoritma dan Pemrograman  

---

## 1. Deskripsi Proyek
Program berbasis konsol (terminal) Python yang dirancang untuk membantu guru matematika dalam membaca data nilai siswa dari file eksternal, memvalidasi rentang nilai (0-100), menghitung statistik dasar (rata-rata, nilai minimum, dan maksimum), menentukan status ketuntasan berdasarkan KKM, serta menyimpan laporan hasil rekapitulasi secara otomatis.

## 2. Fitur Wajib
- Membaca data nilai dari file teks eksternal (`data/nilai_contoh.txt`).
- Memvalidasi rentang nilai agar valid (0 s.d. 100).
- Menghitung statistik kelas (rata-rata, nilai minimum, nilai maksimum).
- Menentukan status ketuntasan siswa (Tuntas / Belum Tuntas).
- Menyimpan hasil laporan ringkas ke dalam file teks (`output/laporan.txt`).

## 3. Struktur Folder Proyek
```text
proyek-akhir-angelita/
├── README.md
├── proposal.md
├── .gitignore
├── data/
│   └── nilai_contoh.txt
├── src/
│   ├── __init__.py
│   ├── main.py
│   ├── data_io.py
│   ├── analisis.py
│   └── utilitas.py
├── tests/
│   └── test_case.md
└── output/
    └── .gitkeep
