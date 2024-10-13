# Komunikasi-Peer-to-Peer-P2P-
Implementasi Analisis Komunikasi Peer-to-Peer dalam Sistem Terdistribusi 
<br>
Azzam Amar Ma'ruf (320220401002) <br> Bainul Dwi Tri Putra (320220401003)
<h2> Deskripsi </h2>
Proyek ini mengimplementasikan sistem komunikasi Peer-to-Peer (P2P) dasar menggunakan metode flooding. Flooding adalah teknik sederhana di mana pesan yang dikirim oleh satu peer diteruskan ke semua peer yang terhubung hingga mencapai semua node dalam jaringan. Simulasi ini berfungsi sebagai alat edukasi untuk memahami cara kerja jaringan P2P dan bagaimana pesan menyebar di jaringan terdesentralisasi.
<h3> Fitur </h3>
<ul>
<li>Penemuan Peer: Setiap peer dalam jaringan dapat menemukan dan terhubung dengan peer lain.</li>
<li>Propagasi Pesan: Pesan yang dikirim dari satu peer akan disebarkan ke semua peer lain menggunakan metode flooding.</li>
<li>Deteksi Duplikasi Pesan: Sistem mencegah peer untuk menyiarkan ulang pesan yang sama.</li>
<li>Skalabilitas Jaringan: Sistem mendukung banyak peer dan dapat menangani penyebaran pesan secara efisien.</li>
</ul>
<h4>log and monitoring</h4>
combined_log.txt: File log ini mencatat event-event berikut:
Koneksi: Waktu saat koneksi dibuat antara node atau client.
Pesan Dikirim: Waktu dan isi pesan yang dikirim.
Pesan Diterima: Waktu dan isi balasan dari server.
Waktu Respon: Waktu yang dibutuhkan untuk memproses permintaan.
Throughput: Kecepatan transfer data yang diukur dalam bytes per detik.
