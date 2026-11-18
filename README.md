# Preprocessing Teks Ulasan E-Commerce Berbahasa Indonesia

**Nama** : Muntasir
**NIM**  : 24146060
**GitHub** : https://github.com/muntasirdw46-sketch/Natural-Language-Preprocessing.git

## Deskripsi

Jupyter Notebook `preprocessing_ulasan_ecommerce.ipynb` untuk preprocessing
teks pada dataset ulasan e-commerce berbahasa Indonesia
[dipawidia/ecommerce-product-reviews-sentiment](https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment)
(kolom: `review`, `translate`, `sentimen`; 1 = positif, 0 = negatif).

Tahapan yang dicakup:

1. Memuat dataset memakai library `datasets`, lalu mengubahnya ke pandas.
2. Informasi dataset: jumlah data, kolom, tipe data, missing value, duplikat,
   dan distribusi label sentimen (tabel + grafik batang).
3. Preprocessing kolom `review`: case folding, cleaning (URL, mention/hashtag,
   angka, tanda baca, emoji, karakter khusus), tokenisasi, stopword removal
   (Sastrawi, kata negasi dipertahankan), dan stemming PySastrawi (dengan cache).
4. 10 contoh teks sebelum dan sesudah preprocessing.
5. Statistik dampak preprocessing (ukuran kosakata, rata-rata jumlah kata dan
   karakter, jumlah ulasan kosong setelahnya).
6. Laporan PDF otomatis (`Laporan_Preprocessing.pdf`) dengan reportlab.

## Cara Menjalankan

```bash
pip install datasets pandas matplotlib PySastrawi reportlab jupyter
jupyter notebook preprocessing_ulasan_ecommerce.ipynb
```

Jalankan seluruh sel dari atas ke bawah (Run All). Isi variabel `NAMA`,
`NIM`, dan `GITHUB_URL` pada sel konfigurasi identitas terlebih dahulu.
"# Natural-Language-Preprocessing" 
"# Natural-Language-Preprocessing" 
"# Natural-Language-Preprocessing" 
