# Bank Marketing Campaign 

## Business Context 

### Perbankan saat ini melakukan mencari nasabah untuk melakukan deposito, hal ini bertujuan dengan melakukan deposito tabungan yang disimpan lebih aman dan bunganya terjangkau daripada jika hanya menyimpan dengan tabungan biasa

## Business Problem 

### Saat ini marketing mencari nasabah untuk melakukan deposito masih dilakukan secara satu per satu sehingga dapat menambah waktu dan biaya yang dikeluarkan

## Business Goal 

### Menghemat waktu dan biaya untuk mencari nasabah yang niat untuk melakukan deposito

## Impact 

### Bank Marketing

## EDA

### 1. Customer have been Loan According Generation

<img src='loan no.png'> </img> 

<img src='loan yes.png'> </img> 

## Berdasarkan data customer tersebut, generasi X merupakan yang melakukan pinjaman, dikarenakan generasi tersebut lebih banyak kebutuhan yang dikeluarkan sehari-hari

### 2. Transaction Marketing Jan - December 

<img src='Bank Marketing.png'> </img>

## Berdasarkan transaksi dari bulan januari - desember, bulan mei merupakan bulan yang tertinggi untuk melakukan mencari nasabah sedangkan dibulan desember merupakan bulan yang sedikit sekali melakukan mencari nasabah untuk melakukan deposito dikarenakan bulan tersebut merupakan liburan natal sehingga uangnya dipakai untuk kebutuhan natal

### Simulation 

<p> Kita Asumsikan Rata - rata call center itu 4 menit: https://financesonline.com/call-center-statistics/ dan minimal deposito Rp 10.000.000:  </p>

### Random Forest: customer yang memiliki niat untuk deposito: 159 * 4 = 636; pemasukan deposito Rp 1.590.000.000; customer yang tidak niat deposito kehilangan 276 ==> Rp 2.760.000.000   
### Gradient Boost: customer yang memiliki niat untuk deposito: 168 * 4 = 672; pemasukan deposito Rp 1.680.000.000; customer yang tidak niat deposito kehilangan 286 ==> Rp 2.860.000.000 
### XGB: customer yang memiliki niat untuk deposito: 158 * 4 = 632; pemasukan deposito Rp 1.580.000.000; customer yang tidak niat deposito kehilangan 284 ==> Rp 2.840.000.000 
### Cat Boost: customer yang memiliki niat untuk deposito: 153 * 4 = 612; pemasukan deposito Rp 1.530.000.000; customer yang tidak niat deposito kehilangan 274 ==> Rp 2.740.000.000 

## Applied Machine Learning

<h4> Penerapan Model ini ketika marketing akan menawarkan produk yang target utama customer belum memiliki deposito tetapi akan mempunyai niat untuk memiliki deposito </h4>

## Conclusion 

<h4> Model Cat Boost merupakan Algoritma ML yang terbaik dimana waktu keseluruhan untuk memanggil customer yang memiliki deposito sebanyak 612 menit 

<p> Dengan melakukan pemodelan ini, marketing dapat melakukan panggilan nasabah keseluruhan hanya dengan waktu 612 menit </p>
