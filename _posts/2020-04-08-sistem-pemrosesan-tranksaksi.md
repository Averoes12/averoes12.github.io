---
layout: post
title: Sistem Pemrosesan Tranksaksi
date: 2020-04-08 +0700
description: informasi data data dan informasi sistem informasi tps sistem pemrosesan tranksaksi
img: data.jpg # Add image post (optional)
tags: [Blog, College]
author: Averoes Blog # Add name author (optional)
---

# Trancsaction Prosessing System(TPS)

 **TPS** adalah sebuag sistem yang digunakan sebagai pintu utama dalam pengumpulan dan pengolahan data pada suatu organisasi, dan sistem yang berinteraksi langsung dengan sumber data(misal pelanggan) adalah sistem pengolahan data.

### Tujuan TPS

  1. Mencatat setiap tranksaksi yang terjadi;
  2. Mempercepat proses yang terjadi di suatu perusahaan;
  3. Menydiakan informasi yang akurat dan tepat waktu;
  4. Meningkatkan kinerja dan layanan.

### Tugas TPS
  
  Mengumpulkan dan mempersiapkan data untuk keperluan sistem informasi yang lain dalam organisasi, misalnya untuk kebutuhan sistem informasi manajemen, atau sistem informasi eksekutif.

  Ada 4 tugas pokok dari sistem pengolahan tranksaksi :

  1. **Pengumpulan data**
   Setiap organisasi yang beriteraksi langsung dengan lingkungannya dalam penyediaan jasa dan produk, pasti mmembutuhkan sistem yang mengumpulkan data tranksaksi  yang bersumber dari lingkungan.

  2. **Manipulasi data**
   Data transaksi yang dikumpulkan biasanya diolah lebih dahulu sebelum disajikan sebagai informasi untuk keperluan bagian-bagian dalam organisasi atau menjadi bahan masukan sistem informasi yang lebih tinggi. Beberapa tugas manipulasi data adalah sebagai berikut:

  - Klassifikasi : data dikelompokkan menurut kategori tertentu, misalnya menurut jenis kelamin, menurut agama, menurut golongan, dsb.

  - Sortir : data diurutkan menurut urutan tertentu agar lebih mudah dalam pencarian data, misalnya di-sortir menurut abjad nama, atau menurut nomer induk, dsb.

  - Perhitungan : melakukan operasi aritmetika terhadap elemen data tertentu, misalnya menjumlahkan penerimaan dan pengeluaran setiap hari, atau menghitung jumlah hutang pelanggan, dsb.

  - Pengikhtisaran : melakukan peringkasan data (summary) seperti sintesa data menjadi total, sub-total, rata-rata, dsb.

  3. **Penyimpanan data** 
   Data tranksaksi haru disimpan dan dipelihara sehingga ketika suatu waktu dibutuhkan data tetap aman dan bisa memenuhi kebutuhan para pengguna.

  4. **Penyiapan dokumen**
   Beberapa dokumen laporan harus disiapkan untuk memenuhi unit-unit kerja dalam organisasi.

### Karakteristik sistem pengolahan tranksaksi
   
   - Volume data yang dimiliki relatif besar.
   - Kapasitas penyimpanan data yang digunakan sangat besar.
   - Kecepatan koneksi yang digunakan sangat cepat agar bisa memproses data yang sangat banyak dalam waktu yang sangat singkat.
   - Pengolahan data biasanya dilakukan periodik harian, mingguan, bulanan, dsb.
   - Orientasi data yang dikumpulkan mengacu pada data masa lalu.
   - *Input* dan *Output* terstruktur, data diformat sesuai standar yang sudah ditetapkan.
   - Komputasi tidak terlalu rumit.

