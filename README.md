# Disease-classification-hybridMethod

Program ini merupakan program machine learning untuk melatih model menggunakan metode hybrid K-mean dan KNN

## K-Mean
K-means adalah algoritma klastering yang bertujuan untuk membagi sekumpulan data menjadi K klaster berdasarkan karakteristik atau fitur data tersebut.

## Knn
K-Nearest Neighbors (KNN) adalah algoritma pembelajaran mesin yang digunakan untuk klasifikasi dan regresi. ketika ada data baru yang belum diklasifikasi, maka akan dilihat data tetangga yang terdekat/memiliki kesamaan, klasifikasi data baru akan mengikuti data tetangga terdekat.

Metode hybrid ini digunakan untuk mendapat akurasi yang lebih efektif. Dataset terlebih dahulu dibagi menjadi beberapa cluster berdasarkan pola kemiripan menggunakan algoritma K-means. setelah dibagi, akan diambil 1 cluster untuk dilatih menggunakan metode KNN.

Dataset yang digunakan pada source code ini adalah dataset penyakit parkinson. machine learning menggunakan semua fitur/variabel untuk melatih model dan variabel target adalah diagnosis positif/negatif terkena penyakit.
sumber dataset diambil dari kaggle pada link berikut:
https://www.kaggle.com/datasets/rabieelkharoua/parkinsons-disease-dataset-analysis

dataset dapat diganti dan disesuaikan berdasarkan kebutuhan.
