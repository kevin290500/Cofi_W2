# Business Understanding

Jaya Jaya Maju adalah sebuah perusahaan multinasional yang telah beroperasi sejak tahun 2000. Perusahaan ini memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. Meskipun telah menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih menghadapi tantangan dalam mengelola karyawan, yang tercermin dalam tingginya tingkat attrition rate mereka. Attrition rate adalah rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan. Dalam konteks ini, attrition rate yang tinggi mengindikasikan bahwa banyak karyawan yang meninggalkan perusahaan.

# Permasalahan Bisnis

Tantangan utama yang dihadapi oleh Jaya Jaya Maju adalah tingginya attrition rate. Tingkat pergantian karyawan yang tinggi dapat memiliki dampak negatif yang signifikan pada kinerja perusahaan, termasuk biaya penggantian karyawan, penurunan produktivitas, dan hilangnya pengetahuan dan keterampilan yang berharga. Oleh karena itu, penting untuk memahami faktor-faktor yang mempengaruhi attrition rate agar langkah-langkah yang sesuai dapat diambil untuk menguranginya.

# Cakupan Proyek

## Pekerjaan yang Akan Dilakukan:

- Pengumpulan Data: Mengumpulkan data karyawan yang mencakup informasi seperti usia, pendidikan, gaji, tingkat kepuasan kerja, keterlibatan kerja, jarak tempuh ke kantor, jabatan, lembur, dan status attrition.

- Pemrosesan Data: Membersihkan dan menormalkan data untuk analisis selanjutnya. Ini termasuk penanganan missing values, penghapusan data yang tidak relevan, dan transformasi data jika diperlukan.
- Analisis Exploratori Data (EDA): Melakukan EDA untuk memahami profil karyawan, distribusi variabel, korelasi antara variabel, dan tren terkait tingkat attrition.
Mengidentifikasi faktor-faktor utama yang berkaitan dengan tingkat attrition, seperti kepuasan kerja, keterlibatan kerja, dan jabatan.

- Pemodelan dan Prediksi Attrition: Membangun model prediktif untuk memprediksi kemungkinan attrition karyawan berdasarkan variabel-variabel yang relevan.
Menggunakan teknik machine learning seperti logistic regression, decision trees, atau random forests untuk membangun model prediktif yang akurat.

- Pengembangan Business Dashboard: Merancang dan mengembangkan business dashboard interaktif untuk memantau dan menganalisis tingkat attrition secara real-time.
Menampilkan visualisasi yang jelas dan informatif tentang profil karyawan, distribusi variabel, trend, dan faktor-faktor yang berkontribusi terhadap attrition.

- Implementasi Strategi Retensi: Menggunakan hasil analisis dan prediksi untuk merancang strategi retensi yang efektif, termasuk program pengembangan karir, kebijakan keseimbangan kerja-hidup, dan insentif kompensasi.
Melakukan tindak lanjut secara teratur untuk memantau efektivitas strategi retensi dan membuat penyesuaian jika diperlukan.

- Evaluasi dan Peningkatan Berkelanjutan: Mengevaluasi hasil dari implementasi strategi retensi untuk mengukur penurunan tingkat attrition dan peningkatan retensi karyawan.
Melakukan analisis ulang secara berkala untuk mengidentifikasi perubahan tren dan peluang perbaikan lebih lanjut.

## Batasan Proyek
Proyek ini terbatas pada data yang tersedia dan variabel-variabel yang dimasukkan ke dalam model prediktif.
Analisis dan strategi retensi yang dihasilkan mungkin tidak mampu mengatasi semua faktor yang memengaruhi attrition.
Proyek ini tidak mencakup implementasi strategi retensi di luar ruang lingkup analisis data dan pengembangan model.

## Tujuan Proyek
Tujuan utama proyek ini adalah mengidentifikasi faktor-faktor yang memengaruhi tingkat attrition karyawan, membangun model prediktif untuk memprediksi kemungkinan attrition, dan merancang strategi retensi yang efektif untuk meningkatkan retensi karyawan.

## Output Akhir Proyek
Output akhir proyek ini termasuk model prediktif untuk memprediksi attrition, business dashboard interaktif untuk memantau tingkat attrition secara real-time, serta rekomendasi strategi retensi berdasarkan hasil analisis dan prediksi.

# Persiapan

## Sumber Data
Link data : https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

## Setup Enviroment

- install enviroment
```
python -m venv myenv
```

- aktifkan enviroment (pada windows)
```
myenv\Scripts\activate
```

- install library yang dibutuhkan
```
pip install pandas numpy scikit-learn matplotlib seaborn
```

# Bussiness Dashboard

Business dashboard yang telah dikembangkan memberikan pandangan yang komprehensif tentang faktor-faktor yang memengaruhi tingkat attrition karyawan di perusahaan. Dashboard ini menyajikan visualisasi yang jelas dan informatif tentang profil karyawan, distribusi variabel, tren, dan faktor-faktor yang berkontribusi terhadap attrition. Melalui dashboard ini, manajemen dapat memantau tingkat attrition secara real-time, mengidentifikasi pola dan tren, serta merancang strategi retensi yang tepat untuk meningkatkan retensi karyawan.

Link Dashboard: https://public.tableau.com/views/Dicoding-Kevin1/HRANALYTHICSDASHBOARD?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

# Kesimpulan:

- Tingkat attrition di perusahaan sekitar 17%, dengan mayoritas karyawan memiliki tingkat kepuasan kerja yang rendah.
- Karyawan cenderung memiliki rata-rata usia akhir 20-an hingga pertengahan 30-an dan mayoritas memiliki pendidikan dari masih kuliah hingga gelar Sarjana dan Magister.
- Tidak terlihat perbedaan signifikan dalam kebijakan kenaikan gaji antara pegawai yang mengalami attrition dan yang tidak. Jarak tempuh ke kantor, umur, dan gender tidak terlalu berpengaruh terhadap tingkat attrition.
- Hampir 72% pegawai melakukan lembur.
- Jabatan dengan persentase attrition tertinggi adalah Sales Representative, Sales Executive, Research Scientist, dan Laboratory Technician.

# Rekomendasi Action Items:

- Peningkatan Kepuasan Kerja: Melakukan survei kepuasan kerja secara berkala dan menindaklanjuti temuan dengan tindakan yang diperlukan, seperti perbaikan lingkungan kerja, pengakuan atas prestasi, dan peningkatan komunikasi antara manajemen dan karyawan.
- Pengembangan Karir dan Pelatihan: Menawarkan program pengembangan karir dan pelatihan yang terstruktur untuk memungkinkan karyawan mengembangkan keterampilan mereka dan merasa didukung dalam pertumbuhan karir mereka.
- Evaluasi Kebijakan Kompensasi: Melakukan peninjauan terhadap struktur gaji dan insentif, memastikan bahwa kompensasi bersifat kompetitif dan adil, serta memberikan insentif tambahan untuk karyawan berkinerja tinggi.
- Manajemen Waktu Kerja: Menerapkan kebijakan yang mendukung keseimbangan kerja-hidup, seperti fleksibilitas jam kerja dan kebijakan lembur yang seimbang, untuk mencegah kelelahan dan kelebihan beban kerja.
- Perhatian Khusus pada Jabatan dengan Tingkat Attrition Tinggi: Melakukan analisis lebih lanjut untuk memahami penyebab attrition di jabatan-jabatan dengan tingkat attrition tinggi dan mengambil langkah-langkah khusus untuk meningkatkan kepuasan dan retensi karyawan di level tersebut.
