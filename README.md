# relation-database
Altera Data Engineer Batch 4. Tugas berkaitan dengan database relational, Data Definition Language, Data Manipulation Language

# Part 1 - Schema Database

penjelasan:

one to many: pelanggan dengan transaction

one to many: payment_method dengan transaction

one to many: transaction dengan transaction_detail

one to many: product dengan transaction_detail

one to many: product_type dengan product

one to one: product_description dengan product

one to many: merk dengan product

# Part 2 - Data Definition Language
1. Create database alta_online_shop

   ![image](https://github.com/farhanriyandi/relation-database/assets/67671418/fc0e153b-d193-47f7-a5fe-4cce064a966d)
 
# Part 3 - Data Manipulation Language

2. Select
2a. Tampilkan nama user/ pelanggan dengan gender laki-laki

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/c368ccdb-09af-435f-a66b-f8c4c16f7bfc)

2b.Tampilkan product dengan id=3

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/1b160816-fdf2-40ce-afa1-e6f140b9fb35)

2c. Tampilkan data pelanggan yang created_at range 7 hari kebelakang dan mempunyai nama mengandung kaya 'a'

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/b30b2ec0-a0e6-443e-8cd1-1373650c9a2e)

2d. hitung jumlah user/pelanggan dengan status gender perempuan.

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/d95d6fb3-1a56-4b2b-b8d7-57a34cd7dcb7)

2e. tampilkan data pelanggan dengan urutan sesuai nama abjad

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/3010022f-d1ae-4eaa-8eb8-eca312e45937)

2f. tampilkan 5 data transaksi dengan product id= 3 

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/06407c10-1251-4b8e-8a91-b7b3fee70984)


# Release 2: Join, Union, Sub-query, function
1. gabungkan data transaksi dari user id 1 dan user id 2

   ![image](https://github.com/farhanriyandi/relation-database/assets/67671418/55f8489b-2817-4511-a248-a12f64a346f6)

2. tampilkan jumlah harga transaksi user id 1

   ![image](https://github.com/farhanriyandi/relation-database/assets/67671418/a3980ad8-79f6-47db-a157-d266f4553847)

3. tampilkan total transaksi dengan product type 2
   
![image](https://github.com/farhanriyandi/relation-database/assets/67671418/77b9e5ee-381d-4fd6-9ea0-b25b4f22b296)

   
4. tampilkan semua field table product dan field name table product type yang saling berhubungan

   ![image](https://github.com/farhanriyandi/relation-database/assets/67671418/8e3aad0f-755e-498c-9bab-52c582cc21c3)
   
5.    tampilkan semua field table transaction, field name table product dan field name table user

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/dfa236f9-8927-46e5-b1d5-fa92835294df)

6. tampilkan data products yang tidak pernah ada di tabel transaction_details dengan sub-query

![image](https://github.com/farhanriyandi/relation-database/assets/67671418/3771de2c-6593-4124-8697-db1ee6b41df5)
  










