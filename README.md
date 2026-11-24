# UAS Pemrograman - Pengolahan Data Sondir

## Identitas

- **Nama:** aulce-14
- **NIM:** D101221087
- **Prodi:** Teknik Sipil, Universitas Tanjungpura
- **Repo:** [uas-pemrog-d101221087](https://github.com/aulce-14/uas-pemrog-d101221087)

## Ringkasan Proyek

Proyek ini merupakan implementasi pengolahan data uji penetrasi konus statis (sondir/CPT) menggunakan Python dan Jupyter Notebook. Analisis mengacu pada SNI 2827:2008, **Cara Uji Penetrasi Lapangan dengan Alat Sondir**.

Data yang digunakan berasal dari titik sondir S-1 di Sukamantri, Pasar Kemis, Tangerang-Banten, dengan kedalaman pengujian sekitar 0–8,6 meter. Notebook menghitung parameter geoteknik utama, antara lain:

- Perlawanan penetrasi konus (`qc`)
- Hambatan lekat/frictional resistance
- Geseran lokal (`fs`)
- Jumlah hambatan pelekat (`Tf`)
- Rasio gesekan (`FR`)

Selain itu, proyek melakukan Exploratory Data Analysis (EDA), klasifikasi konsistensi dan estimasi jenis tanah, penyusunan stratigrafi ringkas, serta pembuatan profil grafis sondir.

## Struktur Repository

- `data/` — berisi data sondir mentah dan data hasil pengolahan.
- `notebooks/` — berisi notebook analisis pengolahan data sondir.
- `output/` — berisi grafik profil sondir hasil visualisasi.

## Cara Menjalankan

1. Pastikan Python dan Jupyter Notebook telah tersedia.
2. Instal pustaka yang diperlukan:
   ```bash
   pip install pandas numpy matplotlib
   ```
3. Jalankan notebook:
   ```bash
   jupyter notebook notebooks/pengolahan_data_sondir_sni_2827_2008.ipynb
   ```
