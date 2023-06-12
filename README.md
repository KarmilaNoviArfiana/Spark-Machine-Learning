# TUGAS BIG DATA SPARK MACHINE LEARNING

Nama : Karmila Novi Arfiana

Kelas : TI 3C / 09

NIM : 2041720073

#
1. PPT HAL 30 (MOVIE LENS RECOMMENDATION)

    - Akses dataset / file, kemudian install pyspark.
    ![](img/ss1.png)

    - import library pyspark.ml, dan pyspark.sql. Kemudian read file ratings.dat pada google drive. kemudian lakukan RDD mapping.
    ![](img/ss2.png)

    - Membuat model rekomendasi menggunakan ALS pada training data yang sebelumnya sudah dibuat
    ![](img/ss3.png)
    - Output
    ![](img/hasil.png)

2. PPT HAL 48 

    - Akses google drive, kemudian install pyspark 
    ![](img/ss4.png)
    ![](img/ss5.png)

    - Mengubah data ratings.dat mejadi objek Rating dan data baru ditambahkan ke RDD. model digunakan untuk merekomendasikan 10 produk kepada pengguna.
    ![](img/ss6.png)
    - Output
    ![](img/hasil2.png)

3. PPT HAL 49

     - Menampilkan statistik summary mulai dari rata", varian, dll dari vectorRdd rating yang telah di proses sebelumnya. 
     ![](img/ss7.png)

4. PPT HAL 52
    - Melakukan klastering dengan algoritma K-means, dengan data diubah menjadi vektor, kemudian model k-means ditrain dan digunakan untuk melakukan prediksi klaster. Lalu hasil within set sum of squared errors (wssse) dihitung dan di cetak.
    ![](img/ss8.png)
    - Output 
    ![](img/hasil3.png)

5. PPT HAL 53 - 54
    - Melakukan klastering dengan K-means, data dibaca dan buat menjadi array, kemudian K-means dibuat untuk mengklasterkan data ke dalam dua klaster. Lalu menghitung within set sum of squared errors. 
    ![](img/ss9.png)
    - Setelah berhasil, maka akan tampil berbentuk file clusters yang telah disimpan pada folder yulia_path
    ![](img/hasil4.png)