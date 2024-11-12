# Ch.-2-Machine-Learning-and-Deep-Learning
tugas MSIB Artificial Intelligence Track • Startup Campus, Indonesia (Assignment 2 - Machine Learning &amp; Deep Learning)

Machine Learning (ML) dan Deep Learning (DL) adalah dua cabang dari kecerdasan buatan (AI) yang memungkinkan komputer belajar dari data. Namun, keduanya memiliki perbedaan dalam kompleksitas dan struktur algoritma yang digunakan.

1. Machine Learning (Pembelajaran Mesin)

Machine Learning adalah bidang dalam AI yang memungkinkan sistem belajar dari data, mengenali pola, dan membuat keputusan tanpa diprogram secara eksplisit. Algoritma ML bekerja dengan "belajar" dari data yang diberikan, membangun model yang bisa digunakan untuk memprediksi atau mengelompokkan data baru. Beberapa konsep dasar dalam ML:

- Algoritma Supervised Learning (Pembelajaran Terawasi): Algoritma ini menggunakan data yang sudah diberi label (data di mana hasil akhirnya sudah diketahui) untuk memprediksi atau mengelompokkan data baru. Contohnya, model dapat dilatih untuk memprediksi harga rumah berdasarkan data harga sebelumnya.
  
- Algoritma Unsupervised Learning (Pembelajaran Tak Terawasi): Algoritma ini digunakan untuk mengelompokkan atau menemukan pola dalam data yang tidak diberi label, seperti mengelompokkan pelanggan berdasarkan pola belanja mereka.

- Reinforcement Learning: Model ini bekerja dengan memberikan "hadiah" atau "hukuman" kepada agen yang bertugas melakukan suatu tugas, misalnya bermain game. Algoritma ini belajar dari pengalaman untuk meningkatkan performanya.

Beberapa algoritma umum dalam Machine Learning mencakup regresi linier, pohon keputusan (*decision tree*), k-nearest neighbors (KNN), dan Support Vector Machine (SVM).

 2. Deep Learning (Pembelajaran Mendalam)

Deep Learning adalah sub-bidang dari Machine Learning yang fokus pada model berbasis jaringan saraf tiruan (neural network) dengan banyak lapisan. Deep Learning cocok untuk data dalam jumlah besar dan kompleksitas tinggi. Jaringan neural dalam deep learning terinspirasi dari cara kerja otak manusia, di mana neuron-neuron tiruan dihubungkan dan berkomunikasi satu sama lain.

Karakteristik Deep Learning:

- Multi-Layered Neural Networks (Jaringan Saraf dengan Banyak Lapisan): Deep Learning menggunakan jaringan saraf yang sangat dalam, yang terdiri dari beberapa lapisan (layer) yang dikenal sebagai "lapisan tersembunyi". Setiap lapisan ini mengekstrak fitur dari data, semakin dalam jaringan, semakin kompleks fitur yang diekstraksi.

- Convolutional Neural Networks (CNN): CNN umumnya digunakan dalam pemrosesan gambar atau data visual. Jaringan ini dirancang untuk mengenali pola dalam gambar, seperti tepi, warna, atau bentuk objek, dan digunakan dalam aplikasi seperti pengenalan wajah dan klasifikasi gambar.

- Recurrent Neural Networks (RNN): RNN cocok untuk data urutan atau sekuensial, seperti teks atau audio, karena mampu mengingat informasi dari data sebelumnya. Ini sangat berguna dalam aplikasi pemrosesan bahasa alami, seperti penerjemahan mesin atau pengenalan suara.

- Self-Learning dan Feature Extraction: Berbeda dengan Machine Learning, di mana fitur sering kali harus didefinisikan oleh manusia, Deep Learning mampu secara otomatis mengekstraksi fitur dari data.

Perbandingan Machine Learning dan Deep Learning:

| Aspek                | Machine Learning                         | Deep Learning                           |
|----------------------|------------------------------------------|-----------------------------------------|
| Kebutuhan Data   | Memerlukan data dalam jumlah moderat     | Membutuhkan data dalam jumlah sangat besar |
| Kompleksitas Model | Algoritma sederhana hingga kompleks     | Sangat kompleks, jaringan saraf dalam   |
| Waktu Latih      | Relatif cepat                           | Lama karena jaringan saraf yang dalam   |
| Penggunaan Sumber Daya | Lebih sedikit                        | Sangat besar, terutama dalam GPU       |
| Interpretasi    | Mudah diinterpretasi                    | Sulit diinterpretasi, seperti "kotak hitam" |

Aplikasi ML dan DL dalam Kehidupan Nyata:
- Machine Learning: Prediksi cuaca, analisis risiko finansial, filter spam pada email, diagnosis kesehatan sederhana.
- Deep Learning: Pengenalan wajah, mobil otonom, penerjemahan bahasa, analisis medis lanjutan, asisten virtual.

Kesimpulan: Machine Learning adalah pendekatan umum untuk membangun model AI, sementara Deep Learning adalah teknik yang lebih khusus dan intensif, ideal untuk data dalam jumlah besar dan tugas yang membutuhkan analisis mendalam.
