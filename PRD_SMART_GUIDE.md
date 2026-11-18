# PRODUCT REQUIREMENTS DOCUMENT (PRD)
# SAWARNA SMART GUIDE
## Pengembangan Peta Ilustrasi Kawasan Wisata Interaktif Berbasis Web sebagai Media Panduan Wisata Digital

**Versi Dokumen:** 1.0  
**Status:** Draft Perencanaan Produk  
**Jenis Proyek:** Program Kerja Kuliah Kerja Nyata (KKN)  
**Bidang:** Informatika — Digitalisasi Pariwisata  
**Lokasi Implementasi:** Kawasan wisata pantai di Desa Sawarna, Kecamatan Bayah, Kabupaten Lebak, Provinsi Banten  
**Lokasi Spesifik:** Belum ditentukan, menyesuaikan lokasi penginapan, hasil observasi, dan kesepakatan dengan pengelola wisata  
**Target Platform:** Mobile Web (Responsive Website)  
**Jenis Produk:** Prototype / Minimum Viable Product (MVP)  
**Metode Akses:** Pemindaian QR Code pada pintu masuk utama  
**Sasaran Pengguna:** Wisatawan dan pengunjung kawasan pantai  
**Pengusul:** Kelompok KKN — Divisi Informatika

---

# 1. PENDAHULUAN

## 1.1 Latar Belakang

Digitalisasi sektor pariwisata merupakan salah satu pendekatan yang dapat dilakukan untuk meningkatkan aksesibilitas informasi dan memberikan pengalaman kunjungan yang lebih baik. Pemanfaatan teknologi berbasis web memungkinkan wisatawan memperoleh informasi mengenai fasilitas, objek wisata, serta kondisi umum kawasan melalui perangkat smartphone. Penerapan teknologi tersebut juga dapat mendukung upaya pengenalan potensi wisata lokal dengan menyediakan media informasi yang mudah diakses.

Desa Sawarna di Kabupaten Lebak, Banten, memiliki kawasan wisata pantai yang menjadi salah satu daya tarik bagi pengunjung. Setiap kawasan wisata dapat memiliki berbagai fasilitas pendukung, seperti area parkir, toilet, mushola, warung makan, tempat beristirahat, serta tempat penjualan produk lokal. Ketersediaan informasi mengenai posisi dan jenis fasilitas tersebut penting untuk membantu wisatawan memahami kawasan yang dikunjungi.

Pada tahap perencanaan, belum dapat dipastikan apakah kawasan pantai yang akan menjadi lokasi KKN telah memiliki sistem informasi fasilitas yang memadai atau masih membutuhkan media panduan tambahan. Oleh sebab itu, kelompok KKN mengusulkan pengembangan prototipe peta ilustrasi interaktif berbasis web sebagai bentuk percobaan digitalisasi informasi kawasan wisata. Kebutuhan aktual, cakupan fasilitas, dan kesesuaian produk dengan kondisi setempat akan diverifikasi melalui observasi langsung setelah lokasi implementasi ditetapkan.

Melalui proyek Sawarna Smart Guide, wisatawan diharapkan dapat mengakses peta ilustrasi kawasan dengan memindai QR Code yang ditempatkan pada pintu masuk utama. Peta tersebut menampilkan posisi relatif berbagai fasilitas menggunakan simbol visual yang dapat dipilih untuk membuka informasi tambahan. Sistem dirancang tanpa pelacakan lokasi secara real-time sehingga lebih sederhana, hemat sumber daya, dan sesuai dengan karakteristik proyek percobaan dalam pelaksanaan KKN.

## 1.2 Identifikasi Masalah

Permasalahan yang menjadi dasar perencanaan produk adalah:

1. Informasi mengenai lokasi fasilitas wisata belum tentu tersedia dalam satu media panduan digital yang terintegrasi.
2. Wisatawan baru mungkin memerlukan orientasi mengenai susunan kawasan, lokasi fasilitas, dan akses umum setelah memasuki area wisata.
3. Media informasi konvensional, jika tersedia, memiliki keterbatasan dalam menampilkan keterangan tambahan secara interaktif.
4. Kelompok KKN memerlukan bentuk kontribusi digitalisasi pariwisata yang dapat direalisasikan dalam waktu terbatas dengan biaya operasional rendah.
5. Belum diketahui tingkat kebutuhan dan penerimaan wisatawan terhadap peta ilustrasi digital di kawasan yang akan menjadi lokasi implementasi.

Kelima hal tersebut merupakan dasar kebutuhan yang perlu diuji di lapangan, bukan pernyataan bahwa seluruh masalah telah terbukti terjadi pada setiap objek wisata di Desa Sawarna.

## 1.3 Tujuan Pengembangan Produk

Tujuan utama pengembangan Sawarna Smart Guide adalah menghasilkan prototipe website peta ilustrasi kawasan wisata yang dapat digunakan sebagai media panduan fasilitas bagi pengunjung pantai.

Tujuan khusus proyek meliputi:

1. Merancang ilustrasi kawasan wisata berdasarkan hasil observasi dan pemetaan fasilitas di lokasi.
2. Mengembangkan website responsif yang dapat diakses melalui perangkat smartphone tanpa instalasi aplikasi.
3. Menyediakan penanda statis lokasi pintu masuk utama sebagai titik orientasi awal pengunjung.
4. Menampilkan lokasi fasilitas menggunakan marker dengan ikon berdasarkan kategori.
5. Menyediakan popup yang memuat informasi tambahan ketika pengunjung memilih marker.
6. Mengimplementasikan fungsi zoom dan pan untuk membantu pengguna mengeksplorasi ilustrasi.
7. Mengintegrasikan QR Code sebagai sarana akses langsung menuju website.
8. Menguji fungsionalitas, kemudahan penggunaan, dan performa website melalui pengujian terbatas.
9. Menghasilkan dokumentasi prototipe dan hasil evaluasi sebagai luaran program kerja KKN.

## 1.4 Visi Produk

**Mewujudkan prototipe panduan wisata digital yang sederhana, informatif, menarik secara visual, dan mudah diakses untuk membantu pengunjung mengenali fasilitas kawasan pantai di Desa Sawarna.**

## 1.5 Nilai Produk

Sawarna Smart Guide dikembangkan berdasarkan lima nilai utama:

- **Accessibility:** dapat diakses langsung melalui browser smartphone.
- **Simplicity:** memiliki alur penggunaan sederhana tanpa registrasi.
- **Visual Clarity:** menggunakan ilustrasi dan ikon yang mudah dipahami.
- **Local Relevance:** menampilkan fasilitas berdasarkan kondisi lapangan.
- **Cost Efficiency:** memanfaatkan teknologi web statis untuk meminimalkan biaya pengembangan dan hosting.

---

# 2. DEFINISI DAN RUANG LINGKUP PRODUK

## 2.1 Definisi Produk

Sawarna Smart Guide adalah website panduan wisata berbasis peta ilustrasi interaktif yang menampilkan informasi spasial secara visual mengenai fasilitas pada suatu kawasan pantai.

Produk menggunakan ilustrasi kawasan sebagai media utama, bukan peta geografis dengan layanan navigasi otomatis. Wisatawan dapat memperbesar, memperkecil, dan menggeser peta serta memilih marker fasilitas untuk melihat informasi tambahan melalui popup.

Produk dikategorikan sebagai prototipe digitalisasi pariwisata yang akan dikembangkan dan diuji selama pelaksanaan KKN. Pengembangan tidak mensyaratkan keberlanjutan operasional secara permanen, tetapi dokumentasi serta file sumber akan disiapkan agar prototipe tetap dapat dimanfaatkan atau dikembangkan kembali apabila diperlukan.

## 2.2 Ruang Lingkup Geografis

Lokasi implementasi mencakup satu kawasan pantai wisata di Desa Sawarna.

Penetapan pantai dilakukan setelah mempertimbangkan:

1. Kedekatan dengan lokasi penginapan kelompok KKN.
2. Kemudahan akses untuk observasi lapangan.
3. Ketersediaan dan persebaran fasilitas wisata.
4. Kesediaan pengelola memberikan izin pendataan.
5. Ketersediaan pintu masuk atau titik akses utama yang cocok untuk QR Code.
6. Kesesuaian kompleksitas kawasan dengan durasi KKN.

Pada versi awal, sistem hanya dirancang untuk satu kawasan wisata. Penambahan kawasan lain merupakan opsi pengembangan, bukan bagian wajib MVP.

## 2.3 Ruang Lingkup Fitur MVP

Fitur yang termasuk dalam pengembangan utama adalah:

