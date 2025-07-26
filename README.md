# RPG-Character-Attributes

Proyek ini merupakan latihan analisis data menggunakan dataset "RPG Character Attributes" yang tersedia di Kaggle. Tujuannya adalah untuk menjelajahi hubungan antara berbagai atribut karakter dalam game RPG dan bagaimana atribut tersebut memengaruhi keberhasilan pemain dalam mengalahkan bos terakhir.

Dataset: [RPG Character Attributes Dataset on Kaggle](https://www.kaggle.com/datasets/jjasser/rpg-character-attributes-dataset)

Ringkasan Analisis
Dalam analisis ini, kami melakukan beberapa langkah untuk memahami data:

Visualisasi Data:

Distribusi: Kami memvisualisasikan distribusi kelas karakter dan status kemenangan melawan bos terakhir (FBoss). Kami juga melihat distribusi masing-masing atribut numerik seperti Armor, Weapon, Physical, Magic, dan Level.
Hubungan: Kami menggunakan scatter plot untuk melihat hubungan antar atribut numerik dan box plot untuk membandingkan atribut antar kelas karakter.
Analisis Statistik:

Matriks Korelasi: Kami menghitung dan memvisualisasikan matriks korelasi untuk melihat hubungan linear antar atribut. Ditemukan korelasi positif yang cukup kuat antara Level dengan Magic dan Physical.
Uji-t: Kami melakukan uji-t untuk membandingkan rata-rata Level antara pemain yang sudah dan belum mengalahkan bos terakhir. Hasilnya menunjukkan perbedaan yang signifikan secara statistik, yang mengindikasikan bahwa Level adalah faktor penting untuk keberhasilan.
Pemodelan Machine Learning:

Regresi Logistik: Kami membangun model Regresi Logistik untuk memprediksi status FBoss berdasarkan atribut numerik. Model ini mencapai akurasi yang sangat tinggi, menunjukkan bahwa atribut-atribut tersebut sangat prediktif.
Random Forest Classifier: Kami juga membangun model Random Forest untuk tugas yang sama. Model ini juga menunjukkan kinerja yang sangat baik dan memberikan gambaran yang lebih realistis tentang bagaimana model akan bekerja pada data baru.
Temuan Utama
Atribut karakter, terutama Level, memiliki hubungan yang kuat dengan kemampuan untuk menyelesaikan permainan (mengalahkan bos terakhir).
Ada perbedaan yang signifikan secara statistik dalam rata-rata Level antara pemain yang berhasil dan yang belum berhasil.
Model machine learning yang kami bangun mampu memprediksi keberhasilan pemain dengan akurasi yang tinggi, yang mengkonfirmasi pentingnya atribut karakter dalam game ini.

Tools:
- Python: Bahasa pemrograman utama yang digunakan untuk analisis.
- Pandas: Untuk manipulasi dan analisis data.
- Matplotlib & Seaborn: Untuk visualisasi data.
- Scikit-learn: Untuk pemodelan machine learning (Regresi Logistik dan Random Forest).
