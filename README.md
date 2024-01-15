<h3>Aplikasi Diagnosa Kesehatan Mata</h3>

<b>Tugas Pra UAS Kecerdasan Buatan</b>

- Requirements : Python (.py) untuk bahasa pemrograman dan Streamlit untuk deploy aplikasi. Pastikan terdapat requirements.txt yang berisikan module jika ingin di deploy.
- Berikut merupakan cara penggunaan aplikasi sistem pakar diagnosa kesehatan mata dengan menggunakan Streamlit.
- Fitur : Input data. Ketika program dijalankan, pada halaman awal user dapat menginputkan nilai gejala pusing, nilai gejala sakit kepala, nilai gejala demam, nilai gejala lemas, nilai gejala migrain, dan nilai gejala mata beair.
  
<img width="1280" alt="Screen Shot 2024-01-15 at 10 23 33" src="https://github.com/FidelaAzzahra/aplikasi_diagnosa_kesehatan_mata/assets/114632917/978495d7-f05e-480b-b658-def1b003fd8d">

<img width="1280" alt="Screen Shot 2024-01-15 at 10 23 42" src="https://github.com/FidelaAzzahra/aplikasi_diagnosa_kesehatan_mata/assets/114632917/80bfe964-6509-479f-8af7-7882c38a622d">

Apabila nilai gejala sudah terinput, sistem pakar akan mengeluarkan kesimpulan yang berupa nilai presentase berdasarkan nilai gejala yang terinput, dengan keterangan:
  
- A [P01] Gejala pusing dan demam: G01 dan G03 
- B [P02] Gejala sakit kepala, demam, dan mata berair: G02, G03, dan G06
- C [P03] Gejala sakit kepala, lemas, pusing, dan migrain: G02, G04, G01, dan G05
- D [P04] Gejala mata berair dan migrain: G06 dan G05

Berdasarkan hasil diagnosa, gejala yang dialami oleh pasien dapat diperkirakan sebagai berikut:
- Pasien memiliki gejala “P03” dengan tingkat kepercayaan sebesar 72.84%.
- Pasien memiliki gejala “P01” dengan tingkat kepercayaan sebesar 46.00%.
- Pasien memiliki gejala “P04” dengan tingkat kepercayaan sebesar 40.00%.
- Pasien memiliki gejala “P02” dengan tingkat kepercayaan sebesar 26.20%.

Berdasarkan tingkat akurasi tersebut, dapat diketahui bahwa pasien memiliki kemungkinan tertinggi untuk mengalami gejala rabun jauh (miopi) berdasarkan hasil presentase <b> P03 </b> yang mewakili gejala G02, G04, G01, dan G05 sebesar 72.84% dimana apabila kita mengacu pada laman https://hellosehat.com/mata/gangguan-penglihatan/ciri-ciri-mata-minus/ dikatakan bahwa salah satu ciri dari penderita rabun jauh yaitu sering sakit kepala jika fokus membaca atau menonton terlalu lama. Sedangkan untuk sakit kepala sendiri sudah diwakili oleh G02 yang dimana apabila sakit kepala (G02) dan pusing (G01) digabungkan bisa menjadi salah satu gejala awal dari rabun jauh (miopi).  
