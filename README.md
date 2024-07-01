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
|Model|	Accuracy Score|	Training Score|	Test Score|	Precision Score|	Recall Score|
| ----- | ----- | ----- | ----- | ----- | -----|
|Logistic Regression|	78.37|	78.20|	78.37|	83.00|	71.36|
|Linear SVM|	78.32|	78.17|	78.32|	83.27|	70.89|
|Decision Tree|	92.02|	100.00|	92.02|	91.18|	93.04|
|Random Forest|	97.03|	100.00|	97.03|	99.49|	94.55|
|Gradient Boosting|	92.26|	92.29|	92.26|	97.73|	86.53|
|XG Boost|	96.43|	96.44|	96.43|	99.91|	92.94|

  
  Dari lima algoritma yang dievaluasi, empat di antaranya mencapai akurasi lebih dari 90%. Algoritma tersebut adalah Decision Tree, Random Forest, Gradient Boosting, dan XGBoosting. Di antara algoritma-algoritma ini, Random Forest dipilih karena tingkat akurasinya yang superior sebesar 97.04%, menjadikannya model yang paling akurat. Selain itu, Random Forest menunjukkan presisi tinggi sebesar 99.55% dan recall sebesar 94.51%. F1-Score yang dihasilkan adalah 96.96%, menunjukkan kinerja yang seimbang antara presisi dan recall. Lebih jauh lagi, model ini mencapai Skor AUC sebesar 99.54%, yang menyoroti kemampuannya yang luar biasa untuk membedakan antara kelas positif dan negatif, serta mencerminkan kinerja keseluruhan model yang kuat.
