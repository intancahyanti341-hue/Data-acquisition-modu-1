# Data-acquisition-modul-1
readme = """# Proyek Akuisisi dan Manajemen Data

Mata kuliah : BIFP-243 Akuisisi dan Manajemen Data
Nama / NIM  : ....................
Tujuan      : ....................

## Struktur Folder

- data/raw       : data mentah hasil akuisisi (READ-ONLY)
- data/interim   : hasil antara (cleaning, transformasi)
- data/processed : dataset final siap analisis
- notebooks      : notebook praktikum
- src            : script Python yang dapat digunakan ulang
- docs           : data dictionary dan metadata
- reports        : laporan kualitas data

## Cara Menjalankan Ulang

1. Install Python 3.11 atau versi yang lebih baru.
2. Install library yang diperlukan.
3. Jalankan notebook di folder notebooks secara berurutan.
"""

(ROOT / "README.md").write_text(readme, encoding="utf-8")

print((ROOT / "README.md").read_text(encoding="utf-8"))
Jangan lupa mengganti:

Nama  : PUTU INTAN CAHYANTI PUTRI
Nim   :2501010046 (E)
