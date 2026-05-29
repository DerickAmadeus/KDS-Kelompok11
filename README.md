
# Deteksi Transisi Respirasi Aerobik-Anaerobik dengan Bi-LSTM

Proyek ini bertujuan untuk mendeteksi transisi antara fase respirasi aerobik dan anaerobik berdasarkan Respiratory Exchange Ratio (RER) menggunakan arsitektur Long Short-Term Memory (LSTM), khususnya Bi-LSTM.



## Dataset
- Sumber: PhysioNet Treadmill Exercise Cardiorespiratory Dataset
- File yang digunakan: test_measure.csv, subject-info.csv
## Langkah Utama Proyek
1. **Import Library**  
	Menggunakan Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, dan TensorFlow.

2. **Load Data & Pembuatan Target**  
	- Membaca data pengukuran.
	- Menghitung RER dan label anaerobik (RER ≥ 1.0).

3. **Exploratory Data Analysis (EDA)**  
	- Visualisasi distribusi kelas, tren RER, dan korelasi fitur.

4. **Feature Engineering & Preprocessing**  
	- Menambah fitur moving average.
	- Normalisasi dan sliding window untuk data time series.
	- Penanganan NaN/Inf.

5. **Modeling (Bi-LSTM)**  
	- Arsitektur Bi-LSTM dengan regularisasi dan gradient clipping.
	- Penanganan class imbalance dengan class_weight.

6. **Evaluasi**  
	- Akurasi, classification report, confusion matrix, dan visualisasi prediksi vs aktual.
## Authors
- [@Wilsonn23](https://github.com/Wilsonn23)- 18223012
- [@BrandonTheodore](https://github.com/BrandonTheodore) - 18223020
- [@Raflind](https://github.com/Raflind) - 18223038
- [@DerickAmadeus](https://www.github.com/DerickAmadeus) - 18223090