- Halaman utama berisi peta ilustrasi kawasan.
- Tampilan antarmuka responsif untuk smartphone.
- Penanda statis pintu masuk utama.
- Marker interaktif untuk fasilitas wisata.
- Popup informasi fasilitas.
- Fungsi zoom in dan zoom out.
- Fungsi pan atau geser peta.
- Legenda kategori ikon.
- Tombol pengembalian tampilan ke posisi awal (*reset view*).
- Halaman atau panel informasi singkat penggunaan.
- QR Code menuju alamat website.
- Hosting website statis menggunakan layanan yang menyediakan paket gratis.
- Penanganan dasar ketika gambar atau data gagal dimuat.

## 2.4 Fitur Tambahan Opsional

Fitur berikut dapat dikembangkan apabila waktu dan sumber daya memungkinkan:

- Filter fasilitas berdasarkan kategori.
- Pencarian fasilitas berdasarkan nama.
- Foto fasilitas pada popup.
- Tombol untuk memusatkan peta ke fasilitas tertentu.
- Mode penggunaan offline terbatas.
- Dukungan beberapa titik masuk menggunakan QR Code berbeda.
- Tampilan bilingual Bahasa Indonesia dan Bahasa Inggris.
- Informasi tarif atau aturan kunjungan yang telah diverifikasi.
- Papan peta ilustrasi fisik sebagai media pendamping.

Fitur opsional tidak boleh menghambat penyelesaian seluruh fitur utama.

## 2.5 Fitur di Luar Ruang Lingkup

Fitur berikut secara eksplisit tidak dikembangkan dalam versi MVP:

1. Pelacakan GPS secara real-time.
2. Navigasi turn-by-turn.
3. Perhitungan rute tercepat atau terpendek.
4. Pelacakan riwayat pergerakan pengunjung.
5. Registrasi dan login wisatawan.
6. Sistem pembayaran tiket digital.
7. Pemesanan penginapan atau fasilitas.
8. Sistem ulasan dan rating pengguna.
9. Dashboard analitik pengunjung secara real-time.
10. Backend kompleks dan database relasional.
11. Pengembangan aplikasi Android atau iOS native.
12. Jaminan akses offline penuh untuk perangkat yang belum pernah membuka website.

Pembatasan ini bertujuan menjaga fokus produk sesuai kebutuhan serta kapasitas pelaksanaan KKN.

---

# 3. TARGET PENGGUNA DAN PEMANGKU KEPENTINGAN

## 3.1 Pengguna Utama: Wisatawan

Pengguna utama adalah wisatawan yang sedang mengunjungi kawasan pantai tempat prototipe diimplementasikan.

Karakteristik yang diasumsikan:

- Menggunakan smartphone Android atau iOS.
- Memiliki browser modern.
- Dapat memindai QR Code melalui kamera perangkat.
- Membutuhkan informasi lokasi fasilitas.
- Memiliki tingkat literasi digital yang bervariasi.
- Mungkin menggunakan jaringan seluler dengan kualitas yang tidak stabil.

Website harus dapat digunakan tanpa pengetahuan teknis khusus.

## 3.2 Pengguna Sekunder: Pengelola Kawasan Wisata

Pengelola kawasan menjadi pihak yang dapat memberikan informasi fasilitas, membantu verifikasi peta, dan memberikan masukan terhadap kesesuaian sistem.

Pihak pengelola tidak diwajibkan mengoperasikan dashboard admin karena fitur tersebut tidak termasuk MVP. Apabila terdapat kesepakatan serah terima, pengelola dapat menerima dokumentasi, file sumber, dan akses akun hosting. Tingkat keterlibatan pengelola ditentukan berdasarkan kondisi serta kesediaan mitra di lapangan.

## 3.3 Pemangku Kepentingan

| Pemangku kepentingan | Peran |
|---|---|
| Kelompok KKN Informatika | Analisis kebutuhan, pengembangan website, integrasi dan pengujian |
| Anggota KKN bidang desain/komunikasi | Ilustrasi, visualisasi informasi, penyusunan konten dan QR Code |
| Pengelola kawasan wisata | Validasi fasilitas, izin implementasi dan umpan balik |
| Pelaku UMKM setempat | Sumber informasi usaha dan fasilitas yang relevan |
| Wisatawan | Pengguna dan responden evaluasi |
| Dosen pembimbing lapangan | Pembimbingan dan evaluasi kegiatan KKN |

Nama mitra definitif akan diisi setelah penentuan lokasi dan koordinasi lapangan.

---

# 4. KONSEP PENGALAMAN PENGGUNA

## 4.1 Konsep Utama Interaksi

Sawarna Smart Guide menggunakan paradigma *scan, explore, and discover*.

Pengguna memindai QR Code, melihat ilustrasi kawasan, kemudian memilih fasilitas yang ingin diketahui. Seluruh interaksi dilakukan dalam antarmuka utama tanpa berpindah ke banyak halaman.

Prinsip desain pengalaman pengguna:

1. Peta langsung menjadi fokus utama setelah website terbuka.
2. Pengguna tidak diwajibkan membuat akun.
3. Tidak ada permintaan izin GPS.
4. Ikon fasilitas menggunakan visual yang mudah dikenali.
5. Informasi tambahan ditampilkan dalam popup singkat.
6. Website mengutamakan navigasi sentuh pada smartphone.
7. Jumlah langkah untuk menemukan informasi fasilitas dibuat seminimal mungkin.

## 4.2 User Journey

**Tahap 1 — Kedatangan**

Wisatawan tiba di pintu masuk utama kawasan pantai. Pada area tersebut tersedia papan atau media informasi yang menampilkan QR Code Sawarna Smart Guide.

**Tahap 2 — Pemindaian**

Wisatawan memindai QR Code menggunakan kamera smartphone. Perangkat kemudian membuka alamat website Sawarna Smart Guide melalui browser.

**Tahap 3 — Orientasi Kawasan**

Website menampilkan ilustrasi kawasan pantai. Pada ilustrasi terdapat penanda pintu masuk utama dengan label "Anda Memulai dari Sini", yang merupakan titik orientasi berdasarkan lokasi QR Code.

**Tahap 4 — Eksplorasi**

Wisatawan menggeser atau memperbesar peta untuk melihat fasilitas di area tertentu. Setiap fasilitas memiliki simbol visual yang menunjukkan kategorinya.

**Tahap 5 — Pemilihan Fasilitas**

Wisatawan menekan salah satu marker, misalnya mushola. Website menampilkan popup yang memuat nama fasilitas, deskripsi singkat, serta informasi tambahan apabila tersedia.

**Tahap 6 — Melanjutkan Eksplorasi**

Setelah membaca informasi, pengguna menutup popup dan melanjutkan eksplorasi peta tanpa perlu memuat ulang halaman.

## 4.3 Skenario Penggunaan

### Skenario A: Mencari Mushola

Wisatawan membuka peta melalui QR Code di pintu masuk. Setelah melihat ilustrasi, wisatawan menemukan simbol mushola dan menekannya. Popup menampilkan nama serta keterangan fasilitas sehingga pengunjung dapat mengenali lokasi relatif mushola dalam kawasan.

### Skenario B: Mencari Warung Makan

Wisatawan mengamati ikon warung pada ilustrasi dan memilih salah satu marker. Popup menampilkan nama warung serta informasi singkat yang telah dikumpulkan dalam survei. Wisatawan dapat menutup popup dan memilih warung lain apabila tersedia.

### Skenario C: Memahami Area yang Perlu Diperhatikan

Wisatawan melihat simbol perhatian pada bagian tertentu dari peta. Ketika simbol dipilih, sistem menampilkan pesan terkait kondisi atau aturan kawasan yang telah dikonfirmasi pengelola. Sistem tidak mengklaim menyediakan peringatan keselamatan secara real-time.

---

# 5. SPESIFIKASI DESAIN ANTARMUKA

## 5.1 Pendekatan Desain

Desain menggunakan pendekatan **mobile-first, illustrated wayfinding map, dan minimal user interface**.

Antarmuka tidak dirancang seperti dashboard administrasi atau portal berita wisata. Sebagian besar ruang layar digunakan untuk menampilkan ilustrasi kawasan, sedangkan kontrol interaksi ditempatkan pada area yang mudah dijangkau pengguna smartphone.

## 5.2 Gaya Ilustrasi

**Gaya utama yang direkomendasikan:** ilustrasi 2D tampak atas (*top-down illustrated map*).

Karakteristik ilustrasi:

