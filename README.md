## 1. Restore Database
Restore database staging.bak, berikut langkahnya :
1. <img width="960" alt="1" src="https://github.com/mzfuadi97/DE-IDX/assets/70827786/a3e0a5b9-3700-4c29-8942-b6b24065a568">

2. <img width="960" alt="Screenshot 2023-08-27 191830" src="https://github.com/mzfuadi97/DE-IDX/assets/70827786/4367b280-0930-4905-baa8-11a326136d9c">

3.<img width="960" alt="3" src="https://github.com/mzfuadi97/DE-IDX/assets/70827786/fe73dcc3-a340-4da8-bbf1-4c051fb8a03b">


## 2. Membuat Tabel Fact & Dimension
Membuat database baru terlebih dahulu yang akan dianggap data warehouse. Didalam database tersbut terdapat tabel fact dan dimension dengan dokumentasi sebagai berikut :
<img width="164" alt="Screenshot 2023-08-27 203257" src="https://github.com/mzfuadi97/DE-IDX/assets/70827786/1b1257ce-5384-4776-ba52-92e53638d194">


## 3. Membuat Job ETL 
Pada bagian transformasi data di komponen tMap gunakan fungsi UPCASE untuk merubah karakter menjadi kapital, dan menggabungkan kata dengan (+), demikian dokumentasinya :
![node_job](https://github.com/mzfuadi97/DE-IDX/assets/70827786/071dcd29-b169-4aa4-9b10-6d108c146ddd)

![tranformation_job](https://github.com/mzfuadi97/DE-IDX/assets/70827786/eb8f03fa-76aa-4f50-8958-2aac445bf258)


## 4. Membuat Store Precedure
Store Procedure, mengikuti kebutuhan format/tipe data sebagai parameter di awal dan memasukkan variabel tersebut sebagai kondisi di akhir (sintaks WHERE), berikut dokumentasinya dengan menampilkan OrderID, CustomerName, ProductName, Quantity, StatusOrder :

<img width="125" alt="store_procedure" src="https://github.com/mzfuadi97/DE-IDX/assets/70827786/d4a4b615-6a4f-4a9b-a188-bcee410f2076">
