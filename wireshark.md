Nama  : HANA ZAKIYAH NUR A.
NIM   : 09030282327053

## *Langkah-Langkah*

1) Hubungkan perangkat ke internet/wifi
#### ![Screenshot 2025-02-24 000104](https://github.com/user-attachments/assets/2becf3b9-70ce-4a33-a07d-10d04fdf506a)

3) Buka aplikasi Wireshark, lalu pilih interface jaringan yang secara aktif terhubung ke internet, seperti Wi-Fi atau Ethernet
![Screenshot 2025-02-24 000332](https://github.com/user-attachments/assets/381987c5-d1ee-4216-8bd0-52927f7d23f4)

4) Lalu jalankan Wireshark untuk menjalankan capture packet dan menganalisis lalu lintas jaringan

kemudian lakukan aktivitas seperti bermain game selama 10 menit untuk menganalisis lalu lintas jaringan

Setelah berhasil melakukan packet capture, berikutnya menganalisis data yang terkumpul dengan melihat properties dari packet capture, untuk mengaksesnya melalui menu Statistics > Capture File Properties, atau menggunakan shortcut keyboard Ctrl+Alt+Shift+C

Perhatikan bagian Statistics pada halaman Capture File Properties. Pada halaman ini kita dapat melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter. Selain itu, kita juga dapat melihat distribusi ukuran paket, jenis protokol yang digunakan, serta waktu kedatangan setiap paket

Hitung berapa Throughput, Packet Loss, Delay, dan Jitter yang didapatkan dari Statistics Wireshark yang sudah dijalankan di Laptop, kemudian catat hasilnya di buku catatan dan bandingkan dengan standar kualitas jaringan yang berlaku

Setelah selesai melakukan pengukuran dan memperoleh nilai Throughput, Packet Loss, Delay, dan Jitter, data tersebut kemudian digunakan untuk melengkapi tabel indeks yang menggambarkan kualitas layanan jaringan (QoS).

Analisis :

Percobaan ini dilakukan untuk mengukur parameter Quality of Service (QoS) dengan menggunakan Wireshark saat bermain game selama 10 menit. Parameter yang dianalisis meliputi Throughput, Packet Loss, Delay, dan Jitter. Pengukuran ini dilakukan di laboratorium jaringan dengan menggunakan komputer yang terhubung ke jaringan lokal. Data yang terkumpul kemudian diolah menggunakan metode statistik untuk mendapatkan hasil yang akurat.

Troughput

Throughput yang diperoleh adalah 27, 09792368125701 kbps (27,0 Mbps), yang berada dalam kategori Baik.
Throughput yang tinggi menunjukkan bahwa jaringan lokal yang terkonfigurasi dengan baik memiliki kapasitas yang cukup untuk menangani lalu lintas data selama percobaan.
Packet Lost

Paket yang terukur adalah 99,5% yang masuk dalam kategori buruk
Packet loss yang rendah menunjukkan bahwa hampir semua paket data yang dikirim berhasil diterima dengan baik tanpa banyak kehilangan data, yang mengindikasikan stabilitas jaringan dan minimnya gangguan yang dapat mempengaruhi kualitas bermain.
Delay

Rata-rata delay yang diperoleh adalah 1,37ms, yang berada dalam kategori baik
Waktu penundaan yang terukur sangat kecil, hal ini menunjukan bahwa jaringan memiliki kemampuan untuk segera merespon permintaan, kondisi ini sangat diperlukan untuk kenyamanan dalam bermain game.
Jitter

jitter yang terukur adalah 2,668ms, yang masuk dalam kategori buruk
Nilai jitter yang tinggi menunjukkan adanya variasi besar dalam waktu kedatangan paket, yang dapat menyebabkan gangguan dalam layanan yang memerlukan kestabilan waktu, seperti bermain game atau panggilan suara, di mana pengguna akan mengalami game yang patah-patah atau suara yang terputus-putus.
Kesimpulan :

Berdasarkan percobaan yang dilakukan untuk mengukur parameter Quality of Service (QoS), yang meliputi latensi, jitter, dan packet loss, saat bermain game selama 10 menit, dapat disimpulkan bahwa :

Hasil percobaan menunjukkan bahwa throughput yang tinggi dan tingkat packet loss yang sangat rendah mengindikasikan kapasitas jaringan yang memadai dan minimnya kehilangan data selama sesi bermain game.
Delay yang sangat baik, menunjukkan waktu respons jaringan yang cepat, yang penting untuk pengalaman bermain game yang lancar.
Nilai jitter yang tinggi dapat merusak momen-momen penting dalam bermain game, menyebabkan game patah-pata atau suara menghilang. Namun, untuk mencapai pengalaman yang benar-benar optimal dalam bermain game, masalah jitter, yaitu ketidakkonsistenan dalam latensi, harus diatasi.
