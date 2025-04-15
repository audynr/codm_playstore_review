# CODM Reviews 

Proyek ini bertujuan untuk memprediksi data teks menggunakan beberapa model machine learning. Data teks diperoleh melalui proses scraping, kemudian diproses dan dianalisis untuk keperluan prediksi.



```markdown
## 🗂️ Struktur Proyek

Berikut adalah struktur folder dan file yang ada dalam proyek ini:

```
├── data/                 # Folder output hasil scraping
├── scrapping_data.ipynb  # Notebook untuk scraping data dari sumber
├── main.ipynb            # Notebook utama untuk preprocessing dan prediksi
├── requirements.txt      # File daftar library yang dibutuhkan
└── README.md             # Dokumentasi proyek
```

Penjelasan:
- **data/**: Folder ini berisi data hasil scraping yang digunakan dalam analisis.
- **scrapping_data.ipynb**: Notebook ini digunakan untuk scraping data dari sumber yang ditentukan.
- **main.ipynb**: Notebook utama yang digunakan untuk melakukan preprocessing data, pelatihan model, dan melakukan prediksi.
- **requirements.txt**: File ini berisi daftar library dan versi yang dibutuhkan untuk menjalankan proyek ini.
- **README.md**: Dokumentasi proyek ini yang menjelaskan bagaimana cara menggunakan dan memahami kode ini.

```

## 📌 Alur Penggunaan

1. **Scraping Data**
   - Jalankan `scrapping_data.ipynb` untuk mengambil data dari sumber yang ditentukan.
   - Data hasil scraping akan otomatis disimpan dalam folder `data/`.

2. **Preprocessing & Prediksi**
   - Buka dan jalankan `main.ipynb` untuk melakukan preprocessing teks, pelatihan model, dan evaluasi hasil prediksi.

3. **Instalasi Dependensi**
   - Sebelum menjalankan notebook, pastikan semua dependensi terinstall dengan menjalankan perintah:
     ```bash
     pip install -r requirements.txt
     ```

## 🛠️ Teknologi & Library yang Digunakan

Library yang digunakan terdapat dalam `requirements.txt`, beberapa di antaranya:
- `pandas`
- `scikit-learn`
- `beautifulsoup4`
- `requests`
- `nltk`
- `tqdm`
- dan lainnya sesuai kebutuhan scraping dan machine learning

## 🧠 Model yang Digunakan

Model prediksi teks dalam proyek ini dapat berupa:
- XGBoost
- Random Forest
- SVM
- BiLSTM

## 📁 Output

- Semua hasil scraping disimpan di folder `data/`.
- Output lain seperti hasil evaluasi model bisa ditambahkan secara manual atau disimpan otomatis di notebook sesuai kebutuhan.

## 📌 Catatan

- Pastikan koneksi internet stabil saat melakukan scraping.
- Disarankan untuk menjalankan proyek ini di lingkungan virtual seperti `venv` atau `conda` environment agar dependensi tidak mengganggu project lain.
