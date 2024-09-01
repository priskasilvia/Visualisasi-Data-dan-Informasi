| **Field**          | **Details**                                                                         |
|--------------------|-------------------------------------------------------------------------------------|
| **Judul Artikel**  | Making data visualization more efficient and effective: a survey                    |
| **Penulis**        | Xuedi Qin, Yuyu Luo, Nan Tang, Guoliang Li                                           |
| **Penerbit**       | The VLDB Journal                                                                     |
| **Tanggal Terbit** | 19 November 2019                                                                     |
| **DOI**            | [https://doi.org/10.1007/s00778-019-00588-3](https://doi.org/10.1007/s00778-019-00588-3) |

**Priska Silvia Ferantiana || 122450053 || RB**

## Pendahuluan 

Perkembangan teknologi yang sangat pesat saat ini tentu menghasilkan data yang banyak pula. Oleh karena itu dibutuhkan pula visualisasi data untuk membantu pengambilan keputusan yang berkaitan dengan pendapatan utama banyak perusahaan terutama perusahaan industri. Tingginya permintaan terkait pemrosesan data seperti volume, kecepatan, dan kebenaran data tentu memunculkan kebutuhan baru untuk membantu visualisasi data yang efisien dan efektif. Visualisasi data sendiri mengubah data abstrak menjadi tampilan fisik (panjang, posisi, bentuk, warna, dan lain-lain) untuk menyajikan data yang menarik dan lebih berorientasi visual. Visualisasi data sangat cocok untuk memberikan gambaran umum tentang big data dan memudahkan interpretasi hasil analisis data. 

 

## Pembahasan
## 1. Alur Visualisasi Data

Visualisasi data memiliki alur sebagai berikut: 

1. Data import, yaitu mengambil data yang diperlukan dari sumber data yang diinginkan. 

2. Data preparation, yaitu menyiapkan data yang telah diimpor untuk divisualisasikan. 

3. Data manipulation, yaitu memilih data yang akan divisualisasikan. 

4. Mapping, yaitu memetakan data yang telah dimanipulasi ke geometric primitives sesuai dengan atributnya, seperti warna, posisi, dan ukuran. 

5. Rendering, yaitu mengubah data geometric di atas menjadi representasi visual. 

 
## 2. Membuat Visualisasi Data Menjadi Efisien dan Efektif
Berdasarkan alur di atas, ada tiga cara untuk membuat visualisasi data menjadi lebih efisien dan efektif. 

1. Visualization Specifications, menyediakan berbagai cara bagi pengguna untuk menentukan apa yang mereka inginkan. 

2. Efficient Approaches for Data Visualization, melibatkan pengguna secara efektif dalam alur kerja iteratif untuk menghasilkan visualisasi data yang lebih cepat dan responsif. 

3. Data Visualization Recommendation, menentukan visualisasi secara tepat dengan memberikan rekomendasi untuk visualisasi berdasarkan spesifikasi pengguna. 

 
## 3. Pendekatan Efisien
Berikut ini adalah pendekatan efisien untuk visualisasi data. 

1. Visualisasi data yang tepat. 
Sistem dapat mengeluarkan query SQL untuk mendapatkan data dari basis data, memetakan data tersebut ke visualisasi yang sesuai. 

2. Perkiraan visualisasi data. 
Dalam data yang besar dan kompleks, perkiraan visualisasi data dapat memberikan gambaran sehingga mempercepat proses pembuatan visualisasi. 

3. Visualisasi data progresif. 
Hasil visualisasi data diperbarui secara progresif seiring dengan pengolahan data lebih lanjut. 

 
## 4. Rekomendasi Visualisasi
Menentukan visualisasi data yang tepat juga menjadi tantangan pada proses visualisasi data. Oleh karena itu terdapat rekomendasi visualisasi sebagai berikut: 

1. Rekomendasi berbasis spesifikasi. Rekomendasi ini terbagi menjadi dua, yaitu spesifikasi tidak lengkap di mana spesifikasi elemen visualisasi kosong atau kosong sebagian. Spesifikasi kedua yaitu spesifikasi berbasis referensi di mana sistem ini akan merekomendasikan visualisasi yang mirip atau berbeda dari referensi yang diberikan. 

2. Rekomendasi berbasis perilaku. Sistem ini menangkap perilaku pengguna sebagai input. 

3. Rekomendasi yang dipersonalisasi. Sistem rekomendasi ini menangkap perilaku historis pengguna sebagai input. 

4. Ringkasan. Sistem rekomendasi dengan spesifikasi kosong digunakan pengguna untuk menjelajahi data dengan cepat ketika pengguna tidak begitu mengenal data dan visualisasi yang diinginkan. 

 

## Kesimpulan 

Pembahasan ini menyoroti pentingnya visualisasi data dalam membantu pengambilan keputusan dan mempermudah interpretasi hasil analitik data. Untuk menjawab tantangan dalam efisiensi pemrosesan data, khususnya dalam hal volume, kecepatan, dan kebenaran data, dibutuhkan berbagai teknik yang membuat visualisasi data lebih efisien dan efektif. Tiga area utama yang dibahas adalah spesifikasi visualisasi, pendekatan efisien untuk visualisasi data, dan rekomendasi visualisasi data. 