- Memiliki bentuk kawasan berdasarkan observasi.
- Menggambarkan perbandingan posisi fasilitas secara masuk akal.
- Menampilkan garis pantai, akses masuk, jalur utama, dan objek penting.
- Menggunakan gaya flat illustration dengan detail sederhana.
- Memisahkan ikon interaktif dari ilustrasi latar.
- Menghindari detail visual berlebihan yang mengganggu keterbacaan.
- Mengutamakan kemampuan ditampilkan dengan jelas pada smartphone.

Ilustrasi tidak harus mempertahankan skala geografis presisi. Namun, hubungan posisi fasilitas dan akses utama harus cukup representatif serta diverifikasi melalui survei lapangan.

## 5.3 Palet Warna

Palet warna awal yang direkomendasikan:

| Elemen | Warna | Kode |
|---|---|---|
| Laut | Biru toska | #56B8D0 |
| Pasir pantai | Krem | #F2DEAD |
| Vegetasi | Hijau lembut | #A7C78B |
| Jalan utama | Cokelat muda | #C5A47E |
| Latar panel | Putih | #FFFFFF |
| Teks utama | Biru gelap | #183B50 |
| Ikon informasi | Biru | #2878B8 |
| Ikon perhatian | Oranye | #E8A23A |
| Ikon larangan | Merah | #C94747 |

Palet bersifat awal dan dapat disesuaikan dengan identitas visual kawasan serta kebutuhan keterbacaan.

## 5.4 Struktur Halaman

### A. Header

Header memuat:

- Nama atau logo Sawarna Smart Guide.
- Subjudul "Peta Panduan Kawasan Wisata".
- Tombol informasi atau bantuan penggunaan.

Header harus berukuran ringkas agar tidak mengurangi area peta pada smartphone.

### B. Area Peta

Area ini merupakan komponen utama website.

Isi area peta:

- Ilustrasi kawasan wisata.
- Marker pintu masuk utama.
- Marker fasilitas.
- Zona informasi apabila diperlukan.
- Kontrol zoom.
- Tombol reset view.

### C. Legenda

Legenda menampilkan simbol fasilitas dan penjelasan singkat mengenai arti masing-masing ikon.

Pada perangkat smartphone, legenda dapat dibuat dalam panel yang bisa dibuka atau ditutup agar tidak menutupi area peta.

### D. Popup Informasi

Popup menampilkan informasi ketika marker dipilih.

Pada layar smartphone, popup direkomendasikan berupa panel yang muncul dari bawah (*bottom sheet*). Pada layar yang lebih besar, popup dapat ditampilkan di dekat marker atau sebagai panel samping.

### E. Footer

Footer bersifat minimal, dengan informasi seperti:

- Nama kelompok KKN.
- Tahun pelaksanaan.
- Identitas mitra jika mendapat persetujuan.
- Keterangan bahwa peta merupakan ilustrasi panduan.

## 5.5 Prinsip Responsivitas

Website wajib dapat menyesuaikan ukuran layar smartphone, tablet, dan desktop.

Prioritas pengujian diberikan pada layar smartphone dengan lebar sekitar 320–430 CSS pixel, tanpa membatasi penggunaan di ukuran lain. Semua tombol penting harus mudah disentuh dan teks informasi tidak boleh terpotong pada ukuran layar yang diuji.

---

# 6. FUNCTIONAL REQUIREMENTS

Bagian ini menjelaskan kebutuhan fungsional yang harus dipenuhi sistem.

## FR-01 — Akses Website melalui QR Code

**Prioritas:** Must Have

**Deskripsi:**

Website harus dapat dibuka melalui URL yang direpresentasikan dalam QR Code pada pintu masuk kawasan wisata.

**Kebutuhan:**

1. QR Code mengarah ke URL HTTPS yang valid.
2. QR Code dapat dipindai menggunakan kamera smartphone.
3. Website terbuka tanpa instalasi aplikasi.
4. Pengguna tidak diwajibkan login.
5. QR Code diuji pada perangkat Android dan iOS yang tersedia.
6. URL final ditetapkan sebelum QR Code dicetak.

**Acceptance Criteria:**

- QR Code dapat membuka website pada browser smartphone yang diuji.
- Halaman utama dapat ditampilkan tanpa autentikasi.
- URL tidak mengarah ke halaman error ketika diuji dengan koneksi aktif.

## FR-02 — Menampilkan Peta Ilustrasi

**Prioritas:** Must Have

**Deskripsi:**

Sistem harus menampilkan ilustrasi kawasan wisata sebagai komponen utama halaman.

**Kebutuhan:**

1. Ilustrasi tersedia dalam format yang didukung browser.
2. Gambar mempertahankan rasio aspek aslinya.
3. Ilustrasi dapat menyesuaikan ukuran layar.
4. Peta menampilkan akses masuk dan objek utama.
5. Ilustrasi tidak berubah bentuk saat zoom atau rotasi layar.
6. Tersedia pesan fallback apabila ilustrasi gagal dimuat.

**Acceptance Criteria:**

- Ilustrasi muncul pada halaman utama.
- Ilustrasi tidak terdistorsi.
- Area peta dapat dilihat dengan jelas di perangkat yang diuji.
- Penempatan marker tetap konsisten terhadap ilustrasi saat ukuran tampilan berubah.

## FR-03 — Penanda Pintu Masuk Utama

**Prioritas:** Must Have

**Deskripsi:**

Sistem harus menampilkan penanda statis yang menunjukkan titik awal akses pengunjung berdasarkan lokasi QR Code.

**Kebutuhan:**

1. Marker pintu masuk ditentukan secara manual.
2. Marker tidak berpindah mengikuti gerakan pengguna.
3. Marker memiliki label "Anda Memulai dari Sini" atau "Pintu Masuk Utama".
4. Marker menggunakan warna atau ikon yang membedakannya dari fasilitas lain.
5. Website tidak meminta izin GPS.

**Acceptance Criteria:**

- Marker muncul di posisi yang telah ditentukan pada ilustrasi.
- Marker tidak berubah ketika pengguna berpindah secara fisik.
- Label tidak memberikan kesan pelacakan lokasi real-time.

## FR-04 — Marker Fasilitas Interaktif

**Prioritas:** Must Have

**Deskripsi:**

Sistem harus menampilkan fasilitas wisata menggunakan marker interaktif di atas peta ilustrasi.

**Kebutuhan:**

1. Marker memiliki ID unik.
2. Marker ditempatkan sesuai posisi relatif pada ilustrasi.
3. Marker menggunakan simbol berdasarkan kategori fasilitas.
4. Marker dapat ditekan menggunakan layar sentuh.
5. Marker yang dipilih memunculkan informasi fasilitas terkait.
6. Marker tidak boleh bergeser dari objek yang ditandai ketika peta diperbesar atau digeser.
7. Marker yang tidak memiliki informasi valid tidak boleh ditampilkan sebagai fasilitas terverifikasi.

**Acceptance Criteria:**

- Setiap marker dapat dipilih.
- Setiap marker membuka informasi yang sesuai.
- Posisi marker tetap konsisten saat zoom dan pan.
- Tidak terdapat marker duplikat yang tidak disengaja.

## FR-05 — Popup Informasi Fasilitas

**Prioritas:** Must Have

**Deskripsi:**

Popup digunakan untuk menyampaikan informasi tambahan mengenai fasilitas yang dipilih pengunjung.

**Struktur informasi minimum:**

- Nama fasilitas.
- Kategori fasilitas.
- Deskripsi singkat.

**Informasi opsional:**

- Foto fasilitas.
- Jam operasional yang telah diverifikasi.
- Informasi akses.
- Keterangan tambahan.

**Kebutuhan:**

1. Popup terbuka ketika marker ditekan.
2. Popup menampilkan informasi sesuai ID marker.
3. Popup memiliki tombol tutup.
4. Popup dapat ditutup tanpa memuat ulang halaman.
5. Popup tidak boleh menutupi seluruh peta secara permanen.
6. Jika informasi tidak tersedia, sistem menggunakan teks yang sesuai atau menyembunyikan bagian tersebut.

**Acceptance Criteria:**

- Popup memuat informasi marker yang dipilih.
- Popup dapat dibuka dan ditutup berulang kali.
- Informasi tampil dengan benar pada smartphone.
- Konten popup tidak melampaui batas layar tanpa mekanisme scroll.

## FR-06 — Zoom In dan Zoom Out

**Prioritas:** Must Have

**Deskripsi:**

Pengguna harus dapat memperbesar dan memperkecil peta untuk melihat detail kawasan.

**Kebutuhan:**

