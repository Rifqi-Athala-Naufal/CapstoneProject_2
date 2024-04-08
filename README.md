# Capstone Project 2

 - **Rifqi Athala Naufal**
 - **JCDSOL - 013**


# **New York City TLC Trip Record**

## **Latar Belakang**

Salah satu perusahaan yang menjadi vendor untuk TLC (Taxi and Limousine Commission) di Kota New York adalah VeriFone Inc. Perusahaan tersebut memfasilitasi pencatatan data setiap perjalanan taxi di kota tersebut.

Terdapat banyak area lokasi penjemputan penumpang di Kota New York, namun tidak semua lokasi tersebut selalu ramai dengan penumpang.

Stackholder yang mengambil keputusan disini adalah Manajer Perusahaan Taxi VeriFone Inc.

## **Pernyataan Masalah**

Stackholder ingin meningkatkan profit perusahaan dengan cara mengetahui area lokasi penjemputan penumpang manakah yang paling ramai di kota New York. Informasi ini akan membantu perusahaan untuk meningkatkan efektifitas penempatan taksi di area yang memiliki jumlah penjemputan tertinggi sehingga harapannya mampu meningkatkan profit perusahaan.

Sebagai seorang Data Analyst, kita akan mencoba menjawab pertanyaan berikut:

**Bagaimanakah cara meningkatkan profit perusahaan dan meningkatkan efektifitas lokasi pickup customer?**


## **Data**
Dataset dapat diakses [di sini](https://drive.google.com/drive/folders/1NYHIL-RgVPW-HONz4pdzlcbIChF-c37N).

## Kesimpulan dan Rekomendasi

### Kesimpulan
* Data yang digunakan dalam proses analisis adalah data pada bulan Januari 2023.

* Terdapat lokasi penjemputan yang kurang efektif sebesar 48%.

* Id Lokasi Pickup 74 merupakan jumlah trip tertinggi dengan jumlah trip sebanyak 10,565 kali.

* Terdapat sebanyak 18 lokasi berbeda yang hanya memiliki jumlah 1 trip yang dapat dikategorikan kurang efektif.

* Jumlah Trip Dispatch sangat sedikit (2.4%) jika dibandingkan dengan Street-hail.

* Terdapat anomali pada data, yaitu Trip Distance 0 sebesar 3%.Adanya kemungkinan taximeter pada beberapa taxi mengalami kerusakan sehingga ada beberapa perjalanan taxi yg memiliki jarak pengantaran 0.

* Hari selasa merupakan hari yang paling banyak penumpang, sedangkan hari minggu merupakan hari yang paling sedikit penumpang.

* Jam paling ramai dari jumlah trip mulai dari jam 12 siang hingga 20 malam. Sedangkan jam paling sepi dari jumlah trip dari jam 0 dini hari hingga 6 pagi.

* jumlah penumpang yang hanya berisi 1 penumpang dalam 1x Trip menjadi yang paling banyak dengan 46,462 orang.

* ID lokasi pickup 74 dan 75 adalah lokasi yang memiliki jumlah trip terbanyak dengan jumlah customer lebih dari 4 orang dalam 1x trip.

* Terdapat sedikit peningkatan income setiap minggunya pada bulan Januari 2023.

* Durasi trip paling lama adalah 23 jam dengan jumlah 139 trip.

* Perjalanan dengan lama durasi selama 23 Jam dan dengan kecepatan 24 mil/jam adalah tidak normal, sehingga perlu dilihat lebih lanjut.


### Rekomendasi

* Mengalokasikan taxi ke lokasi pick up yang ramai (ID Lokasi Pickup 74) untuk meningkatkan efesiensi trip dan profit perusahaan.

* Menghindari lokasi area yang sepi penumpang untuk meningkatkan efektivitas trip dan profit perusahaan.

* Meningkatkan peforma dan kualitas aplikasi taxi untuk menaikkan profit dan efektivitas.

* Memfokuskan pada jam paling ramai yaitu pada pukul 12 siang hingga 20 malam terutama pada hari teramai yaitu hari Selasa.

* Dapat difokuskan pada ID Lokasi Pickup 74 dan 75 untuk jumlah penumpang lebih dari 4 orang per trip karena memiliki jumlah trip terbanyak dibanding yang lain.

* Melakukan pengecekan rutin mengenai keakuratan taximeter pada setiap taxi.

* Dapat dilakukan pengecekan kemacetan dalam perjalanan yang mungkin menyebabkan lamanya durasi trip.
