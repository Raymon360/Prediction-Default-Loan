# Prediction-Default-Loan

## Tentang Project
   Proyek ini bertujuan untuk mengurangi risiko kredit dengan memprediksi apakah peminjam akan melunasi pinjaman mereka secara penuh atau tidak. Model yang akurat dan andal dapat membantu mengidentifikasi peminjam berisiko tinggi, membantu membuat keputusan pemberian pinjaman yang lebih baik dan meningkatkan strategi manajemen risiko.

## Fitur
Prediksi risiko kredit
Identifikasi peminjam berisiko tinggi.
Model akurat dan andal

## Metode
* Proyek ini menggunakan metode CRISP-DM yang melibatkan pemahaman bisnis dan data, kemudian persiapan data, pemodelan, dan akhirnya evaluasi model.
* Dalam proses pemilihan fitur, metode yang digunakan adalah metode Boruta.
* Model yang digunakan dalam proyek ini adalah Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, dan XGBoosting.

## Hasil
Tabel Hasil Evaluasi Model
|Model     |	Akurasi (%)     |	Presisi (%)     |	Recall (%)     |	F1-Score (%)     |	AUC Score (%)
| ----- | ----- | ----- | ----- | ----- | -----|
|Logistic Regression|	88.32|	85.67|	90.45|	87.99|	92.12|
|Decision Tree|	92.76|	91.23|	93.45|	92.33|	95.67|
|Random Forest|	97.04|	99.55|	94.51|	96.96|	99.54|
|Gradient Boosting|	93.67|	94.11|	92.23|	93.16|	97.45|
|XGBoosting|	94.32|	95.34|	93.21|	94.26|	98.12|

  
  Dari lima algoritma yang dievaluasi, empat di antaranya mencapai akurasi lebih dari 90%. Algoritma tersebut adalah Decision Tree, Random Forest, Gradient Boosting, dan XGBoosting. Di antara algoritma-algoritma ini, Random Forest dipilih karena tingkat akurasinya yang superior sebesar 97.04%, menjadikannya model yang paling akurat. Selain itu, Random Forest menunjukkan presisi tinggi sebesar 99.55% dan recall sebesar 94.51%. F1-Score yang dihasilkan adalah 96.96%, menunjukkan kinerja yang seimbang antara presisi dan recall. Lebih jauh lagi, model ini mencapai Skor AUC sebesar 99.54%, yang menyoroti kemampuannya yang luar biasa untuk membedakan antara kelas positif dan negatif, serta mencerminkan kinerja keseluruhan model yang kuat.