1. Zoom mendukung tombol pada antarmuka.
2. Zoom mendukung interaksi sentuh yang kompatibel.
3. Tingkat zoom minimum dan maksimum dibatasi.
4. Ilustrasi tidak boleh menjadi terlalu kecil atau membesar tanpa batas.
5. Posisi marker harus tetap sesuai ilustrasi.

**Acceptance Criteria:**

- Pengguna dapat memperbesar peta.
- Pengguna dapat memperkecil peta.
- Marker tetap berada pada posisi relatif yang benar.
- Interaksi tidak menyebabkan halaman rusak atau keluar dari area peta.

## FR-07 — Pan atau Geser Peta

**Prioritas:** Must Have

**Deskripsi:**

Pengguna dapat menggeser peta untuk mengeksplorasi area yang tidak terlihat pada layar.

**Kebutuhan:**

1. Pan dapat dilakukan menggunakan sentuhan.
2. Pan dapat dilakukan menggunakan mouse pada desktop.
3. Pergerakan dibatasi agar peta tidak hilang sepenuhnya dari area tampilan.
4. Interaksi marker tetap dapat dilakukan setelah peta digeser.

**Acceptance Criteria:**

- Peta dapat digeser ke berbagai arah.
- Tidak terjadi konflik interaksi yang menghalangi pemilihan marker.
- Pengguna dapat kembali ke tampilan awal.

## FR-08 — Reset View

**Prioritas:** Must Have

**Deskripsi:**

Sistem menyediakan tombol untuk mengembalikan tampilan peta ke kondisi awal.

**Kebutuhan:**

1. Tombol reset mudah ditemukan.
2. Ketika ditekan, zoom dikembalikan ke nilai awal.
3. Posisi peta dikembalikan ke tampilan kawasan semula.
4. Penanda pintu masuk tetap terlihat sesuai konfigurasi awal.

**Acceptance Criteria:**

- Satu tindakan dapat mengembalikan peta ke tampilan awal yang telah ditetapkan.

## FR-09 — Legenda Simbol

**Prioritas:** Must Have

**Deskripsi:**

Sistem harus menyediakan penjelasan mengenai simbol yang digunakan pada ilustrasi.

**Kebutuhan:**

1. Legenda memuat kategori simbol yang digunakan.
2. Simbol pada legenda konsisten dengan marker.
3. Legenda dapat dibaca pada layar smartphone.
4. Kategori yang tidak digunakan pada lokasi implementasi tidak perlu ditampilkan.

**Acceptance Criteria:**

- Pengunjung dapat memahami arti simbol utama.
- Tidak terdapat perbedaan simbol antara legenda dan peta.

## FR-10 — Informasi Penggunaan Website

**Prioritas:** Must Have

**Deskripsi:**

Website menyediakan instruksi penggunaan yang sederhana.

**Konten minimum:**

1. Geser peta untuk melihat kawasan.
2. Perbesar peta untuk melihat fasilitas.
3. Tekan ikon untuk menampilkan informasi.
4. Penanda pintu masuk merupakan titik orientasi statis.
5. Peta merupakan ilustrasi, bukan navigasi GPS real-time.

**Acceptance Criteria:**

- Instruksi mudah ditemukan.
- Instruksi dapat dibaca tanpa perlu berpindah ke website lain.

## FR-11 — Filter Kategori Fasilitas

**Prioritas:** Should Have

**Deskripsi:**

Pengunjung dapat memilih kategori fasilitas yang ingin ditampilkan.

**Kebutuhan:**

1. Tersedia pilihan semua kategori.
2. Pengguna dapat menampilkan kategori tertentu.
3. Marker kategori lain disembunyikan sementara.
4. Filter tidak mengubah data asli.

**Acceptance Criteria:**

- Marker yang ditampilkan sesuai kategori pilihan.
- Pilihan "Semua" mengembalikan seluruh marker aktif.

## FR-12 — Pencarian Fasilitas

**Prioritas:** Could Have

**Deskripsi:**

Pengguna dapat mencari fasilitas berdasarkan nama yang tersimpan pada data lokal.

**Kebutuhan:**

1. Pencarian tidak harus menggunakan layanan eksternal.
2. Hasil pencarian hanya mencakup fasilitas yang terdaftar.
3. Pengguna dapat memilih hasil untuk menampilkan informasi fasilitas.

**Acceptance Criteria:**

- Nama fasilitas yang tersedia dapat ditemukan.
- Pemilihan hasil menampilkan fasilitas terkait.

## FR-13 — Mode Offline Terbatas

**Prioritas:** Could Have

**Deskripsi:**

Sistem dapat menyimpan aset utama agar pengguna yang pernah membuka website dapat mengakses sebagian informasi ketika tidak terhubung ke internet.

**Kebutuhan:**

1. Cache hanya diimplementasikan apabila pengujian dasar MVP selesai.
2. Ilustrasi dan data lokal dapat disimpan menggunakan mekanisme cache browser.
3. Sistem tidak menjanjikan akses offline pada kunjungan pertama.
4. Tersedia informasi ketika konten tidak dapat dimuat.

**Acceptance Criteria:**

- Setelah website berhasil dimuat dan aset tersimpan, konten yang ditentukan tetap dapat dibuka pada skenario offline yang diuji.
- Fitur tidak bergantung pada layanan tile peta eksternal.

---

# 7. KATEGORI DAN STRUKTUR INFORMASI FASILITAS

## 7.1 Kategori Awal

Kategori berikut merupakan kandidat dan hanya digunakan apabila fasilitas terkait benar-benar terdapat pada lokasi implementasi.

| Kategori | Contoh objek | Simbol yang disarankan |
|---|---|---|
| Akses | Pintu masuk, pintu keluar | 🚪 |
| Transportasi | Area parkir kendaraan | 🅿️ |
| Ibadah | Mushola | 🕌 |
| Sanitasi | Toilet umum | 🚻 |
| Kuliner | Warung dan restoran | 🍽️ |
| UMKM | Toko souvenir | 🛍️ |
| Istirahat | Gazebo, tempat duduk | 🪑 |
| Kebersihan | Tempat sampah | 🗑️ |
| Informasi | Pos informasi wisata | ℹ️ |
| Keselamatan | Area perhatian atau area terlarang | ⚠️ |
| Objek Wisata | Spot foto atau landmark | 📍 |

Ikon final dapat menggunakan aset SVG yang konsisten agar tampilannya tidak berbeda antarsistem operasi.

## 7.2 Data Minimum Setiap Fasilitas

Setiap fasilitas minimal memiliki:

1. ID fasilitas.
2. Nama fasilitas.
3. Kategori.
4. Posisi horizontal pada ilustrasi.
5. Posisi vertikal pada ilustrasi.
6. Deskripsi singkat.
7. Status validasi data.

Data opsional meliputi foto, jam operasional, keterangan akses, serta catatan pembaruan.

## 7.3 Contoh Struktur Data

```json
{
  "id": "FAC-001",
  "name": "Mushola",
  "category": "worship",
  "position": {
    "x": 62.5,
    "y": 41.0
  },
  "description": "Fasilitas ibadah pengunjung.",
  "image": null,
  "verified": false,
  "status": "draft"
}
```

Nilai koordinat dalam contoh menggunakan persentase relatif terhadap ilustrasi, bukan koordinat geografis. Nilai tersebut hanya digunakan sebagai contoh struktur data sebelum survei lapangan.

## 7.4 Aturan Penempatan Marker

Marker harus diposisikan menggunakan sistem koordinat yang terikat pada ukuran dasar ilustrasi.

Jika menggunakan koordinat persentase, nilai horizontal dan vertikal dihitung relatif terhadap bidang gambar. Jika menggunakan Leaflet dengan sistem koordinat sederhana, posisi perlu dikonversi mengikuti sistem koordinat ilustrasi yang ditentukan.

Seluruh marker harus mengikuti transformasi zoom dan pan yang sama dengan ilustrasi agar tidak bergeser ketika ukuran layar berubah.

## 7.5 Proses Validasi Informasi

Data fasilitas harus melalui tahapan:

1. Observasi lapangan.
2. Pencatatan nama dan fungsi.
3. Dokumentasi lokasi.
4. Penempatan awal pada ilustrasi.
5. Pemeriksaan silang dengan kondisi aktual.
6. Verifikasi akhir bersama pengelola atau pihak lokal yang mengetahui kawasan.
7. Penetapan status layak publikasi.

Informasi yang belum terverifikasi tidak boleh ditampilkan sebagai informasi resmi.

---

# 8. NON-FUNCTIONAL REQUIREMENTS

