# Experiment-Code-Chapter-3
## Nama      : Arya Admaja
## Kelas     : TI - 3C
## No. Absen : 04

BIG DATA - Chapter 3

## Hasil

## Uji Coba SpySpark
![S1](https://user-images.githubusercontent.com/90190923/227858768-c8f70a57-c9e8-4f9e-ad1d-d1ae5dc6f994.jpg)

## Accumulator
![S2](https://user-images.githubusercontent.com/90190923/227859117-f8ac90a5-e535-49f3-956f-9daf6690e903.jpg)
Fungsi accumulator (bertujuan akumulasi shared variable) berhasil dijalankan dengan output "4950".

## Broadcast
![S3](https://user-images.githubusercontent.com/90190923/227859205-a83bd438-b2b2-4dbb-bae2-043c493b782a.jpg)
Fungsi Broadcast (Membuat variabel broadcast) sesuai range dan untuk mengakses nilai matriks / array menggunakan atribut broadcastVar.value

## PairRDD
![S4](https://user-images.githubusercontent.com/90190923/227859424-f2b13bf6-4a83-4280-8b24-70131ad4054b.jpg)
Hasil : Berhasil. fungsi dasar dari sebuah collection. 
- method maps digunakan untuk mapping sebuah collection 
- key: variabel myList
- value: jumlah huruf dari tiap" kata variabel myList
- myPairRDD.collect(): print collection
- myPairRDD.keys().collect(): print key pada collection
- myPairRDD.values().collect(): print values pada collection

## SystemCommandsOutput
![S7](https://user-images.githubusercontent.com/90190923/227860364-1cdb806f-eab5-42ad-b742-974fc14e8789.jpeg)
Menampilkan list file pada hdfs. Output 0 atau string "" karna belum terdapat file.

## SystemCommandsReturnCode
![S8](https://user-images.githubusercontent.com/90190923/227860287-326c884e-3a3f-43ac-9475-1df30761aff6.jpg)
Menampilkan list file pada folder /tmp (temporary file)

## UnderstandingRDDs
![S5](https://user-images.githubusercontent.com/90190923/227859790-749aa0d7-a43f-4b84-b419-1018d8b784ca.jpg)
Membuat sebuah list, dengan mempraktikan yaitu menghitung jumlah partisi, elemen, menampilkan data pada collection, dan memodifikasi collection (menambahkan atau mengurangi).

## WordCount
![S6](https://user-images.githubusercontent.com/90190923/227859957-33042d5b-9f19-4f9d-bb86-db2c2d395884.jpg)
Menghitung jumlah kata yang ada suatu file (test.txt).
