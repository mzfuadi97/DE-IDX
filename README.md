## 1. Restore Database
Restore database staging.bak, berikut langkahnya :
1. 
2.
3.

## 2. Membuat Tabel Fact & Dimension
Membuat database baru terlebih dahulu yang akan dianggap data warehouse. Didalam database tersbut terdapat tabel fact dan dimension dengan dokumentasi sebagai berikut :


## 3. Membuat Job ETL 
Pada bagian transformasi data di komponen tMap gunakan fungsi UPCASE untuk merubah karakter menjadi kapital, dan menggabungkan kata dengan (+), demikian dokumentasinya :


## 4. Membuat Store Precedure
Store Procedure, mengikuti kebutuhan format/tipe data sebagai parameter di awal dan memasukkan variabel tersebut sebagai kondisi di akhir (sintaks WHERE), berikut dokumentasinya dengan menampilkan OrderID, CustomerName, ProductName, Quantity, StatusOrder,