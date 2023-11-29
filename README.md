# Mushroom-Classification-ANN-and-GA
- Raihan Fauzi
- Wildan Hazballah Arrosyid
- Miftakhul Amal
- Muhamad Febrian Soambaton

## Pendahuluan
Pada percobaan ini digunakan ANN untuk mengkalsifikasikan apakah suatu jamur dapat di makan atau bercacun dari berbagai parameter. Setelah di klasifikasikan ANN akan di optimasi konstanta ANN nya.

## Metode
1. Penginisilaisasian library
2. Pembuatan Fungsi Untuk ANN dan GA
3. Memasukkan Dataset
4. Melakukan Klasifikasi
5. Melakukan Optimasi Dengan GA
6. Menggunakan Data Training Untuk Menetest Model
7. Menggunakan Data Test Untuk Uji Coba Model
8. Hasil Dan Kesimpulan

## Hasil
Pada pengklasifikasian menggunakan ANN dan GA dilakukan 15 generasi dengan 4 Parents Mating dan 8 Offspring/Population
![image](https://github.com/Muhamad-Febrian-Soambaton/Mushroom-Classification-ANN-and-GA/assets/148663785/4bc33786-39ed-4b9a-9b2e-3ef433cf2f52)

pada gambar di atas didapatkan mutasi dan error, dapat dilihat bahwa setelah sekian persen mutasi, mutasi tidak dapat berubah lagi atau GA sudah selesai mengkombinasikan genetic. Dan dalam pengenerasian GA Mutation Error semakin besar.

Selanjutnya dari hasil pengietrasian GA dilakukan pemilihan mutation rate terbaik yaitu di beri parameter 0.1. didapatkan hasil oleh gambar di bawah,
![image](https://github.com/Muhamad-Febrian-Soambaton/Mushroom-Classification-ANN-and-GA/assets/148663785/2b1fbd0f-bc7c-4fcd-b31a-f1326663470b)

akurasi untuk solusi terbaik dari pengenerasian GA yang sebelumnya di lakukan adalah 0.67 atau 67 persen.

Visualisasi dari ke cocokan dengan akurasi dari setiap iterasi di tunjukkan oleh gamabr di bawah.
![image](https://github.com/Muhamad-Febrian-Soambaton/Mushroom-Classification-ANN-and-GA/assets/148663785/c6e6d4ec-7b48-466e-8c83-9a4915a45f69)

dilakukan juga pengujian dari model yang di buat dengan menggunakan data train di tunjukkan oleh confusion matrix di bawah.
![image](https://github.com/Muhamad-Febrian-Soambaton/Mushroom-Classification-ANN-and-GA/assets/148663785/3d3c151b-ae6f-491d-b06d-7b35c6eaa25a)

banyak data yang gagal di klasifikasi. dilakukan juga pengujian dengan data Test di tunjukan oleh confusion matrix di bawah.
![image](https://github.com/Muhamad-Febrian-Soambaton/Mushroom-Classification-ANN-and-GA/assets/148663785/fbd7387c-5eaa-4089-9bc8-f8e29c9c1ef0)

banyak data yang gagal di kalsifikasi karena accuracy hanya 66%

ANN tidak terlalu cocok untuk pengklasifikasian jamur sehingga akurasi pengklasifikasian tidak terlalu bagus, pada pengujian juga generasi dari GA hanya 15 jadi kurang banyak.






