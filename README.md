# TPOT - <i>Automated Machine Learning Library</i> 

<p align="right">
بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم 
</p>
<p align="center"><img src="https://raw.githubusercontent.com/EpistasisLab/tpot/master/images/tpot-logo.jpg" height="250" width="300"/></p>

TPOT adalah <i>library</i> dalam bahasa pemrograman Python yang dapat digunakan untuk mengoptimalkan/menentukan algoritma pembelajaran mesin secara otomatis dengan menggunakan algoritma genetika. Sebelum membaca lebih lanjut ada baiknya kalian tahu jawaban dari pertanyaan "apa sih algoritma genetika itu?" sama "gimana sih cara kerja algoritma genetika?". Kalo nggak tahu jangan khawatir pilih aja salah satu link di bawah ini untuk mendapatkan jawaban dari kedua pertanyaan tadi :<br>
1. <a href="https://id.wikipedia.org/wiki/Algoritme_genetik">Penjelasan Pertama</a>
2. <a href="https://github.com/Rakhid16/Python-GA-TPOT/blob/master/Algoritma%20Genetika.pdf">Penjelasan Kedua</a>
3. <a href="https://www.youtube.com/watch?v=2mXcs-CNCB8">Penjelasan Ketiga</a>

Sesuai dengan apa yang saya jelaskan di awal, jadi TPOT ini bakal nyari algoritma pembelajaran mesin dengan menjelajahi(coba-coba) ratusan atau bahkan ribuan parameter dengan menggunakan algoritma genetika untuk menemukan algoritma pembelajaran mesin beserta parameternya yang paling optimal. Jadinya ya kalo kita punya <i>dataset</i> kita ndak perlu nyobain SEMUA algoritma dan ndak perlu juga coba-coba nyesuaiin parameternya buat cari tahu mana nih algoritma yang ngepas/cocok sama <i>dataset</i> kita. Mantap jiwa kan? Ehehehe. Algoritma genetika dan pembelajaran mesin itu bagian dari kecerdasan buatan namun algoritma genetika bukanlah bagian dari pembelajaran mesin, si algoritma genetika ini dia itu lebih ke teknik optimasi(<a href="https://en.wikipedia.org/wiki/Metaheuristic">baca lebih lanjut</a>). Ini nih bagian yang diurus sama si TPOT itu.
<p align="center"><img src="https://raw.githubusercontent.com/EpistasisLab/tpot/master/images/tpot-ml-pipeline.png" height="300" width="600"/><br>Gambar 1 - Bagan tahapan dari sebuah alur pembelajaran mesin.</p>

Setelah TPOT selesai mencari algoritma pembelajaran mesin yang paling optimal, TPOT juga bisa mengekspor algoritma (model pembelajaran mesin) tersebut ke dalam baris-baris kode bahasa pemrograman Python. Jadinya ntar tinggal dipake aja. Mantab jiwa(lagi) kan? Ehehehe.
<p align="center"><img src="https://raw.githubusercontent.com/EpistasisLab/tpot/master/images/tpot-pipeline-example.png" height="300" width="600"/><br>Gambar 2 - Contoh dari <a href="https://id.wikipedia.org/wiki/Pipeline"><i>pipeline</i></a> yang dihasilkan oleh TPOT.</p>

O iya TPOT ini dibuat di atas <i>library</i> <a href="https://scikit-learn.org/stable/supervised_learning.html#supervised-learning">scikit-learn</a>(<i>supervised learning</i>), jadi semua algoritma pembelajaran mesin yang dicari sama TPOT waktu kita pake TPOT itu semuanya dari scikit-learn. Begitoe...<br>
Cara pasang TPOT cukup mudah.<br>
Ketikan saja salah satu dari dua perintah di bawah ini di dalam konsol kalain(terminal/cmd) : 

<p align="center">
<b>pip install tpot</b> atau <b>pip3 install tpot</b>
</p>

Jika sudah terpasang pilih aja salah satu dari dua link di bawah ini(<i>atau dua-duanya juga boleh</i>) untuk mengetahui gimana sih caranya nggunain si TPOT ini.

<a href="https://github.com/Rakhid16/Python-TPOT/blob/master/Klasifikasi.ipynb">Klasifikasi</a><br>
<a href="https://github.com/Rakhid16/Python-TPOT/blob/master/Regresi-Prediksi.ipynb">Regresi/Prediksi</a>

<p align="center">Semoga bermanfaat! :)</p>