### Teknik pengolahan data

   1. **Batch Prosessing** 
    Data yang diperoleh dari sumber akan dikumpulkan terlebih dahulu dan akan diproses diwaktu-waktu tertentu, misal dikumpulkan data dari Bulan ke-2 hingga bulan ke-4 pada jam 08:00 lalu jika sudah terkumpul akan diproses pada jam 19:00 - 22:00, Proses ini membutuhkan waktu lama dan data menjadi tidak selalu *up-to-date*.

   2. **Online Prosessing** 
    Data yang diperoleh dari sumber akan langsung diproses saat diterima, seperti melakukan tranksaksi melalui *M-Banking*.

   3. **Real–time processing**
    Pemrosesan data tidak boleh ditunda karena waktu sangat kritis, penundaan pengolahan dapat mengakibatkan sesuatu yang fatal. Misalnya pengolahan data hasil pemantauan aktivitas gunung berapi.

   4. **Hybird Prosessing** 
    Kombinasi antara batch-processing dan online-processing. Misalnya pengolahan transaksi di Cafe, dimana transaksi penjualan melalui POS (point of sale) langsung dilakukan (online), tetapi pengolahan lebih lanjut tentang persediaan barang dilakukan setiap jam 11:00 malam.

### Siklus TPS

  Mengelompokkan tranksaksi berdasarkan kesamaan unsur dan/atau sasaran

  - **Siklus Pendapatan**
   Tranksaksi penjualan dan tranksaksi penerimaan tunai.
 
  - **Siklus Pengeluaran**
   Tranksaski pembelian dan tranksaksi pengeluaran tunai.

### Komponen TPS
   
   1. **Input**
    
   Dokumen sumber seperti faktur pembelian, struk tranksaksi, kartu jam karyawan, dsb. adalah bukti fisik inputan TPS.

   Tujuannya adalah :

   - Menangkap data.
   - Membantu proses komunikasi dan otorisasi operasi departemen.
   - Menyediakan berkas permanen untuk analisis.

   2. **Prosessing** 
    
   Mencakup penggunaan jurnal dan register untuk menyajikan catatan input secara permanen dan kronologis.

   - Jurnal digunakan untuk mencatat tranksaksi akuntansi keuangan.
   - Register digunakan untuk memcatat tipedata lain yang tidak berhubungan langsung dengan akuntasi.

   3. **Storage** 

   Media penyimpanan yang digunakan untuk menyediakan data baik dalam sistem manual atau terkomputerisasi, Media penyimpanan tersebut menyediakan ringkasan suatu tranksaksi keuangan.

   4. **Output**  

   Terdapat beragam variasi keluaran dari sistem pemrosesan transaksi. Setiap dokumen yang di hasilkan dari sistem adalah keluaran. Dokumen keluaran dari departemen accounting adalah laporan keuangan.
   Contoh output :
   - Trial balance.
   - Financial reports.
   - Operational reports.
   - Paychecks.

### Perbedaan pemrosesan batch dan online

  | Karakteristik | Batch         | Online  |
  | ------------- |:-------------:| -----:|
  | Pemrosesan tranksaksi | Data transaksi direkam, dikumpulkan, di urutkan dan di proses secara periodis | Transaksi diproses seketika |
  | Pemutakhiran berkas | Ketika tumpuakan diproses | Saat transaksi di proses |
  | Waktu Response | Beberapa jam atau hari setelah tumpukan dikirim atau di proses | Beberapa detik setelah transaksi di proses |

### Kesimpulan

Sistem Pengolahan Transaksi (Transaction Processing System disingkat TPS) adalah sistem yang menjadi pintu utama dalam pengumpulan dan pengolahan data pada suatu organisasi.

Dalam jenis pemrosesan “online processing” lebih efisiens dari pada jenis “bath processing” yang membutuhkan banyak waktu dan menunggu pengumpulan data terlebih dahulu sebelum data diproses. Banyak juga pengembangan system pemrosesan transakasi  yang ada di kehidupan sehari – hari.

  ___

   Sumber

   https://ilmuprabowo.wordpress.com/category/pertemuan-ke-3/sistem-pemrosesan-transaksi/
   http://anissya-rohman.blogspot.com/2014/09/sistem-pemrosesan-transaksi.html
   https://marlonsn.wordpress.com/2012/05/10/sistem-pemprosesan-transaksi/
 