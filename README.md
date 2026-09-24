# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Perusahaan memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

Untuk mencegah hal ini semakin parah, manajer departemen HR ingin meminta bantuan Anda mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate tersebut. Selain itu, ia juga meminta Anda untuk membuat business dashboard untuk membantunya memonitori berbagai faktor tersebut. 

### Permasalahan Bisnis

Terdapat beberapa permasalahan bisnis yang akan menjadi tujuan dari analisis ini yakni

1. Bagaimana kondisi attrition rate karyawan di perusahaan Jaya Jaya Maju?
2. Faktor-faktor apa yang paling berpengaruh terhadap keputusan karyawan untuk keluar dari perusahaan
3. Bagaimana menyajikan informasi tersebut dalam bentuk dashboard yang dapat membantu departemen HR memantau faktor-faktor penyebab attrition?

### Cakupan Proyek
Proyek ini mencakup beberapa tahapan yang dilakukan, meliputi:

1. Memahami permasalahan bisnis perusahan
2. Menyiapkan library, serta dataset yang akan digunakan
3. Melakukan data understanding dan data preparation pada dataset 
4. Membersihkan data dengan menghapus missing values pada kolom attrition
5. Melakukan analisis terhadap beberapa faktor yang kemungkinan berkaitan dengan attrition
6. Membuat business dashboard dengan Metabase untuk memvisualisasikan hasil dari analisis
7. Menyusun rekomendasi berdasarkan hasil analisis

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup environment:

```bash
pip install -r requirements.txt
```

## Business Dashboard

Business dashboard dibuat dengan menggunakan Metabase untuk membantu departement HR dalam memantau tingkat attrition perusahaan serta faktor-faktor yang berkaitan dengan keluarnya karyawan.

Dashboard tersebut terdiri dari beberapa visualisasi yakni:  
- Total Employee
- Total Attrition
- Attrition Rate
- Attrition Rate berdasarkan Department
- Attrition Rate berdasarkan Work-Life Balance
- Attrition Rate berdasarkan Job Involvement
- Average Monthly Income berdasarkan Job Role dan Attrition Status
- Attrition Rate berdasarkan Job Role dan OverTime
- Attrition Rate by JobSatisfiction and JobRole
Dashboard dapat digunakan HR dalam mengidentifikasi kelompok karyawan yang memiliki tingkat attrition yang tinggi sehingga dapat menjadi dasar untuk menentukan strategi selanjutnya.

## Conclusion
Berdasarkan hasil analisis yang telah dilakukan, diperoleh beberapa informasi yakni:
1. Attrition rate perusahaan mencapai nilai 16,92%, nilai tersebut lebih tinggi dari target perusahaan yakni senilai <10%
2. Department Sales merupakan department dengan attrition rate tertinggi yakni 20,69%, nilai tersebut lebih tinggi dibandingkan dengan department lainnya
3. Karyawan yang bekerja overtime memiliki attrition rate yang lebih tinggi dibandingkan karyawan yang tidak overtime.
4. Karyawan dengan Job Involement yang rendah menunjukkan attrition rate yang lebih tinggi.
5. Karyawan yang memiliki Work Life Balance yang rendah berkaitan dengan tingginya nilai attrition rate
6. Monthly Income tidak menunjukkan pola yang konsisten terhadap attrition pada seluruh Job Role sehingga kemungkinan bukan merupakan faktor utama yang memengaruhi keputusan karyawan untuk keluar

### Rekomendasi Action Items (Optional)

Terdapat beberapa rekomendasi action items yang dapat dilakukan perusahaan untuk mengurangi tingkat attrition rate pada perusahaan yakni sebagai berikut

1. Mengurangi beban lembur pada semua JobRole yang ada
2. Meningkatkan program work-life balance melalui kebijakan kerja yang lebih fleksibel dan dukungan terhadap kesejahteraan karyawan
3. Meningkatkan employee engagement bagi karyawan dengan Job Involvement rendah melalui pelatihan, mentoring, dan pengembangan karier
4. Memberikan perhatian khusus pada Department Sales dengan melakukan evaluasi terhadap beban kerja, lingkungan kerja, dan strategi retensi karyawan

## Akses Dashboard Metabase

Email: putripitamutia99@gmail.com

Password: HPsAy9CZYI?XrF