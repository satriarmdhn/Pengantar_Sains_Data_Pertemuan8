# Pertemuan 8 - Pengantar Sains Data

Repository ini berisi praktik **Regresi Linear Sederhana** menggunakan Python di Google Colab pada **Pertemuan 8** mata kuliah Pengantar Sains Data.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satriarmdhn/Pengantar_Sains_Data_Pertemuan8/blob/main/Regresi_Linear_Sederhana.ipynb)

## Files

- **Regresi_Linear_Sederhana.ipynb**: notebook hasil praktik (kode dan output)

## Ringkasan Praktik

Studi kasus: hubungan antara **jam belajar** (variabel X) dan **nilai ujian** (variabel Y) pada 60 data simulasi.

Alur kerja di notebook:

1. Membuat dataset simulasi (`numpy`, `pandas`, seed 42)
2. Eksplorasi data: `head()`, `shape`, cek missing value, `describe()`
3. Scatter plot jam belajar vs nilai ujian
4. Membagi data latih dan data uji (80:20)
5. Melatih model `LinearRegression` dari scikit-learn
6. Visualisasi garis regresi
7. Evaluasi model dengan MAE, RMSE, dan R²

## Hasil

Persamaan model:

```
nilai_prediksi = 34.524 + 4.933 x jam_belajar
```

| Metrik | Nilai |
| ------ | ----- |
| MAE    | 4.730 |
| RMSE   | 5.239 |
| R²     | 0.804 |

Setiap tambahan 1 jam belajar menaikkan prediksi nilai ujian sekitar 4.9 poin. Model menjelaskan sekitar 80% variasi nilai pada data uji.

## Library

`numpy`, `pandas`, `matplotlib`, `scikit-learn`

## Author

**Satria Ramadhani (20264920010)** / Statistika - Data Science

Matana University

### Terima kasih
