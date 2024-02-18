# NLP-projects

Proyek ini dibuat selama menjalankan AI mastery program dari Orbit Future Academy. 
Cyberbullying merupakan hal yang saat ini sering sekali terjadi terutama pada fitur komentar sosial media. Tak jarang pengguna sosial media enggan membuka fitur komentar untuk "menghindari" komentar negatif. Bahkan, pada aplikasi instagram sudah terdapat fitur mematikan instagram. Padahal tidak semua komenar tersebut bersifat negatif. Melihat bahaya cyberbullying yang tentu meresahkan banyak orang dikarenakan dampak yang ditimbulkan, maka dari itu dilakukan suatu analisis sentimen pada kolom komentar Instagram yang berupaya untuk mengetahui sentimen dari setiap komentar. Sebagai tambahan. saya ingin melakukan identifikasi komentar positif dan negatif terhadap suatu komentar pada salah satu postingan instagram.

Dataset yang digunakan diambil dari akun github bernama rizalespe. Spesifikasi dari data tersebut dapat dilihat sebagai berikut :

1. Dikumpulkan dari posingan pada instagram
2. Dilabeli secara manual oleh pemilik dataset dengan label positif dan negatif
3. Jumlah total dataset adalah 400 komentar
4. Pembagian masing masing kelas label selumlah 200 komentar positif dan negatif.

Text preprocessing yang dilakukan diantaranya casefolding, word normalization, Filtering (Stopword Removal), dan stemming.

Model yang digunakan adalah Machine Learning Algoritma Naive Bayes. Naive Bayes adalah metode yang cocok untuk klasifikasi biner dan multiclass. Metode yang juga dikenal sebagai Naive Bayes Classifier ini menerapkan teknik supervised klasifikasi objek di masa depan. Tujuan metode ini adalah mengklasifikasikan probabilitas berdasarkan pembelajaran mesin atas probabilitas lain.

Beberapa keunggulan dari metode ini diantaranya :

sederhana dan mudah diterapkan,
tidak membutuhkan banyak data pelatihan,
menangani data kontinu dan diskrit,
sangat skalabel dengan jumlah prediktor dan titik data,
serta cepat dan dapat digunakan untuk membuat prediksi realtime.
Metode ini dipilih karena dapat mengklasifikasikan suatu dataset sekaligus memprediksi kelas untuk input baru.

Dataset yang digunakan juga hanya terdiri dari 400 data dan tidak terlalu banyak, sehingga metode ini dapat dikatakan sebagai metode yang paling sesuai.

Kesimpulan dari pengujian di atas didapatkan hasil akurasi tertinggi sebesar 91,25% pada komposisi 80% untuk data latih dan 20% untuk data uji. Selain itu, didapat wordcloud di atas untuk menampilkan kata yang paling sering muncul di kedua sentiment.

for better experience use  https://colab.research.google.com/drive/1Wt12Vu7A-yb12cx-Zwwj668AQ4j7Hq5p?usp=sharing
or watch my explanation at https://www.youtube.com/watch?v=b1GWT1hZuPg&t=84s
