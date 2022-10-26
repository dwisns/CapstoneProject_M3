# CapstoneProject_M3
Capstone Project Module 3 File ini dibuat untuk memenuhi kewajiban syarat kelulusan Purwadhika Job Connector Module 3 : Machine Learning

**Repo ini berisi:**
1. Gambar yang akan dimuat pada jupyter notebook (accuracy_precision_recall.png, SMOTE.png, NearMiss.png, Confusion_matrix.png)
2. Jupyter notebook file
3. Pickle save model pada machine learning (best_xgbc_capstone.sav)
4. Data set yang bersumber dari Kaggle (data_travel_insurance.csv)

**Pendahuluan :**  
Sebuah perusahaan yang bergerak di bidang `Asuransi Perjalanan International` ingin menawarkan produk asuransi kepada calon nasabah. Namun perusahaan ingin mengetahui nasabah mana yang berpotensi akan mengajukan Claim (mengalami resiko yang akan ditanggung perusahaan) dan yang tidak. Dilain sisi perusahaan juga ingin menekan biaya marketing (diskon yang diberikan) dikarenakan setengah dari calon nasabah diasumsikan tidak akan Claim dan setengah lagi diasumsikan bakal Claim.

**Pernyataan masalah :**
Pemberian diskon kepada calon nasabah secara acak menyebabkan tidak tepat sasaran. Kemungkinan terburuk yang terjadi adalah calon nasabah yang melakukan Claim namun mendapatkan diskon/potongan premi. Hal ini dapat berakibat fatal pada pendapatan Perusahaan Asuransi, dimana kas yang diterima perusahaan lebih kecil dari pengeluaran (yang disebabkan oleh resiko yang ditanggung / Claim).
Jika hal tersebut terjadi secara terus menerus, maka sebuah perusahaan asuransi akan tutup.

**Tujuan Pembuatan Model:**
Berdasarkan permasalahan tersebut, perusahaan ingin memiliki kemampuan untuk memprediksi kemungkinan suatu nasabah akan mengajukan Claim atau tidak. Sehingga selain dapat memberikan harga yang bersahabat kepada nasabah yang diprediksi tidak akan Claim dengan harapan menjadi nasabah setia, dan kita dapat meminimalisir terjadinya kerugian yang diakibatkan nasabah yang mengajukan Claim.

Dan perusahaan juga ingin mengetahui faktor apa yang membuat calon nasabah ingin mengajukan Claim atau tidak. Dengan begitu perusahaan bisa menyiapkan premi yang lebih tinggi agar perusahaan mendapatkan keuntungan juga.

**Proses Pendekatan :**
Untuk mengatasi hal ini, penulis ingin melakukan pembuatan Machine Learning yang dapat memprediksi suatu calon nasabah asuransi dengan data yang sudah ada. Dengan tujuan agar perusahaan dapat memberikan harga/premi yang tepat kepada calon nasabah asuransi. Machine Learning yang akan dihasilkan adalah Supervised Machine Learning beserta faktor apa yang berpengaruh terhadap target (Claim atau tidak)
