# capstone-project2-purwadhika

## **Background**
Bangkok merupakan salah satu destinasi wisata terpopuler di dunia, menarik jutaan pengunjung setiap tahunnya. Kota ini menawarkan berbagai atraksi mulai dari kuil-kuil bersejarah, kehidupan malam yang dinamis, hingga pusat perbelanjaan yang modern. Airbnb, sebagai salah satu platform penyewaan jangka pendek terkemuka, telah menjadi pilihan utama bagi banyak wisatawan yang mencari pengalaman menginap yang unik dan nyaman di Bangkok.

Semakin populernya Airbnb, banyak pemilik properti di Bangkok yang melihat ini sebagai peluang untuk mendapatkan penghasilan tambahan. Mereka menawarkan berbagai jenis akomodasi, mulai dari kamar pribadi hingga seluruh rumah atau apartemen, yang tersebar di berbagai lingkungan kota. Melalui platform ini, para wisatawan dapat menemukan tempat tinggal yang sesuai dengan kebutuhan dan anggaran mereka, sementara pemilik properti dapat memanfaatkan aset mereka dengan lebih efektif.

Analisis dataset Airbnb ini memberikan wawasan yang berharga tentang pasar sewa jangka pendek di kota Bangkok. Dengan analisis data seperti harga, lokasi, jenis properti, ulasan pelanggan, dan kinerja host, kita dapat mengidentifikasi tren dan pola yang dapat membantu pemilik properti dan pengelola dalam membuat keputusan yang lebih baik.

## **Problem**
1. Identifikasi Lokasi Strategis

Menentukan lokasi strategis adalah kunci untuk mengoptimalkan pendapatan dan tingkat hunian. Perusahaan perlu menemukan lingkungan dan kawasan di Bangkok yang memiliki permintaan tinggi dan harga sewa yang menguntungkan. Tanpa data yang akurat, perusahaan berisiko berinvestasi di area yang kurang menguntungkan, yang dapat berdampak negatif pada ROI.

2. Penetapan Harga

Untuk memaksimalkan pendapatan, perusahaan harus menentukan strategi penetapan harga yang optimal berdasarkan jenis properti dan lokasinya. Tantangannya adalah outliers pada kolom `price` dan `number_of_reviews` yang dapat mendistorsi analisis harga rata-rata dan median. Tanpa strategi penetapan harga yang jelas perusahaan berisiko menetapkan harga yang terlalu tinggi atau terlalu rendah, yang dapat mengakibatkan kehilangan pelanggan potensial atau pendapatan yang tidak maksimal.

 3. Kinerja Host

Variasi besar dalam jumlah listing yang dimiliki oleh host dan ketidakseimbangan jumlah ulasan per bulan menimbulkan tantangan dalam mengevaluasi kinerja host secara adil dan efektif. Perusahaan perlu mengidentifikasi host dengan kinerja terbaik berdasarkan jumlah ulasan dan ratingnya. Tanpa evaluasi yang tepat, sulit untuk memberikan rekomendasi yang dapat membantu host lain meningkatkan kinerjanya yang pada akhirnya dapat mempengaruhi reputasi dan keuntungan perusahaan.

4. Kepuasan Pelanggan

Kepuasan pelanggan adalah faktor kunci dalam mempertahankan tingkat hunian yang tinggi dan mendapatkan ulasan positif. Tantangan yang dihadapi adalah nilai yang hilang pada kolom `reviews_per_month` dan `last_review` yang mengganggu akurasi analisis. Tanpa memahami dengan jelas apa yang membuat pelanggan puas atau tidak, ini berisiko kehilangan pelanggan dan mendapatkan ulasan negatif.

5. Analisis Tren dan Musiman

Mengidentifikasi pola musiman dalam hunian dan harga adalah penting untuk mengoptimalkan strategi pemasaran. Perusahaan perlu menyesuaikan harga dan promosi berdasarkan tren musiman untuk memaksimalkan pendapatan. Namun, data yang tidak lengkap dan tidak konsisten dapat menghambat kemampuan identifikasi pola dengan akurat. Tanpa analisis tren dan musiman yang tepat, perusahaan berisiko kehilangan peluang untuk meningkatkan pendapatan selama periode puncak dan tidak efisien dalam memanfaatkan sumber daya yang ada.

## **Tujuan dari analisis ini meliputi:**

1. Mengidentifikasi Lokasi Strategis:
   Menemukan lingkungan dan kawasan di Bangkok yang memiliki permintaan tinggi dan harga sewa yang menguntungkan.
2. Strategi Penetapan Harga:
   Menentukan strategi penetapan harga berdasarkan jenis properti dan lokasi untuk memaksimalkan pendapatan.
3. Analisis Kinerja Host:
   Mengevaluasi kinerja host berdasarkan jumlah ulasan dan rating untuk mengidentifikasi praktik terbaik.
4. Kepuasan Pelanggan:
   Memahami faktor-faktor yang mempengaruhi kepuasan pelanggan berdasarkan ulasan untuk meningkatkan layanan dan fasilitas.
5. Analisis Tren dan Musiman:
   Mengidentifikasi pola musiman dalam hunian dan harga untuk mengoptimalkan strategi pemasaran.

### **Steps**

A. Data Cleaning:
   - Memastikan semua kolom diformat dengan benar.
   - Menangani nilai yang hilang dengan mengisi atau menghapus data yang tidak lengkap.
   - Mengidentifikasi dan menangani outliers.

B. Exploratory Data Analysis (EDA):
   - Membuat statistik ringkasan untuk setiap kolom.
   - Visualisasi distribusi data dengan grafik dan plot.

C. Analysis:
   - Mengidentifikasi Lokasi Strategis:
     - Analisis harga dan permintaan di berbagai lingkungan untuk menemukan lokasi strategis.
   - Strategi Penetapan Harga:
     - Menentukan harga optimal berdasarkan jenis properti dan lokasi.
   - Analisis Kinerja Host:
     - Mengevaluasi host berdasarkan jumlah ulasan dan rating.
   - Kepuasan Pelanggan:
     - Menganalisis ulasan untuk memahami faktor kepuasan pelanggan.
   - Analisis Tren dan Musiman:
     - Mengidentifikasi pola musiman dalam harga dan hunian.
