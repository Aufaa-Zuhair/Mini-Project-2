# Mini Project Perusahaan LuxGro Beauty Market

# Latar Belakang

Dalam era digital saat ini, konsumen semakin aktif dalam memberikan penilaian dan ulasan terhadap produk yang mereka beli secara daring. Penilaian tersebut, yang tercermin dalam rating produk, menjadi indikator penting dalam mengukur kepuasan dan persepsi konsumen terhadap kualitas suatu barang. Oleh karena itu, memahami faktor-faktor yang memengaruhi rating produk menjadi hal yang krusial, terutama bagi pelaku bisnis dan pemilik merek.

Beberapa faktor yang diduga memengaruhi penilaian konsumen antara lain harga produk, besarnya diskon, dan brand. Secara umum, ada anggapan bahwa harga yang lebih tinggi mencerminkan kualitas yang lebih baik, sehingga akan mendapatkan penilaian yang lebih tinggi pula. Namun, realitas di lapangan tidak selalu sejalan. Sebaliknya, produk dengan harga murah dan diskon besar belum tentu mendapatkan rating rendah sebagian bahkan justru menjadi produk favorit konsumen.

Selain itu, nama dan reputasi brand juga memainkan peran penting. Brand yang dikenal akan kualitas dan kepuasan pelanggan cenderung memiliki rating lebih tinggi dibandingkan brand baru atau yang memiliki masalah dalam layanan maupun produk.

# Rumusan Masalah

1. Apakah produk dengan diskon tinggi cenderung mendapatkan rating lebih rendah karena ekspektasi pelanggan?
2. Brand mana yang memiliki rata-rata rating tertinggi berdasarkan ulasan pelanggan?
3. Produk apa dengan rating tertinggi tetapi harga paling murah?
4. Apakah kategori produk tertentu cenderung memiliki stok lebih rendah karena tingginya permintaan?

# Data Cleaning

Berdasarkan data terlampir yang hanya kami perlukan untuk analisa, yaitu hanya brand, stock, rating, discount, category, product_name. data - data tersebut merupakan data yang krusial/esensial untuk efektifitas kami dalam membaca dan menganalisa data, sehingga kami tidak kesulitan dalam melihat brand apa saja yang menjadi rating tertinggi maupun rating terendah.

title kita ubah menjadi product_name untuk menghindari kebingungan dalam membaca, karena title merupakan kode unique dari nama produk itu sendiri

# Analisa Data

1. Apakah produk dengan diskon tinggi cenderung mendapatkan rating lebih rendah karena ekspektasi pelanggan?

insight : 
Harga (Price) punya korelasi positif lemah terhadap rating (+0.16):

Artinya, semakin mahal suatu produk, cenderung memiliki rating sedikit lebih tinggi.

Meskipun korelasinya lemah, ini bisa menunjukkan bahwa pelanggan mungkin menilai produk mahal sebagai "lebih berkualitas".

📉 Diskon (Discount) punya korelasi negatif lemah terhadap rating (−0.20):

Semakin besar diskon, rating cenderung sedikit lebih rendah.

Mungkin produk yang sering diskon dianggap kurang eksklusif, bermasalah stok, atau kurang laku, sehingga persepsi pelanggan juga rendah.

Bisa juga karena konsumen punya ekspektasi lebih tinggi saat beli dengan diskon, lalu kecewa.

2. Brand mana yang memiliki rata-rata rating tertinggi berdasarkan ulasan pelanggan?

insight : 
Knoll (4.88), Velvet Touch (4.64), dan FreshCo (4.46) menduduki peringkat teratas.

Ini menunjukkan bahwa konsumen sangat puas terhadap produk dari brand ini.

Essence (2.56) dan Glamour Beauty (2.86) memiliki rating terendah.

Perlu dilakukan evaluasi: apakah masalahnya di produk, harga, pelayanan, atau ekspektasi pelanggan yang tidak terpenuhi?

3. Produk apa dengan rating tertinggi tetapi harga paling murah?

insight : 
dengan rating tertinggi (4.93), harga termurah (2.49), dan stok tinggi (99), artinya:

Produk dengan rating tinggi tidak selalu mahal. Bahkan, dalam kasus ini, produk termurah justru paling disukai pelanggan.

Ini membuka kemungkinan bahwa harga terjangkau dapat mendorong rating positif, terutama untuk kebutuhan sehari-hari seperti bahan makanan.

4. Apakah kategori produk tertentu cenderung memiliki stok lebih rendah karena tingginya permintaan?

Insight :
Kategori groceries memiliki rata-rata stok terendah, sementara beauty memiliki stok tertinggi. dapat disimpulkan bahwa permintaan terhadap groceries lebih tinggi karena sifatnya yang esensial dan cepat habis. Sebaliknya, produk beauty cenderung bergerak lambat karena siklus pembelian yang lebih jarang. Namun, stok rendah belum tentu berarti permintaan tinggi, bisa juga karena strategi penyimpanan.

# Kesimpulan

1. Korelasi Harga dan Rating (+0.16)
Produk yang lebih mahal sedikit lebih cenderung memiliki rating lebih tinggi.
Ini menunjukkan adanya persepsi kualitas berdasarkan harga, meskipun tidak signifikan secara statistik.

2. Korelasi Diskon dan Rating (−0.20)
Produk dengan diskon besar cenderung memiliki rating lebih rendah.
Bisa jadi karena ekspektasi tinggi saat membeli dengan diskon tidak terpenuhi, atau produk diskon memang berkualitas rendah.

3. Rating Tertinggi Bukan Produk Termahal
Produk dengan rating tertinggi justru paling murah dan stok tinggi.
Artinya, harga terjangkau + kualitas baik adalah kombinasi yang sangat disukai konsumen, terutama untuk kebutuhan sehari-hari.

4. Kategori Groceries vs Beauty
Groceries memiliki rata-rata stok terendah, mengindikasikan permintaan tinggi karena sifatnya yang esensial dan cepat habis. Sebaliknya, produk beauty cenderung memiliki stok tinggi dan bergerak lambat karena siklus pembelian lebih jarang. Namun, stok rendah juga bisa dipengaruhi oleh strategi penyimpanan, bukan semata-mata tingginya permintaan.

# Saran

1. Jangan Hanya Andalkan Harga Tinggi untuk Menciptakan Persepsi Kualitas
Walau korelasi ada, konsumen kini lebih cerdas. Investasikan pada kualitas nyata dan pengalaman pengguna, bukan sekadar positioning harga tinggi.

2. Evaluasi Produk Diskonan
Produk dengan diskon besar sebaiknya ditinjau ulang kualitasnya.
Pastikan layanan, kemasan, dan ekspektasi konsumen tetap terpenuhi, meski harganya lebih murah.

3. Fokus pada Produk Berkualitas dengan Harga Terjangkau
Produk seperti yang memiliki rating 4.93 dan harga 2.49 membuktikan bahwa value for money sangat dihargai.
Ini peluang untuk skala besar dan loyalitas pelanggan jika strategi harga dan kualitas dijaga.

4. Brand Monitoring
Brand seperti Knoll dan Velvet Touch layak dijadikan contoh sukses.
Sementara Essence dan Glamour Beauty butuh evaluasi mendalam: analisis review, peningkatan kualitas, atau reposisi pasar.

5. Kombinasikan Harga, Kualitas, dan Kategori
Insight gabungan antara harga, diskon, rating, dan kategori bisa dijadikan fondasi strategi promosi yang lebih relevan. Penekanan pada groceries sebagai produk kebutuhan rutin bisa mendongkrak volume penjualan dan kepuasan pelanggan jika kualitas tetap terjaga.
