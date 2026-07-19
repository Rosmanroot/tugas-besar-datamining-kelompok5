Tugas Besar Data Mining: Market Basket Analysis Time Laundry

Repositori ini berisi implementasi Market Basket Analysis untuk mengidentifikasi pola hubungan antar layanan pada Time Laundry menggunakan Algoritma Apriori.

Penerapan Market Basket Analysis Menggunakan Algoritma Apriori untuk Menentukan Strategi Bundling Layanan pada Time Laundry.

Anggota Kelompok & NIM

Afifah Rahmani  714230026
Nurfanis Rosman  714230022
Efendi Sugiantoro  714230018
Hadzik Sofyan 714230019

Penelitian ini bertujuan untuk membantu pengelola Time Laundry dalam memahami pola perilaku konsumen melalui data transaksi. 
Dengan menggunakan metode Market Basket Analysis dan algoritma Apriori, penelitian ini mengidentifikasi keterkaitan antar layanan untuk 
merumuskan strategi penggabungan layanan (bundling) yang efektif guna meningkatkan volume transaksi

Dataset bersumber dari catatan transaksi pelanggan Time Laundry yang mencakup 273 catatan transaksi dan 19 varian layanan.

Proses pengolahan data mengikuti metodologi Knowledge Discovery in Database (KDD) yang meliputi:  
Data Selection: Memilih atribut yang relevan untuk analisis transaksi.  
Data Cleaning: Penanganan nilai yang hilang, deteksi duplikasi, dan penyeragaman nomenklatur layanan.  
Data Transformation: Mengubah tabel transaksi menjadi format transaction basket menggunakan one-hot encoding (format biner 0 dan 1).

Algoritma yang DigunakanAlgoritma: Apriori.  Parameter:Minimum Support: 4%.  Minimum Confidence: 30%.

Evaluasi & HasilHasil: Ditemukan 9 frequent itemset yang signifikan.  
Aturan Asosiasi:Aturan Cuci Kering → Setrika memiliki confidence tertinggi (100%).  
Aturan Setrika, Sprei → Cuci Kering memiliki nilai lift sebesar 3,38, menandakan asosiasi yang sangat kuat.  
Kesimpulan: Algoritma Apriori berhasil mengidentifikasi pola yang dapat menjadi landasan strategis untuk bundling layanan dan cross-selling.
