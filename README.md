
readme_text = """# Proyek Akuisisi dan Manajemen Data

Mata kuliah : Data Acquisition  dan Manajemen Data
Nama        : Putu Intan Cahyanti Putri
NIM         : 2501010046
Tujuan      : Menyiapkan environment dan struktur proyek standar akuisisi data.

## Struktur Folder
- `data/raw`: data mentah hasil akuisisi (READ-ONLY)
- `data/interim`: hasil antara (cleaning, transformasi)
- `data/processed`: dataset final siap analisis
- `notebooks`: notebook praktikum
- `src`: script Python yang dapat digunakan ulang
- `docs`: data dictionary dan metadata
- `reports`: laporan kualitas data

## Cara Menjalankan Ulang
1. `pip install -r requirements.txt`
2. Jalankan notebook di folder `notebooks` secara berurutan.
"""

(ROOT / "README.md").write_text(readme_text, encoding="utf-8")
print("README.md berhasil dibuat!")

