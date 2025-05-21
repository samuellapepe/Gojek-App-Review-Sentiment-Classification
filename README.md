# **Gojek App Review Sentiment Classification**

Proyek ini bertujuan untuk melakukan klasifikasi sentimen terhadap ulasan pengguna aplikasi Gojek yang diambil dari Google Play Store. Dengan memanfaatkan teknik Natural Language Processing (NLP) dan algoritma XGBoost, proyek ini menghasilkan model yang mampu membedakan apakah suatu ulasan bersifat positif atau negatif, yang berguna untuk meningkatkan kualitas layanan berdasarkan feedback pelanggan.

## **Tools & Library**
* Python
* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn
* XGBoost
* imbalance-learn
* NLTK & Sastrawi

## **Fitur**
* Pengumpulan data: ulasan aplikasi Gojek dari Google Play Store
* Preprocessing teks: cleaning, normalisasi kata tidak baku, penghapusan stopwords, stemming
* Teks eksplorasi: melihat distribusi sentimen
* Ekstraksi fitur: TF-IDF
* Penanganan data imbalance: SMOTE & `scale_pos_weight`
* Modeling: XGBoost Classifier
* Evaluasi model: confusion matrix, akurasi, precision, recall, F1-score

## **Struktur File**
* Portofolio Module 3 - Ayes.ipynb : Notebook utama yang berisi seluruh proses modeling.
* gojek_app_review.csv : dataset yang review pengguna aplikasi Gojek.

## **Link Terkait**
* File gojek_app_review. csv dapat di download [disini.](https://drive.google.com/file/d/1xtf8MtCXK-CpZqqVpTrEmB_xvGI0H0LF/view?usp=sharing)

## **Lisensi**
Portofolio ini merupakan project Bootcamp JCDS 2804 Purwadhika.
