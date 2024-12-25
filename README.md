
# Klasifikasi Bioaktivitas Inhibitor IDO1

### Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasikan bioaktivitas senyawa obat yang berpotensi sebagai inhibitor *Indoleamine 2,3-dioxygenase 1 (IDO1)* menggunakan model pembelajaran mesin. IDO1 adalah enzim penting dalam regulasi imun dan menjadi target terapeutik utama dalam pengobatan kanker dan penyakit autoimun. 

Melalui analisis data molekuler, proyek ini membantu mengidentifikasi senyawa aktif dan fitur molekuler yang signifikan, sekaligus membandingkan performa beberapa model pembelajaran mesin untuk menemukan prediktor terbaik.

### Fitur Utama
- **Klasifikasi Bioaktivitas**: Prediksi senyawa aktif atau tidak aktif berdasarkan deskriptor molekuler Lipinski.
- **Analisis Fitur Signifikan**: Identifikasi sifat molekuler utama yang berkontribusi pada penghambatan IDO1.
- **Perbandingan Model Pembelajaran Mesin**: Evaluasi performa model seperti KNN, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM, Neural Networks, dan XGBoost.

### Dataset
- Dataset diambil dari *ChEMBL Database*, terdiri dari data bioaktivitas senyawa terhadap IDO1.
- **Variabel Target**: Bioaktivitas (aktif, tidak aktif).
- **Fitur Deskriptor Molekuler**:
  - Berat Molekul (MW)
  - LogP (lipofilisitas)
  - Jumlah Donor Ikatan Hidrogen (NumHDonors)
  - Jumlah Akseptor Ikatan Hidrogen (NumHAcceptors)

### Metodologi
1. **Pra-pemrosesan Data**: Pembersihan data, penskalaan fitur, dan pembuatan label target.
2. **Eksplorasi Data**: Analisis hubungan antara fitur dan bioaktivitas senyawa.
3. **Pelatihan Model**: 
   - Implementasi berbagai model pembelajaran mesin.
   - Validasi silang 10-lipat untuk memastikan keandalan hasil.
4. **Evaluasi Model**: Metode seperti akurasi dan F1-Macro digunakan untuk membandingkan model.

### Hasil Utama
- **Decision Tree** adalah model terbaik dengan rata-rata akurasi tertinggi (0.89).
- Fitur **NumHDonors** dan **MW** adalah faktor signifikan dalam prediksi bioaktivitas.
- Analisis statistik menunjukkan relevansi kuat fitur dengan aktivitas inhibitor IDO1.

### Kontributor:
- Ivander Perdana Mokhtar  
- Rika Ajeng Finatih  
- Sarah Natalia Geraldine  
- Anita Rahma Pramoda Cahyani  
- Putri Maulida Chairani  
- Ima Alifah  
---

