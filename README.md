# Judul Project
Penerapan statistik deskriptif dan statistik inferensial untuk meningkatkan tingkat retensi pengguna jasa pengiriman jasa makanan di Bangalore

## Repository Outline
- clean_df.xlsx - Dataset yang sudah dibersihkan dalam bentuk excel.
- onlinedeliverydata.csv - Dataset yang akan diolah dan analisis.
- P0M1_dwi-adhi_dataset.csv - Dataset yang sudah dibersihkan dalam bentuk csv.
- P0M1_dwi-adhi.ipynb - Notebook yang berisi pengolahan dan analisis data.

## Problem Background
Saya adalah seorang **Data Analyst** di perusahaan jasa pengiriman makanan yang berbasis di Bangalore. Perusahaan saat ini menghadapi **penurunan jumlah pengguna aktif**, terutama dalam hal **retensi pelanggan**.

Tim marketing memperkirakan tingkat retensi pengguna saat ini sekitar **60%**, dan perusahaan kekurangan referensi maupun strategi untuk mempertahankan pelanggan agar terus menggunakan layanan.

Sebagai data analyst, saya ditugaskan untuk:
- Menganalisis pola perilaku pengguna
- Mengidentifikasi faktor-faktor yang mempengaruhi keputusan pengguna untuk tetap menggunakan layanan
- Memberikan rekomendasi berbasis data untuk meningkatkan tingkat retensi pengguna

## SMART and Problem Statement
Specific: Meningkatkan tingkat retensi pengguna jasa pengiriman makanan dengan cara meningkatkan faktor-faktor yang mempengaruhi kemauan user menggunakan jasa tersebut.

Measurable: Berhasil meningkatkan tingkat retensi user sebesar 70%

Achievable: Mengetahui faktor-faktor yang mempengaruhi user menggunakan jasa pengiriman makanan.

Relevant: Peningkatan tingkat retensi dapat diartikan pengguna lebih bersedia menggunakan jasa yang pada gilirannya meningkatkan pendapatan perusahaan.

Time-bound: Proses analisis dan visualisasi data dilakukan selama 2 minggu hari kerja.

Problem statement: Perusahaan mengalami penurunan pengunaan jasa pengiriman makan. Tim marketing mengestimasikan tingak retensi user sebesar 60%. Selain itu perusahaan kekurangan refensi agar user tetap menggunakan jasa. Saya sebagai data analyst yang berkerja diperusahaan pengiriman makanan di Bangalore ditugasakan meningkatkan retensi user.


## Project Output
Output project ini berupa Tableau dashboard dari analisis jasa pengiriman.

## Data
Dataset ini terdiri dari 388 baris dan 55 kolom. 
Tipe data tiap kolom dibagi menjadi:
- 49 string 
- 3 integer
- 2 float
- 1 boolean

## Method
- Statistik Dekriptif
- Statistik Inferensial (Chi-squared test)

## Penjabaran Masalah
Berikut adalah penjabaran masalah yang akan di analisa:
1. Kapan saja customer menggunkan jasa untuk memesan makanan?
2. Umur customer yang akan menggunakan jasa lagi?
3. Perbandingan gender customer yang akan menggunakan jasa lagi?
4. Pekerjaan apa saja user yang memesan makanan?
5. Faktor apa saja yang mempengaruhi user menggunakan jasa pengiriman makanan lagi?

## Analisis dan Insight
1. Kapan saja customer menggunakan jasa untuk memesan makanan?
  Temuan:
    - Proporsi sarapan siang (brunch) sebanyak 38 (17.2%)
    - Proporsi makan siang sebanyak 71 (32.1%)
    - Proporsi makan malam sebanyak 44 (19.9%)
    - Proporsi snack sebanyak 68 (30.8%)

  Insight:
    - Customer paling sering menggunakan aplikasi di jam makan siang.
    - Penggunaan aplikasi paling jarang terjadi saat sarapan.
    - Proporsi pemesanan snack cukup tinggi, hampir mendekati waktu makan utama.
  
