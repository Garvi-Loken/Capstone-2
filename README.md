**Capstone-2**
Capstone 2 Purwadhika - Bimayu Satriyo Gusmana
# PENDAHULUAN
Sebuah supermarket menjual beberapa barang seperti daging, ikan, buah buahan, minuman dan emas. Barang tersebut bisa dibeli atau didapatkan melalui web, katalog toko dan pembelian langsung di toko. 

Supermarket tersebut ingin meningkatkan efektivitas strategi pemasarannya dengan memahami pola - pola dari perilaku, karakteristik dan preferensi pelangganya agar strategi pemasaran bisa sesuai dengan kelompok target pelanggan dan bisa memiliki potensi untuk melakukan transaksi. Untuk itu diperlukan sebuah analisis kepribadian pelanggan untuk memahami dan memberikan informasi dari karakteristik dan kebutuhan pelanggan.
# TUJUAN
Dari data yang ada dan keinginan dari supermarket tersebut, tujuan yang harus dicapai adalah :

1. Mengetahui karakteristik pelanggan bedasarkan usia dan pendapatan.
2. Mengetahui produk yang diminati bedasarkan karakteristik pelanggan.
3. Mengetahui cara yang digunakan untuk berbelanja (Web, katalog, toko).
# DATA DICTIONARY
People

* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Products

* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years

Promotion

* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

Place

* NumWebPurchases: Number of purchases made through the company’s website
* NumCatalogPurchases: Number of purchases made using a catalog
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to the company’s website in the last month
# PEMBERSIHAN DATA DAN PENYIAPAN DATA
1. Menghapus missing value
2. Mengganti nama kolom.
3. Membuat kolom baru.
4. Menghapus outliers.
# VISUALISASI DATA
1. Melihat korelasi antar kolom
2. Melihat distribusi bedasarkan Umur dan Kelas Ekonomi
3. Melihat rata rata pembelian produk
4. Melihat produk favorit tiap kelompok pembeli (sesui umur dan kelas ekonomi)
5. Melihat cara pembelian tiao kelompok pembeli (sesui umur dan kelas ekonomi)