## NFR-01 — Performance

Website harus dioptimalkan agar dapat digunakan pada smartphone dengan kemampuan menengah dan koneksi seluler yang terbatas.

Target awal pengembangan:

- Ukuran transfer awal diupayakan tidak melebihi 2 MB setelah optimasi, di luar aset opsional yang dimuat kemudian.
- Ilustrasi menggunakan format SVG atau WebP yang sesuai.
- Gambar popup dimuat hanya ketika diperlukan.
- Tidak menggunakan video autoplay.
- Tidak menggunakan animasi berat.
- Pemuatan halaman dievaluasi melalui pengujian jaringan terbatas.

Target ukuran tersebut merupakan sasaran desain internal dan dapat disesuaikan dengan kebutuhan ilustrasi serta hasil pengujian.

## NFR-02 — Compatibility

Website harus mendukung browser modern pada smartphone Android dan iOS.

Pengujian minimum dilakukan pada:

- Google Chrome Android.
- Safari iOS apabila perangkat tersedia.
- Browser desktop untuk pengembangan dan debugging.

## NFR-03 — Usability

Pengguna harus dapat memahami fungsi utama website tanpa pelatihan khusus.

Persyaratan:

- Ikon mudah dikenali.
- Tombol memiliki area sentuh yang memadai.
- Popup mudah dibaca.
- Tersedia legenda.
- Informasi ditulis dengan bahasa sederhana.
- Pengguna dapat kembali ke tampilan peta tanpa kesulitan.

## NFR-04 — Accessibility

Website harus mempertimbangkan pengguna dengan kemampuan visual dan motorik yang berbeda.

Kebutuhan:

- Kontras teks memadai.
- Ikon tidak hanya mengandalkan warna.
- Tombol memiliki label yang bermakna.
- Elemen interaktif dapat digunakan melalui keyboard jika relevan.
- Teks popup tidak tertanam sebagai bagian gambar.
- Gambar dekoratif dan informatif memiliki penanganan alternatif teks yang sesuai.

## NFR-05 — Security and Privacy

Website tidak mengumpulkan identitas pribadi wisatawan sebagai bagian dari MVP.

Persyaratan:

- Tidak meminta izin GPS.
- Tidak menyimpan riwayat pergerakan pengunjung.
- Tidak menggunakan login atau pembuatan akun pengunjung.
- Menggunakan HTTPS.
- Menghindari penyisipan HTML tidak aman dari data fasilitas.
- Menggunakan dependensi dari sumber tepercaya.
- Tidak menyimpan informasi sensitif dalam file publik.

Hosting dapat memiliki log teknis sesuai kebijakan penyedia, tetapi sistem tidak dirancang untuk membangun profil pengunjung.

## NFR-06 — Reliability

Website diharapkan dapat diakses selama masa implementasi dan evaluasi, selama layanan hosting dan koneksi internet tersedia.

Persyaratan:

- Seluruh aset utama disimpan dan dikelola secara terstruktur.
- Tersedia pesan ketika aset gagal dimuat.
- Terdapat backup file sumber.
- Pengujian dilakukan sebelum QR Code dipublikasikan.

Tidak ada jaminan uptime permanen karena website menggunakan layanan hosting pihak ketiga.

## NFR-07 — Maintainability

Kode sumber harus memiliki struktur yang mudah dipahami dan tidak bergantung pada konfigurasi yang hanya diketahui satu orang.

Persyaratan:

- Data fasilitas dipisahkan dari kode tampilan.
- Ilustrasi dipisahkan dari layer marker.
- Struktur folder konsisten.
- Terdapat README instalasi dan deployment.
- Terdapat dokumentasi cara menambah atau mengubah data.
- Terdapat backup versi final proyek.

---

# 9. ARSITEKTUR DAN TEKNOLOGI

## 9.1 Arsitektur Sistem

Arsitektur Sawarna Smart Guide menggunakan pendekatan *static web application*.

Alur sistem:

**QR Code → Browser Smartphone → Static Web Hosting → Ilustrasi Peta + Data Fasilitas → Marker Interaktif → Popup Informasi**

Interaksi utama diproses di sisi browser menggunakan JavaScript.

Tidak diperlukan backend aplikasi untuk operasi dasar, karena data fasilitas dapat dibaca langsung dari berkas JSON lokal.

## 9.2 Teknologi yang Direkomendasikan

| Komponen | Teknologi |
|---|---|
| Struktur halaman | HTML5 |
| Styling | CSS3 |
| Logika aplikasi | JavaScript |
| Library interaksi peta | Leaflet.js |
| Sistem koordinat peta | Leaflet CRS.Simple |
| Ilustrasi peta | SVG atau WebP |
| Data fasilitas | JSON |
| Ikon fasilitas | SVG |
| Hosting | Cloudflare Pages atau layanan hosting statis sejenis |
| Version control | Git |
| Repositori kode | GitHub atau repositori lain |
| Pengembangan | Visual Studio Code |
| Pengujian | Browser DevTools dan pengujian langsung |

Pemilihan teknologi final dapat disesuaikan dengan kompetensi pengembang, selama seluruh kebutuhan MVP terpenuhi.

## 9.3 Penggunaan Leaflet CRS.Simple

Leaflet dengan `CRS.Simple` memungkinkan ilustrasi non-geografis digunakan sebagai bidang peta.

Ilustrasi dapat ditampilkan sebagai image overlay dengan batas yang ditentukan berdasarkan dimensi aslinya. Marker kemudian diletakkan pada koordinat yang sesuai dengan bidang ilustrasi sehingga dapat mengikuti zoom dan pan.

Pendekatan ini tidak membutuhkan tile peta geografis dan tidak melakukan perhitungan navigasi berdasarkan koordinat GPS.

## 9.4 Struktur Direktori

Contoh struktur proyek:

```text
sawarna-smart-guide/
|
|-- index.html
|-- README.md
|
|-- assets/
|   |-- maps/
|   |   |-- beach-map.webp
|   |
|   |-- icons/
|   |   |-- entrance.svg
|   |   |-- parking.svg
|   |   |-- toilet.svg
|   |   |-- mushola.svg
|   |   |-- restaurant.svg
|   |
|   |-- photos/
|
|-- data/
|   |-- facilities.json
|   |-- map-config.json
|
|-- css/
|   |-- style.css
|
|-- js/
|   |-- app.js
|   |-- map.js
|   |-- markers.js
|   |-- popup.js
|
|-- docs/
|   |-- user-guide.md
|   |-- deployment-guide.md
|   |-- data-guide.md
```

Struktur tersebut merupakan rancangan awal dan dapat disederhanakan apabila implementasi tidak memerlukan pemisahan modul sebanyak itu.

## 9.5 Konfigurasi Peta

Konfigurasi peta disimpan terpisah agar lokasi implementasi dapat diganti tanpa mengubah logika inti.

Contoh atribut konfigurasi:

- Nama kawasan.
- Nama file ilustrasi.
- Lebar dan tinggi ilustrasi dasar.
- Zoom awal.
- Zoom minimum.
- Zoom maksimum.
- Posisi pusat awal.
- Posisi marker pintu masuk.
- Keterangan versi peta.

Dengan pendekatan ini, website dapat dikembangkan menggunakan ilustrasi sementara sebelum lokasi pantai definitif dipilih.

---

# 10. KEBUTUHAN DATA DAN SURVEI LAPANGAN

## 10.1 Tujuan Survei

Survei bertujuan memperoleh informasi aktual yang diperlukan untuk membuat ilustrasi serta menempatkan marker secara representatif.

Survei juga digunakan untuk memastikan bahwa kebutuhan terhadap panduan digital sesuai dengan kondisi lokasi implementasi.

## 10.2 Data yang Dikumpulkan

Data survei meliputi:

1. Nama kawasan pantai.
2. Posisi pintu masuk utama.
3. Akses jalan dan jalur pedestrian utama.
4. Lokasi parkir.
5. Lokasi toilet.
6. Lokasi mushola.
7. Warung dan restoran.
8. Tempat penjualan souvenir.
9. Tempat duduk atau gazebo.
10. Tempat sampah.
11. Pos informasi.
12. Objek atau landmark penting.
13. Area yang memerlukan informasi perhatian berdasarkan konfirmasi pengelola.
14. Foto dokumentasi fasilitas.
15. Informasi pendukung yang relevan.

Kategori yang tidak tersedia pada kawasan terpilih dihilangkan dari tampilan.

## 10.3 Metode Pengumpulan Data

Pengumpulan data dilakukan melalui:

- Observasi langsung.
- Dokumentasi foto.
- Pencatatan posisi fasilitas pada sketsa kawasan.
- Pencatatan koordinat GPS smartphone sebagai data bantu survei jika diperlukan, bukan untuk melacak pengunjung.
- Wawancara singkat dengan pengelola atau pelaku usaha.
- Pemeriksaan ulang berdasarkan kondisi lapangan.

## 10.4 Penyusunan Ilustrasi

Ilustrasi dibuat melalui tahapan:

1. Menentukan cakupan batas peta.
2. Membuat sketsa denah kasar.
3. Mengidentifikasi bentuk garis pantai dan jalur utama.
4. Menggambarkan lokasi fasilitas penting.
5. Menyederhanakan bentuk bangunan dan vegetasi.
6. Menentukan posisi marker.
7. Melakukan validasi ilustrasi.
8. Mengekspor gambar ke format web.
9. Mengintegrasikan ilustrasi dengan website.

Ilustrasi harus mengutamakan keterbacaan dibandingkan kemiripan artistik yang berlebihan.

## 10.5 Validasi Peta

Validasi perlu menjawab pertanyaan berikut:

- Apakah pintu masuk berada di posisi ilustrasi yang sesuai?
- Apakah hubungan arah antarfasilitas mudah dipahami?
- Apakah jalur utama digambarkan secara benar?
- Apakah marker menandai objek yang sesuai?
- Apakah ada fasilitas yang salah nama atau salah kategori?
- Apakah informasi keselamatan sudah dikonfirmasi?
- Apakah wisatawan dapat memahami orientasi peta tanpa bantuan?

Hasil koreksi dicatat sebelum website dinyatakan siap digunakan.

---

# 11. IMPLEMENTASI QR CODE

## 11.1 Tujuan

QR Code menjadi media akses utama antara kawasan wisata fisik dan prototipe digital.

## 11.2 Lokasi Pemasangan

Prioritas pemasangan adalah pintu masuk utama kawasan yang telah mendapat persetujuan pengelola.

Titik pemasangan tambahan dapat dipertimbangkan apabila lokasi memiliki beberapa akses penting dan terdapat izin.

## 11.3 Isi Media QR Code

Media QR Code setidaknya memuat:

**SAWARNA SMART GUIDE**

*Peta Panduan Wisata Interaktif*

**Scan QR Code untuk Melihat Peta dan Fasilitas Kawasan**

Konten pendukung:

- QR Code.
- Instruksi singkat.
- Identitas mitra jika disetujui.
- Identitas kegiatan KKN.

## 11.4 Persyaratan Implementasi

1. QR Code menggunakan alamat website final.
2. QR Code diuji pada beberapa smartphone.
3. Ukuran cetak harus memadai untuk jarak pemindaian yang direncanakan.
4. Media ditempatkan pada lokasi yang mudah terlihat.
5. Material dan pemasangan menyesuaikan kondisi lingkungan pesisir.
6. QR Code tidak boleh menghalangi papan resmi atau jalur pengunjung.
7. Pemasangan dilakukan setelah memperoleh izin pengelola.

## 11.5 Catatan

QR Code tidak mendeteksi lokasi smartphone.

Penanda pintu masuk pada website berasal dari konfigurasi sistem. Jika pada masa depan terdapat beberapa QR Code pintu masuk, URL dapat diberi parameter untuk membedakan titik orientasi, tanpa membutuhkan izin GPS.

---

# 12. RENCANA PENGUJIAN

## 12.1 Tujuan Pengujian

Pengujian bertujuan memastikan bahwa website dapat menjalankan fitur yang direncanakan dan dapat dipahami oleh pengguna.

Pengujian dilakukan melalui kombinasi pengujian teknis dan evaluasi terbatas kepada pengguna.

## 12.2 Functional Testing

| ID | Skenario | Hasil yang diharapkan |
|---|---|---|
| TC-01 | Scan QR Code | Website terbuka |
| TC-02 | Membuka halaman utama | Peta muncul |
| TC-03 | Melihat titik masuk | Marker statis terlihat |
| TC-04 | Klik marker fasilitas | Popup terbuka |
| TC-05 | Tutup popup | Popup tertutup |
| TC-06 | Zoom in | Peta membesar |
| TC-07 | Zoom out | Peta mengecil |
| TC-08 | Geser peta | Tampilan bergerak |
| TC-09 | Reset view | Peta kembali ke tampilan awal |
| TC-10 | Mengubah ukuran layar | Marker dan ilustrasi tetap selaras |
| TC-11 | Membuka legenda | Keterangan simbol muncul |
| TC-12 | Data fasilitas tidak tersedia | Pesan fallback ditampilkan |
| TC-13 | Memilih fasilitas berulang | Informasi selalu sesuai |
| TC-14 | Menguji koneksi lambat | Website tetap memberikan respons atau pesan yang sesuai |

Pengujian tambahan mengikuti fitur opsional yang benar-benar diimplementasikan.

## 12.3 Responsive Testing

Pengujian dilakukan pada beberapa ukuran layar untuk memastikan:

- Peta tidak terdistorsi.
- Marker tetap mudah diklik.
- Popup tidak terpotong.
- Tombol dapat diakses.
- Tidak muncul horizontal scrolling yang tidak diperlukan.
- Tampilan tetap nyaman dalam orientasi portrait maupun landscape yang didukung.

## 12.4 Performance Testing

Pengujian mencakup:

1. Ukuran total data yang dimuat.
2. Waktu awal pemuatan website.
3. Respons interaksi marker.
4. Kelancaran zoom dan pan.
5. Performa pada kondisi koneksi seluler yang terbatas.

Pengukuran dapat menggunakan Chrome DevTools, Lighthouse, serta pengujian langsung di kawasan wisata.

Tidak ditetapkan klaim performa aktual sebelum hasil pengujian diperoleh.

## 12.5 Usability Testing

Pengujian terbatas dapat dilakukan dengan melibatkan wisatawan atau calon pengguna yang bersedia.

Contoh tugas pengujian:

1. Temukan lokasi pintu masuk pada peta.
2. Temukan simbol mushola.
3. Buka informasi salah satu warung.
4. Perbesar peta untuk melihat area tertentu.
5. Kembalikan peta ke tampilan awal.

Data yang dapat dicatat:

- Keberhasilan menyelesaikan tugas.
- Waktu penyelesaian tugas.
- Kesalahan penggunaan.
- Kesulitan memahami simbol.
- Pendapat pengguna mengenai kejelasan ilustrasi.
- Saran perbaikan.

Apabila memungkinkan, pengujian melibatkan sedikitnya 10 responden sebagai target awal evaluasi formatif. Jumlah akhir disesuaikan dengan kondisi lapangan dan tidak dianggap otomatis mewakili seluruh populasi wisatawan Sawarna.

## 12.6 Evaluasi Kualitatif

Selain pengujian fungsi, kelompok KKN dapat melakukan wawancara singkat dengan pengguna serta pengelola untuk mengetahui:

- Apakah informasi yang disajikan membantu?
- Apakah ikon mudah dipahami?
- Apakah peta terlalu rumit?
- Apakah fasilitas yang dianggap penting telah ditampilkan?
- Apakah pengelola melihat potensi manfaat dari prototipe?

Hasil evaluasi digunakan untuk menyusun kesimpulan berdasarkan bukti pengujian, bukan berdasarkan asumsi manfaat.

---

# 13. SUCCESS METRICS

Keberhasilan MVP dinilai menggunakan indikator yang terukur.

| Indikator | Target Awal |
|---|---|
| Website dapat dibuka melalui QR Code | Berhasil pada seluruh skenario uji utama |
| Fitur wajib | 100% memenuhi acceptance criteria sebelum serah terima |
| Marker fasilitas | Seluruh marker yang dipublikasikan tervalidasi |
| Konsistensi penempatan marker | Tidak bergeser dari ilustrasi saat zoom/pan |
| Keberhasilan tugas pengguna | Target ≥80% pada pengujian terbatas |
| Kemudahan pemahaman simbol | Dievaluasi melalui umpan balik pengguna |
| Performa website | Memenuhi target internal yang ditetapkan setelah uji perangkat dan jaringan |
| Dokumentasi proyek | Berkas sumber, data, dan panduan tersedia |
| Pelaksanaan demonstrasi | Prototipe dapat diperagakan kepada pengelola |

Target tersebut merupakan kriteria perencanaan, bukan hasil yang telah dicapai.

