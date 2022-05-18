# Bank Marketing Campaign 

## Define Problem 

### Saat ini memasarkan produk deposito masih random sehingga perbankan mengalami kehilangan cost terutama 

## Goal 

### Memasarkan produk deposito secara efisien 

## Impact 

### Bank Marketing

## EDA

### 1. Customer have been Loan According Generation

<img src='loan no.png'> </img> 

<img src='loan yes.png'> </img> 

### 2. Transaction Marketing Jan - December 

<img src='Bank Marketing.png'> </img>

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

