# Suvervisor-Vektor-Machine-Suvervisor-Vector-Regretio

Machine Learning: Diabetes, Salary Prediction, dan Support Vector Machine (SVM)
Deskripsi Proyek
Proyek ini berisi tiga materi pembelajaran Machine Learning menggunakan
Python dan Jupyter Notebook. Setiap materi menerapkan metode yang
berbeda untuk mengolah data, membangun model, dan menghasilkan prediksi
atau visualisasi.
Daftar Materi
1. Klasifikasi Diabetes (diabetes.ipynb)
Materi ini menggunakan algoritma Support Vector Classifier (SVC)
untuk melakukan klasifikasi berdasarkan dataset diabetes.

Tahapan proses: 1. Mengimpor library Pandas dan membaca dataset
diabetes.csv. 2. Melihat beberapa data awal menggunakan head() dan
informasi dataset menggunakan info(). 3. Memisahkan delapan atribut
pertama sebagai fitur (X) dan kolom Outcome sebagai label (y). 4.
Melakukan standarisasi fitur menggunakan StandardScaler. 5. Membagi
data menjadi data training dan testing dengan proporsi 67% dan 33%. 6.
Membuat serta melatih model SVC menggunakan data training. 7.
Mengevaluasi model dengan melihat skor akurasi pada data testing.

Tujuan: Mempelajari proses klasifikasi data diabetes menggunakan
algoritma SVC.
2. Prediksi Gaji (salary data.ipynb)
Materi ini menggunakan algoritma Support Vector Regression (SVR)
untuk memprediksi gaji berdasarkan lama pengalaman kerja.

Dataset: - Salary_Data.csv - YearsExperience: jumlah tahun
pengalaman kerja. - Salary: nilai gaji.

Tahapan proses: 1. Mengimpor Pandas dan membaca dataset
Salary_Data.csv. 2. Memeriksa informasi serta beberapa baris awal
dataset. 3. Memisahkan YearsExperience sebagai fitur (X) dan
Salary sebagai target (y). 4. Mengubah fitur menjadi array NumPy
dengan bentuk dua dimensi. 5. Membuat model SVR dengan parameter
C=1000, gamma=0.05, dan kernel='rbf'. 6. Melatih model menggunakan
data yang tersedia. 7. Menampilkan data aktual dan hasil prediksi dalam
bentuk grafik.

Tujuan: Mempelajari regresi menggunakan SVR untuk memperkirakan
nilai gaji berdasarkan pengalaman kerja.
3. Support Vector Machine (svm.ipynb)
Materi ini membahas penerapan Support Vector Machine (SVM)
menggunakan dataset sederhana yang menggambarkan hubungan jam belajar
dan jam tidur dengan hasil kelulusan ujian.

Atribut dataset: - x1: Study Hours (jam belajar). - x2: Sleep
Hours (jam tidur). - y: Passed Exam, dengan nilai 1 untuk lulus dan
-1 untuk tidak lulus.

Tahapan proses: 1. Mengimpor NumPy, Matplotlib, dan SVM dari
Scikit-learn. 2. Membuat dataset sederhana berisi jam belajar, jam
tidur, dan label hasil ujian. 3. Menggabungkan atribut jam belajar dan
jam tidur menggunakan np.column_stack(). 4. Membuat model SVM dengan
kernel linear. 5. Melatih model menggunakan data melalui fungsi fit().
6. Mengambil nilai koefisien dan intercept untuk menentukan decision
boundary. 7. Memvisualisasikan data, decision boundary, dan kategori
hasil ujian menggunakan Matplotlib.

Tujuan: Memahami cara kerja klasifikasi SVM dalam memisahkan dua
kelompok data menggunakan decision boundary.
Teknologi dan Library
Library yang digunakan dalam ketiga materi:
- Python --- bahasa pemrograman.
- Pandas --- membaca dan mengolah dataset.
- NumPy --- pengolahan data numerik dan array.
- Matplotlib --- membuat visualisasi grafik.
- Scikit-learn --- membangun model Machine Learning.
- Jupyter Notebook --- menjalankan kode secara interaktif.
Instalasi Library
Pastikan Python dan Jupyter Notebook sudah terpasang. Instal library
yang diperlukan dengan perintah:
pip install pandas numpy matplotlib scikit-learn jupyter
Cara Menjalankan
1. Unduh atau salin seluruh file notebook dan dataset yang diperlukan.
2. Simpan file dalam folder proyek yang sama.
3. Pastikan dataset diabetes.csv tersedia untuk materi klasifikasi
   diabetes.
4. Pastikan dataset Salary_Data.csv tersedia untuk materi prediksi
   gaji.
5. Buka terminal pada folder proyek.
6. Jalankan Jupyter Notebook dengan perintah:
jupyter notebook
7. Buka file notebook yang ingin dipelajari.
8. Jalankan setiap cell kode secara berurutan.
Struktur Folder
Machine-Learning/
│
├── README.md
├── diabetes.ipynb
├── salary data.ipynb
├── svm.ipynb
├── diabetes.csv
└── Salary_Data.csv
Catatan: File CSV merupakan dataset pendukung dan perlu disediakan
secara terpisah. Notebook tidak menyertakan dataset tersebut.
Kesimpulan
Ketiga materi memperkenalkan penerapan Machine Learning menggunakan
Python. Materi diabetes menerapkan klasifikasi menggunakan SVC, materi
salary data menerapkan regresi menggunakan SVR, sedangkan materi SVM
menjelaskan klasifikasi dua kelompok data melalui decision boundary.
Melalui ketiga notebook ini, dapat dipelajari tahapan membaca dataset,
mengolah fitur, membangun model, melakukan pelatihan, evaluasi, dan
visualisasi hasil.