Keberhasilan utama KKN adalah terealisasinya prototipe, tersedianya data fasilitas hasil survei, dan adanya evaluasi penggunaan. Produk tidak harus mencapai jumlah pengunjung tertentu atau beroperasi secara permanen untuk dinyatakan telah memenuhi tujuan percobaan yang ditetapkan.

---

# 14. RENCANA PENGEMBANGAN DAN TIMELINE

## 14.1 Tahap Pra-KKN

Kegiatan yang dapat diselesaikan sebelum keberangkatan:

1. Finalisasi kebutuhan produk.
2. Pembuatan wireframe antarmuka.
3. Pemilihan teknologi.
4. Pembuatan kerangka website.
5. Implementasi Leaflet CRS.Simple.
6. Pembuatan ilustrasi dummy.
7. Implementasi data marker dummy.
8. Implementasi popup.
9. Pengujian zoom dan pan.
10. Persiapan format survei lapangan.

**Output:** prototipe fungsional menggunakan data sementara.

## 14.2 Minggu Pertama KKN — Observasi dan Pemetaan

Kegiatan:

- Menentukan kawasan wisata implementasi.
- Berkoordinasi dengan pengelola.
- Memastikan izin pendataan dan pemasangan QR.
- Melakukan inventarisasi fasilitas.
- Mendokumentasikan kawasan.
- Menyusun sketsa dasar peta.
- Memvalidasi informasi awal.

**Output:** dataset fasilitas dan sketsa kawasan.

## 14.3 Minggu Kedua — Pengembangan Ilustrasi

Kegiatan:

- Membuat ilustrasi peta berdasarkan hasil survei.
- Menyusun ikon kategori.
- Melakukan optimasi aset gambar.
- Memasukkan data fasilitas.
- Menempatkan marker.
- Mengintegrasikan popup.

**Output:** prototipe sesuai kawasan aktual.

## 14.4 Minggu Ketiga — Pengujian dan Penyempurnaan

Kegiatan:

- Menguji fungsionalitas.
- Menguji responsivitas.
- Memeriksa kesesuaian informasi.
- Melakukan pengujian pengguna terbatas.
- Memperbaiki kesalahan teknis.
- Menyempurnakan tampilan.

**Output:** versi kandidat rilis.

## 14.5 Minggu Keempat — Implementasi dan Evaluasi

Kegiatan:

- Mempublikasikan website pada alamat final.
- Menguji URL produksi.
- Mencetak QR Code.
- Memasang media akses dengan izin pengelola.
- Melakukan demonstrasi penggunaan.
- Mengumpulkan evaluasi akhir.
- Menyusun dokumentasi hasil program.
- Melakukan serah terima apabila disepakati.

**Output:** prototipe website yang dapat diakses, dokumentasi, dan laporan evaluasi.

Jadwal empat minggu adalah asumsi perencanaan dan harus disesuaikan dengan durasi KKN yang sebenarnya.

---

# 15. PEMBAGIAN TUGAS KELOMPOK

Pembagian tugas dapat disesuaikan dengan jumlah anggota dan keahlian yang tersedia.

| Peran | Tanggung jawab |
|---|---|
| Product Coordinator | Menentukan prioritas dan koordinasi kegiatan |
| Frontend Developer | Implementasi antarmuka dan interaksi |
| Map Illustrator / UI Designer | Ilustrasi kawasan dan ikon |
| Data Surveyor | Pendataan dan dokumentasi fasilitas |
| QA / Documentation | Pengujian dan dokumentasi |
| Mitra Lapangan | Verifikasi informasi dan persetujuan |

Satu anggota diperbolehkan menjalankan lebih dari satu peran.

Untuk kolaborasi lintas disiplin, anggota Ilmu Komunikasi dapat berkontribusi pada desain visual, bahasa informasi, media QR Code, dan evaluasi keterbacaan. Anggota Informatika menangani integrasi teknis, pengelolaan data, responsivitas, deployment, dan pengujian sistem.

---

# 16. KEBUTUHAN SUMBER DAYA DAN ANGGARAN

## 16.1 Perangkat Pengembangan

Kebutuhan utama meliputi:

- Laptop pengembangan.
- Smartphone pengujian.
- Koneksi internet.
- Perangkat lunak pengembangan.
- Perangkat lunak ilustrasi.
- Akses layanan hosting statis.
- Perlengkapan dokumentasi.

## 16.2 Komponen Anggaran

| Komponen | Kebutuhan | Keterangan |
|---|---|---|
| Hosting statis | Website online | Dapat menggunakan paket gratis |
| Subdomain | Alamat website | Dapat menggunakan domain bawaan penyedia |
| Pembuatan ilustrasi | Aset peta utama | Dikerjakan tim jika kompetensi tersedia |
| Pengembangan website | Pemrograman | Dikerjakan anggota kelompok |
| Survei | Pendataan lapangan | Menyesuaikan kondisi lokasi |
| QR Code | Akses website | Pembuatan digital dapat gratis |
| Cetak media QR | Media fisik | Membutuhkan anggaran sesuai bahan dan ukuran |
| Papan peta fisik | Luaran tambahan | Opsional |
| Dokumentasi | Laporan dan publikasi | Menyesuaikan kebutuhan KKN |

Nominal biaya final belum ditetapkan karena kebutuhan cetak, material, izin, lokasi, dan harga penyedia setempat belum diketahui.

## 16.3 Strategi Efisiensi

Untuk menekan biaya:

1. Menggunakan hosting statis dengan paket gratis.
2. Menggunakan subdomain bawaan penyedia.
3. Menghindari backend berbayar.
4. Menghindari layanan API yang tidak diperlukan.
5. Menggunakan pustaka open-source dengan memperhatikan lisensi.
6. Mengembangkan ilustrasi dan website secara internal.
7. Membatasi cakupan pada satu kawasan wisata.
8. Menggunakan data lokal JSON.

---

# 17. RISIKO DAN MITIGASI

| Risiko | Dampak | Mitigasi |
|---|---|---|
| Lokasi pantai belum ditentukan | Desain spesifik belum bisa diselesaikan | Kembangkan kerangka website dengan data dummy |
| Fasilitas tersebar dan sulit didata | Survei membutuhkan waktu lebih lama | Batasi area pilot |
| Ilustrasi tidak representatif | Pengunjung salah memahami kawasan | Validasi melalui survei dan pengelola |
| Marker tidak sesuai posisi | Informasi sulit digunakan | Pisahkan data marker dan lakukan verifikasi |
| Pengguna sulit memahami ikon | Pengalaman pengguna menurun | Gunakan legenda dan uji keterbacaan |
| Koneksi seluler lemah | Website lambat atau gagal dimuat | Kompres aset dan siapkan fallback |
| Hosting gratis berubah kebijakan | Website berpotensi tidak dapat diakses | Simpan backup dan dokumentasi deployment |
| QR Code rusak | Akses pengguna terganggu | Gunakan material yang sesuai dan uji kondisi pemasangan |
| URL website berubah | QR Code tidak lagi sesuai | Finalisasi URL sebelum pencetakan |
| Tidak ada pengelola pasca-KKN | Data tidak diperbarui | Dokumentasikan kondisi terakhir dan status prototipe |
| Waktu KKN terbatas | Fitur tidak selesai | Prioritaskan fitur Must Have |
| Izin pemasangan tidak diberikan | QR Code tidak dapat dipasang | Gunakan media demonstrasi alternatif setelah koordinasi |
| Informasi keselamatan tidak valid | Risiko kesalahan pemahaman | Publikasikan hanya informasi yang telah diverifikasi |

---

# 18. KEBERLANJUTAN DAN BATASAN OPERASIONAL

## 18.1 Status sebagai Prototipe KKN

Sawarna Smart Guide dirancang sebagai proyek percobaan digitalisasi pariwisata dalam program KKN.

Proyek tidak mewajibkan mitra melakukan pemeliharaan rutin secara mandiri setelah masa KKN berakhir. Fokus utama adalah penerapan teknologi, demonstrasi manfaat, pengujian terbatas, dan penyusunan dokumentasi hasil.

## 18.2 Hosting dan Masa Akses

Website dapat menggunakan layanan hosting statis gratis untuk menghindari kebutuhan biaya server selama berada dalam batas paket layanan.

Namun, paket gratis tidak memberikan jaminan bahwa website akan selalu tersedia tanpa batas waktu. Ketersediaan layanan dipengaruhi oleh kebijakan penyedia, status akun, dan kondisi teknis lainnya.

## 18.3 Dokumentasi dan Backup

Walaupun proyek bersifat percobaan, kelompok KKN tetap menyiapkan:

