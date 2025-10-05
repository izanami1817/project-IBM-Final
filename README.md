# project-IBM-Final
# Analisis Sentimen Berbasis Aspek pada Ulasan Produk Smartphone

## Gambaran Umum Proyek
(" disini saya menganalisis sentimen sorang di aplikasi tokipedia dimana rpoduk yang dinalaisa yakni adalah handpohone dimulai dari pengambnilan data, cleaning hingga tahap analisis menggunakan genertaive ai dari IBM, project ini bertujuan untuk mengetahui kekurangan serta kelebihan dalam produk yersebut")

---

## Dataset
Dataset yang digunakan adalah ulasan produk dari Tokopedia yang diambil dari Kaggle.
* **Link Dataset:** [Tokopedia Product Reviews](https://www.kaggle.com/datasets/farhan999/tokopedia-product-reviews)
* **Catatan:** Data difilter untuk hanya menganalisis ulasan dari kategori "handphone".

---

## Temuan Utama & Insight
Berdasarkan hasil analisis menggunakan AI, ditemukan beberapa insight utama:

### Aspek yang Paling Disukai Pelanggan (Sentimen Positif)
(<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5aa27e25-7bc5-4a38-820a-72e06f292084" />
)

**Penjelasan:**
(" insight utama dari grafik ini adalah bahwa pengalaman berbelanja yang lancar dan tepercaya (dari segi pengiriman dan komunikasi) adalah pendorong kepuasan pelanggan yang sama kuatnya dengan kualitas produk itu sendiri")

### Aspek yang Paling Dikeluhkan Pelanggan (Sentimen Negatif)
()

**Penjelasan:**
(" Grafik ini menunjukkan keluhan utama pelanggan, yang sebagian besar berpusat pada masalah produk itu sendiri. Aspek seperti "Fungsi", "Ori" (keaslian), dan "Kendala" berada di peringkat atas, yang mengindikasikan bahwa pelanggan seringkali merasa kecewa karena produk tidak berfungsi seperti yang diharapkan atau meragukan originalitasnya. Temuan ini menyarankan perlunya peningkatan kontrol kualitas produk secara ketat sebelum barang dikirim ke pembeli.")

---

## Penjelasan Dukungan AI
Proyek ini menggunakan model AI Large Language Model (LLM) dari platform Hugging Face untuk melakukan tugas **Analisis Sentimen Berbasis Aspek**.

Peran AI dalam proyek ini adalah:
1.  **Mengidentifikasi Aspek:** AI secara otomatis membaca setiap ulasan untuk menemukan aspek-aspek yang dibicarakan (misalnya: Baterai, Layar, Pengiriman).
2.  **Menentukan Sentimen:** Untuk setiap aspek yang ditemukan, AI menentukan apakah sentimen pelanggan terhadap aspek tersebut Positif, Negatif, atau Netral.
3.  **Memberikan Output Terstruktur (JSON):** AI diinstruksikan untuk memberikan output dalam format JSON yang konsisten, sehingga memudahkan proses pengolahan data dan visualisasi.

---

## Rekomendasi Bisnis
Berdasarkan temuan di atas, berikut adalah rekomendasi yang bisa dijalankan:
1.  **Untuk Tim Marketing:** Jadikan "Pengiriman Cepat" dan "Packing Aman" sebagai nilai jual utama dalam kampanye pemasaran.
2.  **Untuk Tim Operasional:** Lakukan pengecekan kualitas (Quality Control) yang lebih ketat untuk memastikan **fungsi** produk berjalan baik dan verifikasi **keaslian** produk dari pemasok.
