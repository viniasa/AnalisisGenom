# Influenza Virus Genome Comparator

Web aplikasi untuk analisis perbandingan genom virus influenza menggunakan Multiple Sequence Alignment (ClustalW).

## Fitur
- Upload file FASTA untuk 3 jenis virus influenza
- Analisis Multiple Sequence Alignment
- Visualisasi hasil alignment
- Download hasil analisis

## Cara Penggunaan
1. Buka `index.html` di browser
2. Upload file FASTA untuk setiap virus
3. Klik tombol "Run" untuk memulai analisis
4. Lihat hasil dan download file hasil

## Tim Pengembang
**Kelompok 11 - Kelas 05**
1. Yasra Zhafirah (18222002)
2. Vini Putiasa (18222030)
3. Kerlyn Deslia Andeskar (18222090)
```

## 🔧 Perbaikan yang Dilakukan

1. **Masalah tombol Browse**: 
   - Menggunakan `flex-shrink: 0` untuk tombol browse
   - Mengurangi gap menjadi 8px
   - Mengubah padding tombol browse
   - Menambahkan `min-width: 0` pada input untuk mencegah overflow

2. **Struktur File**:
   - HTML terpisah di `index.html`
   - CSS terpisah di `css/style.css`
   - JavaScript terpisah di `js/script.js`
   - README untuk dokumentasi

3. **Peningkatan UX**:
   - Input file disembunyikan, menggunakan display input untuk nama file
   - Responsive design yang lebih baik
   - Validasi file yang lebih robust

## 🚀 Cara Deploy
1. Buat folder `influenza-genome-analyzer`
2. Buat subfolder `css` dan `js`
3. Simpan setiap file sesuai struktur di atas
4. Buka `index.html` di browser