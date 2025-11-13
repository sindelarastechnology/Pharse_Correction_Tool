<h1>📝 Phrase Correction Tool</h1>

<img width="1918" height="1078" alt="Screenshot 2025-08-13 162618" src="https://github.com/user-attachments/assets/f98bc020-c9a3-4c04-8a3b-fee8886724ad" />

<p><strong>Phrase Correction Tool</strong> adalah aplikasi berbasis Python & Tkinter yang digunakan untuk <strong>menganalisis, mengoreksi, dan mengurutkan frasa</strong> berdasarkan label yang telah ditentukan.<br>
Aplikasi ini dirancang untuk mempermudah proses pelabelan kata/frasa baru menggunakan model Machine Learning yang dilatih dari dataset yang ada.</p>

<hr>

<h2>✨ Fitur Utama</h2>
<ul>
<li><strong>Analisis Frasa</strong> – Memecah frasa menjadi kata-kata, memeriksa labelnya, dan mengurutkan sesuai urutan kategori yang sudah ditentukan.</li>
<li><strong>Deteksi Kata Baru</strong> – Menampilkan popup konfirmasi jika ditemukan kata yang belum ada di dataset.</li>
<li><strong>Pelabelan Kata</strong> – Prediksi otomatis label kata baru menggunakan kombinasi model ML (SVM, Naive Bayes, KNN, Random Forest, dan VSM).</li>
<li><strong>Pengelolaan Dataset</strong> – Menyimpan kata baru beserta labelnya ke file <code>new_words.txt</code> atau dataset utama (<code>dataset.csv</code>).</li>
<li><strong>Tampilan Interaktif</strong> – Menggunakan GUI Tkinter dengan popup, combobox label, dan scrollbar untuk mempermudah navigasi.</li>
</ul>

<hr>

<h2>🧠 Algoritma yang Digunakan</h2>
<ul>
<li><strong>TF-IDF Vectorization</strong> (char &amp; word n-grams) – Mengubah teks menjadi representasi numerik berdasarkan frekuensi kemunculan kata.</li>
<li><strong>VSM (Vector Space Model)</strong> – Mengukur <em>cosine similarity</em> antara kata/frasa baru dengan dataset yang sudah ada.</li>
<li><strong>SVM (Support Vector Machine)</strong> – Klasifikasi berbasis margin maksimal.</li>
<li><strong>Multinomial Naive Bayes</strong> – Klasifikasi probabilistik berbasis distribusi kata.</li>
<li><strong>K-Nearest Neighbors (KNN)</strong> – Berdasarkan kedekatan jarak.</li>
<li><strong>Random Forest</strong> – Ensemble berbasis pohon keputusan.</li>
<li><strong>Ensemble Scoring</strong> – Menggabungkan prediksi dari beberapa model dengan bobot tertentu.</li>
</ul>

<hr>

<h2>📂 Cara Menjalankan Aplikasi</h2>
<ol>
<li>Download <a href="https://drive.google.com/drive/folders/1BchigjzxR1_N9UZsZ6l4sNEw7MEOUS_U?usp=sharing" target="_blank">Phrase Correction Tool di Google Drive</a></li>
<li>Lalu klik kanan pada file rar, pilih ekstrak to <code>Phrase Correction Tool</code></li>
<li>Buka folder <code>main</code> lalu klik 2 kali pada aplilasi <code>Phrase Correction Tool.exe</code></li>
<li>Jalankan aplikasi</li>
</ol>
