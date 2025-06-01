# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech
Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding
Jaya Jaya Maju merupakan perusahaan multinasional yang telah berdiri sejak tahun 2000 dan kini memiliki lebih dari 1.000 karyawan yang tersebar di seluruh wilayah Indonesia. Meskipun telah berkembang menjadi perusahaan besar, Jaya Jaya Maju menghadapi tantangan serius dalam hal pengelolaan sumber daya manusia, yang terlihat dari tingginya angka attrition rate (rasio karyawan keluar terhadap total karyawan) yang mencapai lebih dari 10%. Oleh karena itu, perlu dianalisis faktor-faktor yang mempengaruhi tingkat keluarnya karyawan untuk membantu departemen HR dalam mengurangi tingkat attrition.

## Permasalahan Bisnis
Tingginya attrition rate menandakan adanya masalah internal yang belum teridentifikasi atau ditangani dengan tepat. Tanpa intervensi yang tepat, masalah ini berpotensi menimbulkan kerugian finansial akibat biaya rekrutmen dan pelatihan ulang, maupun hilangnya karyawan berpengalaman dan berdampak pada produktivitas.

## Cakupan Proyek
1. Mengolah data karyawan untuk membangun model dengan menggunakan algoritma Logistic Regression.
2. Membuat dashboard untuk memvisualisasikan dan menganalisis faktor yang mempengaruhi attrition.  
3. Memberikan rekomendasi action items berdasarkan hasil analisis yang dilakukan.

## Persiapan 
Sumber Data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup Environment: 

** Install dependencies **

pip install -r requirements.txt

### Buka dan Jalankan Attrition_Rate.ipynb
1. Pastikan dependensi yang ada dalam daftar requirements.txt telah terinstall.
2. Buka dan jalankan seluruh isi Attrrition_Rate.ipynb dengan menggunakan Google Colab atau IDE Python lainnya yang mendukung notebook.
3. Temukan visualisasi dan insight yang diperoleh untuk menemukan pola-pola yang relevan berdasarkan hasil analisis.

### Buka dan Jalankan prediction.py
1. Data yang digunakan untuk prediksi, bisa disesuaikan sendiri inputannya. 
2. Upload file model dan scaler pada direktori yang sama dengan script prediction.py 
3. Jalankan prediction.py di IDE yang mendukung Python seperti Google Colab. Hasil prediksi akan langsung ditampilkan di terminal.

### Menjalankan Dashboard 
Dashboard dibuat dengan menggunakan tableu, sehingga untuk melihatnya dapat melalui URL dashboard yang telah dicantumkan.

## Business Dashboard
Berikut URL dashboard:

**https://public.tableau.com/app/profile/nurul.fatimah4077/viz/Attrition_17484346710410/Dashboard1
https://public.tableau.com/app/profile/nurul.fatimah4077/viz/Attrition_17484346710410/Dashboard2
https://public.tableau.com/app/profile/nurul.fatimah4077/viz/Attrition_17484346710410/Dashboard3
https://public.tableau.com/app/profile/nurul.fatimah4077/viz/Attrition_17484346710410/Dashboard4**

### Faktor Utama
1. Attrition berdasarkan faktor demografis dan penghasilan (dashboard 1)
Pegawai muda rata-rata umur 33 dengan kompensasi rendah dan beban perjalanan bisnis yang tinggi cenderung lebih mudah keluar dari perusahaan.
2. Attrition berdasarkan faktor karir dan pengembangan professional (dashboard 2)
Pegawai yang cenderung keluar adalah pegawai mid-level (pengalaman 8 tahun, masa kerja 5 tahun di perusahaan) yang berada di departemen R&D, memiliki riwayat sering pindah kerja, dan relatif baru di posisi saat ini. 
3. Attrition berdasarkan faktor kehidupan pribadi dan work-life balance (dashboard 3)
Pegawai yang rentan keluar adalah pegawai lajang, sering lembur, dan work-life balance level 3.
4. Attrition berdasarkan faktor kepuasan, pendidikan dan job role (dashboard 4)
Pegawai yang cenderung keluar memiliki kepuasan yang rendah pada lingkungan kerja, pekerjaan, dan hubungan kerja. Selain itu pegawai dengan lulusan Life Sciences dan Technical Degree juga lebih mudah keluar. Pegawai dengan role Sales Executive dan Laboratory Technician juga memiliki tingkat attrition yang tinggi.

## Conclusion
Berdasarkan empat perspektif yang ditampilkan dalam dashboard, ditemukan bahwa attrition karyawan dipengaruhi oleh kombinasi faktor demografis, karier, kehidupan pribadi, serta kepuasan kerja dan latar belakang pendidikan. Rincian kesimpulan sebagai berikut:

1. Pegawai muda (rata-rata usia 33 tahun) dengan kompensasi rendah dan beban perjalanan dinas yang tinggi cenderung lebih mudah keluar dari perusahaan. Hal ini menunjukkan bahwa ketimpangan antara beban kerja dan kompensasi menjadi faktor pendorong utama dalam keputusan mereka untuk meninggalkan perusahaan.

2. Pegawai mid-level dengan pengalaman sekitar 8 tahun, masa kerja 5 tahun di perusahaan, sering berpindah kerja, dan relatif baru di posisi saat ini (khususnya di departemen R&D) menunjukkan tingkat attrition yang tinggi. Ini menunjukkan adanya kebutuhan akan jalur karier yang jelas dan pengembangan profesional yang lebih baik bagi karyawan berpengalaman.

3. Pegawai yang lajang, sering lembur, dan memiliki skor work-life balance yang rendah (level 3) cenderung lebih mudah keluar. Ini menandakan bahwa ketidakseimbangan antara kehidupan kerja dan pribadi menjadi penyebab signifikan attrition, terutama bagi karyawan yang belum memiliki komitmen keluarga.

4. Tingkat attrition tinggi juga ditemukan pada karyawan dengan kepuasan rendah terhadap lingkungan kerja, pekerjaan, dan hubungan kerja. Selain itu, lulusan dari jurusan Life Sciences dan Technical Degree lebih cenderung keluar. Role tertentu seperti Sales Executive dan Laboratory Technician juga memiliki attrition rate yang tinggi, mengindikasikan bahwa karakteristik pekerjaan atau tekanan dalam posisi tersebut mungkin menjadi faktor risiko.

## Rekomendasi Action Items
- Meningkatkan kompensasi dan fleksibilitas kerja, terutama untuk pegawai muda.
- Menyediakan jalur karier dan pengembangan profesional yang jelas, khususnya untuk pegawai di R&D.
- Mendorong kebijakan work-life balance yang sehat, termasuk pengurangan lembur.
- Meningkatkan kualitas lingkungan kerja dan hubungan antarpegawai.
- Melakukan evaluasi ulang terhadap job role dengan tingkat attrition tinggi dan memberikan dukungan tambahan bagi pegawai di posisi tersebut. 



