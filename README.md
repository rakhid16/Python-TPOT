# TPOT - _Automated Machine Learning Library_

<p align="right">
بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم
</p>

<p align="center"><img src="https://raw.githubusercontent.com/EpistasisLab/tpot/master/images/tpot-logo.jpg" height="250" width="300"/></p>

TPOT adalah library Python yang digunakan untuk memilih dan mengoptimalkan algoritma pembelajaran mesin secara otomatis dengan menggunakan algoritma genetika. Sebelum melanjutkan, Anda dapat mempelajari dasar algoritma genetika melalui salah satu tautan berikut:

1. <a href="https://id.wikipedia.org/wiki/Algoritme_genetik">Penjelasan Pertama</a>
2. <a href="https://github.com/Rakhid16/Python-GA-TPOT/blob/master/Algoritma%20Genetika.pdf">Penjelasan Kedua</a>
3. <a href="https://www.youtube.com/watch?v=2mXcs-CNCB8">Penjelasan Ketiga</a>

Dengan mencoba ratusan hingga ribuan kombinasi algoritma dan parameter, TPOT berupaya menemukan konfigurasi yang paling optimal untuk _dataset_ Anda. Dengan demikian, Anda tidak perlu menguji semua algoritma dan menyesuaikan setiap parameter secara manual. Algoritma genetika merupakan salah satu teknik optimasi dalam kecerdasan buatan dan <a href="https://en.wikipedia.org/wiki/Metaheuristic">bukan bagian dari pembelajaran mesin itu sendiri</a>.

<p align="center"><img src="https://raw.githubusercontent.com/EpistasisLab/tpot/master/images/tpot-ml-pipeline.png" height="300" width="600"/><br>Gambar 1 - Bagan tahapan dari sebuah alur pembelajaran mesin.</p>

Setelah pencarian selesai, TPOT dapat mengekspor model terbaik beserta konfigurasi pipeline-nya ke kode Python yang siap digunakan.

<p align="center"><img src="https://raw.githubusercontent.com/EpistasisLab/tpot/master/images/tpot-pipeline-example.png" height="300" width="600"/><br>Gambar 2 - Contoh dari <a href="https://id.wikipedia.org/wiki/Pipeline"><i>pipeline</i></a> yang dihasilkan oleh TPOT.</p>

TPOT dibangun di atas <a href="https://scikit-learn.org/stable/supervised_learning.html#supervised-learning">scikit-learn</a>. Oleh karena itu, algoritma pembelajaran mesin yang digunakan berasal dari ekosistem scikit-learn.

## Instalasi

Masukkan salah satu perintah berikut pada terminal atau Command Prompt:

<p align="center">
<b>pip install tpot</b> atau <b>pip3 install tpot</b>
</p>

Setelah terpasang, pilih salah satu contoh berikut untuk mempelajari cara penggunaan TPOT:

<a href="https://github.com/Rakhid16/Python-TPOT/blob/master/Klasifikasi.ipynb">Klasifikasi</a><br>
<a href="https://github.com/Rakhid16/Python-TPOT/blob/master/Regresi-Prediksi.ipynb">Regresi/Prediksi</a>

<p align="center">Semoga bermanfaat! :)</p>
