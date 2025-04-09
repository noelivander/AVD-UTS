# Prediksi Nilai Siswa Berdasarkan Waktu Belajar dan Jumlah Mata Kuliah Menggunakan Decision Tree Regression

By :
Noel Ivander Pusung (221031002)

Dalam dunia pendidikan, prestasi akademik siswa dipengaruhi oleh berbagai faktor, salah satunya adalah durasi belajar dan jumlah mata kuliah yang diambil. Analisis ini bertujuan untuk memahami sejauh mana kedua variabel tersebut memengaruhi nilai akhir siswa menggunakan pendekatan Decision Tree Regression. Dengan memanfaatkan data historis, model ini dibangun untuk mengidentifikasi pola hubungan antara input (time study dan number of courses) terhadap output (nilai). Pendekatan ini penting agar institusi pendidikan dapat membuat keputusan berbasis data, memberikan intervensi tepat waktu, serta membantu siswa dalam mengatur strategi belajar yang lebih efektif.

Source : https://www.kaggle.com/datasets/yasserh/student-marks-dataset?resource=download

# KESIMPULAN

Berdasarkan hasil pengujian model menggunakan metode Decision Tree Regression dengan proporsi data latih 70% dan data uji 30%, diperoleh nilai R² sebesar 0.991, yang menunjukkan bahwa model mampu menjelaskan sekitar 99,1% variasi nilai siswa (Marks) berdasarkan jumlah mata kuliah (number_courses) dan terutama durasi waktu belajar (time_study). Kedua fitur yang digunakan (time_study dan number_courses) secara bersamaan memberikan kontribusi besar terhadap prediksi nilai siswa. Nilai R² yang sangat tinggi ini mengindikasikan bahwa model memiliki performa yang sangat baik dalam memprediksi nilai siswa pada data uji. Dengan tingkat akurasi yang tinggi tersebut, Decision Tree Regression dapat dijadikan pendekatan yang efektif untuk memprediksi nilai siswa berdasarkan faktor-faktor yang diberikan.

# REKOMENDASI

Melihat performa model yang tinggi, pendekatan Decision Tree Regression ini dapat dijadikan alat bantu dalam sistem monitoring pembelajaran untuk memprediksi dan mengevaluasi capaian akademik mahasiswa secara objektif. Dosen atau institusi pendidikan dapat memanfaatkan model ini untuk memberikan intervensi lebih awal kepada siswa yang memiliki risiko nilai rendah. Selain itu, disarankan agar siswa lebih memperhatikan manajemen waktu belajar, karena waktu belajar terbukti berkontribusi penting terhadap hasil nilai. Untuk pengembangan ke depan, model dapat disempurnakan dengan menambahkan variabel lain seperti minat belajar, kehadiran, atau aktivitas pembelajaran daring untuk meningkatkan ketepatan prediksi.