1. Kode sumber website.
2. File ilustrasi final.
3. File data fasilitas.
4. Dokumentasi instalasi.
5. Panduan deployment.
6. Informasi akun dan kepemilikan yang diserahkan melalui prosedur aman apabila disepakati.
7. Dokumentasi pengujian.
8. Laporan hasil implementasi.

Kata sandi dan informasi akses rahasia tidak boleh dimasukkan ke dokumen publik.

## 18.4 Mekanisme Penutupan Proyek

Jika website tidak dapat dipertahankan setelah masa KKN, kelompok tetap memiliki dokumentasi prototipe dan hasil evaluasi yang dapat dijadikan dasar pengembangan berikutnya.

Apabila terdapat papan atau media QR fisik yang telah dipasang, perlu ada kesepakatan dengan pengelola mengenai pemantauan tautan atau pencabutan media tersebut jika website dinonaktifkan. Langkah ini diperlukan agar pengunjung tidak terus diarahkan ke tautan yang sudah tidak berfungsi.

Dengan demikian, keberhasilan program tetap dinilai berdasarkan tujuan proyek percobaan yang telah dirumuskan, bukan asumsi bahwa sistem harus beroperasi permanen.

---

# 19. DELIVERABLES

Luaran akhir proyek dibagi menjadi luaran wajib dan luaran tambahan.

## 19.1 Luaran Wajib

1. Website Sawarna Smart Guide yang telah dipublikasikan.
2. Ilustrasi digital kawasan wisata hasil survei.
3. Marker fasilitas interaktif.
4. Popup informasi fasilitas.
5. Penanda statis pintu masuk utama.
6. Fitur zoom, pan, dan reset view.
7. Legenda simbol fasilitas.
8. QR Code dengan URL yang telah diuji.
9. Dataset fasilitas yang telah diverifikasi.
10. Dokumen pengujian fungsional.
11. Dokumentasi foto kegiatan.
12. Kode sumber dan dokumentasi teknis.
13. Laporan hasil implementasi KKN.

## 19.2 Luaran Tambahan

1. Peta fisik kawasan wisata.
2. Filter kategori.
3. Pencarian fasilitas.
4. Foto fasilitas dalam popup.
5. Mode offline terbatas.
6. Artikel publikasi kegiatan pengabdian.
7. Video dokumentasi penggunaan.
8. Panduan singkat untuk pengelola wisata.

Luaran tambahan dikerjakan setelah seluruh kebutuhan wajib terpenuhi.

---

# 20. DEFINITION OF DONE

Proyek dinyatakan selesai secara teknis apabila seluruh kondisi berikut terpenuhi:

- [ ] Lokasi kawasan implementasi telah ditetapkan.
- [ ] Pendataan fasilitas telah dilakukan.
- [ ] Ilustrasi final telah dibuat dan diverifikasi.
- [ ] Website dapat dibuka melalui browser smartphone.
- [ ] QR Code mengarah ke website yang benar.
- [ ] Penanda pintu masuk ditampilkan secara statis.
- [ ] Marker fasilitas ditampilkan sesuai data.
- [ ] Popup membuka informasi yang benar.
- [ ] Zoom in dan zoom out berfungsi.
- [ ] Pan peta berfungsi.
- [ ] Tombol reset view berfungsi.
- [ ] Legenda simbol tersedia.
- [ ] Tampilan responsif pada perangkat pengujian.
- [ ] Tidak ditemukan kesalahan kritis pada fitur utama.
- [ ] Pengujian pengguna terbatas telah dilakukan.
- [ ] Hasil evaluasi terdokumentasi.
- [ ] File sumber dan data telah dicadangkan.
- [ ] Status prototipe telah dikomunikasikan kepada mitra.

Jika izin pemasangan QR fisik belum diperoleh, implementasi lapangan dicatat sebagai belum terlaksana, meskipun pengujian akses QR secara teknis telah berhasil.

---

# 21. PENGEMBANGAN PRODUK DI MASA DEPAN

Walaupun pengembangan lanjutan bukan kewajiban KKN, arsitektur website sebaiknya tidak menghalangi penambahan fitur sederhana pada masa depan.

Peluang pengembangan meliputi:

1. Mendukung lebih dari satu kawasan wisata.
2. Mendukung beberapa pintu masuk.
3. Menambahkan kategori fasilitas baru.
4. Menghubungkan direktori UMKM.
5. Menambahkan informasi tarif dan aturan kawasan.
6. Mendukung beberapa bahasa.
7. Mengembangkan mode offline.
8. Menambahkan panel pengelolaan data.
9. Mengembangkan peta geografis pendamping.
10. Melakukan evaluasi penggunaan dalam skala lebih besar.

Pengembangan tersebut membutuhkan analisis kebutuhan baru dan tidak termasuk komitmen MVP.

---

# 22. KEPUTUSAN PRODUK DAN HAL YANG BELUM DITETAPKAN

## 22.1 Keputusan yang Telah Ditetapkan

| Aspek | Keputusan |
|---|---|
| Nama produk | Sawarna Smart Guide |
| Bentuk produk | Website interaktif |
| Pendekatan peta | Peta ilustrasi kawasan |
| Gaya desain rekomendasi | 2D tampak atas |
| Pengguna utama | Wisatawan |
| Metode akses | QR Code |
| Posisi awal pengguna | Penanda statis pintu masuk |
| GPS real-time | Tidak digunakan |
| Navigasi otomatis | Tidak dikembangkan |
| Interaksi utama | Klik marker dan popup |
| Interaksi pendukung | Zoom, pan, reset view |
| Penyimpanan data | JSON lokal |
| Hosting | Layanan hosting statis gratis |
| Platform utama | Smartphone |
| Status produk | Prototipe KKN |
| Kewajiban pemeliharaan permanen | Tidak diwajibkan |

## 22.2 Hal yang Belum Ditetapkan

| Aspek | Metode penentuan |
|---|---|
| Pantai implementasi | Setelah lokasi penginapan dan survei diketahui |
| Mitra resmi | Koordinasi dengan pengelola setempat |
| Luas kawasan | Observasi lapangan |
| Jumlah marker | Hasil inventarisasi fasilitas |
| Daftar kategori final | Hasil survei |
| Ilustrasi final | Hasil pemetaan kawasan |
| Alamat URL final | Setelah deployment |
| Jumlah QR Code | Menyesuaikan izin dan kebutuhan lokasi |
| Nominal anggaran cetak | Berdasarkan kebutuhan dan harga lokal |
| Jumlah responden akhir | Sesuai kondisi pengujian lapangan |
| Penanggung jawab hosting pasca-KKN | Kesepakatan kelompok dan mitra |
| Durasi implementasi aktual | Menyesuaikan jadwal KKN |

---

# 23. PENUTUP

Sawarna Smart Guide merupakan rancangan prototipe peta ilustrasi interaktif berbasis web yang dikembangkan untuk mendukung percobaan digitalisasi informasi wisata di salah satu kawasan pantai Desa Sawarna. Produk difokuskan pada penyajian ilustrasi kawasan, penanda fasilitas, dan informasi tambahan melalui interaksi sederhana yang dapat diakses menggunakan QR Code. Pengembangan tidak mencakup pelacakan GPS real-time maupun navigasi otomatis sehingga kompleksitas sistem tetap sesuai dengan kebutuhan dan keterbatasan kegiatan KKN.

Pendekatan website statis dipilih karena memungkinkan pengembangan tanpa kebutuhan backend atau database yang kompleks. Penggunaan ilustrasi peta lokal, data fasilitas berformat JSON, dan hosting statis dengan paket gratis diharapkan dapat menekan kebutuhan sumber daya operasional. Meskipun tidak ditargetkan untuk dikelola secara permanen, dokumentasi serta file sumber akan disiapkan sebagai hasil kegiatan dan dasar pengembangan selanjutnya.

Keberhasilan proyek akan dievaluasi melalui ketercapaian fitur utama, kesesuaian informasi fasilitas dengan kondisi lapangan, pengujian kemudahan penggunaan, serta hasil demonstrasi kepada pihak terkait. Dengan ruang lingkup yang terukur, Sawarna Smart Guide diharapkan menjadi contoh penerapan kemampuan Informatika dalam mendukung aktivitas pariwisata lokal. Pengembangan dan evaluasinya sekaligus menjadi sarana pembelajaran lapangan bagi kelompok KKN dalam menerapkan proses analisis kebutuhan, perancangan produk, implementasi teknologi, serta pengujian sistem berbasis kebutuhan pengguna.

---

**Akhir Dokumen — PRD Sawarna Smart Guide v1.0**