2. Umur customer yang akan menggunakan jasa lagi?
  Temuan:
    - Rata-rata umur: 24.28 tahun
    - Median: 24 tahun
    - Modus: 23 tahun

  Insight:
    - Sebaran umur cenderung simetris, didominasi oleh usia muda (sekitar 20–25 tahun).ng.
    - Hal ini menunjukkan bahwa mayoritas pengguna aktif berasal dari kelompok usia muda, yang lebih akrab dengan layanan online food delivery.

3. Bagaimana perbandingan gender customer yang akan menggunakan jasa lagi?
  Temuan:
    - Laki-laki: 129 pengguna
    - Perempuan: 92 pengguna

  Insight:
    - Pengguna laki-laki lebih banyak dibanding perempuan.
    - Hal ini bisa disebabkan oleh faktor aktivitas di luar rumah atau kebiasaan memesan makanan secara online yang lebih tinggi pada laki-laki.
4. Pekerjaan apa saja user yang memesan makanan?
  Temuan:
    - Pengguna terbanyak adalah mahasiswa.
    - Pengguna kedua terbanyak adalah karyawan.
    - Pengguna paling sedikit adalah ibu rumah tangga.
  Insight:
    - Aplikasi lebih sering digunakan oleh segmen muda dan produktif, yang memiliki keterbatasan waktu untuk memasak.
    - Potensi promosi dapat difokuskan ke mahasiswa dan pekerja kantoran.
5. Faktor apa saja yang mempengaruhi user menggunakan jasa pengiriman makanan lagi?
  Temuan:
  ['marital_status',
 'occupation',
 'monthly_income',
 'preference(p2)',
 'ease_and_convenient',
 'time_saving',
 'more_restaurant_choices',
 'easy_payment_option',
 'more_offers_and_discount',
 'good_food_quality',
 'good_tracking_system',
 'self_cooking',
 'health_concern',
 'late_delivery',
 'bad_past_experience',
 'unavailability',
 'unaffordable',
 'delay_of_delivery_person_picking_up_food',
 'maximum_wait_time',
 'less_delivery_time',
 'number_of_calls',
 'politeness']

## Kesimpulan

Kesimpulan yang diperoleh dari analisis ini adalah bahwa customer yang berpotensi menggunakan aplikasi kembali cenderung memesan makanan pada waktu makan siang dan saat snack time.

Mayoritas pengguna berasal dari kelompok usia muda, dengan rata-rata umur 24 tahun dan standar deviasi 2.94, yang menunjukkan bahwa sebagian besar pengguna adalah dewasa muda.

Selain itu, jumlah pengguna laki-laki lebih banyak dibandingkan perempuan, yang menunjukkan adanya kecenderungan dominasi pengguna pria dalam penggunaan layanan pemesanan makanan online.

## Recommendation

1. Strategi Pemasaran:
  - Tim marketing dapat memfokuskan promosi pada laki-laki berusia 21–27 tahun, terutama dari kalangan mahasiswa dan karyawan muda.
  - Promosi yang efektif dapat berupa diskon khusus untuk waktu makan siang atau penawaran menarik untuk kategori makanan ringan (snack).
2. Peningkatan Pengalaman Pengguna:
  - Tingkatkan fitur-fitur aplikasi yang berhubungan dengan kemudahan pemesanan online, variasi pilihan restoran, dan kemudahan metode pembayaran.
  - Perkuat aspek penawaran diskon, kualitas sistem pelacakan pesanan, serta kecepatan pengiriman.
  - Dorong peningkatan kualitas pelayanan kurir, terutama dalam hal komunikasi dengan pelanggan (frekuensi panggilan) dan kesopanan dalam interaksi.
3. Perbaikan Faktor Negatif:
  - Aplikasi perlu meminimalkan masalah seperti pengiriman yang terlambat, ketidaktersediaan layanan, dan ongkos kirim yang terlalu tinggi.
  - Selain itu, perlu ada upaya untuk mengurangi waktu pengiriman dan waktu tunggu pelanggan agar pengalaman pengguna menjadi lebih baik.

## Stacks
- Python
- pandas, numpy, scipy, and plotly-express
- Tableau (Dashboard visualization)

## Reference
https://www.kaggle.com/datasets/benroshan/online-food-delivery-preferencesbangalore-region
https://public.tableau.com/app/profile/dwi.adhi.widigda.k./viz/AnalysisOnlineFoodPreferencesBangalore/Dashboard1

---
