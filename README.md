<h3>Aplikasi Diagnosa Kesehatan Mata</h3>

<b>Tugas Pra UAS Kecerdasan Buatan</b>

- Requirements : Python (.py) untuk bahasa pemrograman dan Streamlit untuk deploy aplikasi. Pastikan terdapat requirements.txt yang berisikan module jika ingin di deploy.
- Berikut merupakan cara penggunaan aplikasi sistem pakar diagnosa kesehatan mata dengan menggunakan Streamlit.
- Fitur : Input data. Ketika program dijalankan, pada halaman awal user dapat menginputkan nilai gejala pusing, nilai gejala sakit kepala, nilai gejala demam, nilai gejala lemas, nilai gejala migrain, dan nilai gejala mata beair.
  
<img width="1280" alt="Screen Shot 2024-01-15 at 10 23 33" src="https://github.com/FidelaAzzahra/aplikasi_diagnosa_kesehatan_mata/assets/114632917/978495d7-f05e-480b-b658-def1b003fd8d">

<img width="1280" alt="Screen Shot 2024-01-15 at 10 23 42" src="https://github.com/FidelaAzzahra/aplikasi_diagnosa_kesehatan_mata/assets/114632917/80bfe964-6509-479f-8af7-7882c38a622d">

Apabila nilai gejala sudah terinput, sistem pakar akan mengeluarkan kesimpulan yang berupa nilai presentase berdasarkan nilai gejala yang terinput, dengan keterangan:
  
- A. Gejala pusing dan demam: G01 dan G03 
- B. Gejala sakit kepala, demam, dan mata berair: G02, G03, dan G06
- C. Gejala sakit kepala, lemas, pusing, dan migrain: G02, G04, G01, dan G05
- D. Gejala mata berair dan migrain: G06 dan G05
  
Dimana presentase huruf yang paling besar merupakan gejala dari user tersebut.

