# Aplikasi Cek Cuaca Sederhana

**Aplikasi Cek Cuaca Sederhana** adalah aplikasi Java yang memungkinkan pengguna untuk memeriksa cuaca terkini di berbagai kota menggunakan data dari API OpenWeatherMap. Pengguna dapat memasukkan nama kota, melihat informasi cuaca seperti deskripsi cuaca, suhu, dan ikon cuaca, serta menyimpan dan memuat data cuaca favorit ke dalam file.

## Fitur Aplikasi

- Mengambil data cuaca terkini berdasarkan nama kota
- Menampilkan deskripsi cuaca dan suhu dalam satuan Celsius
- Menampilkan ikon cuaca berdasarkan kondisi cuaca
- Menyimpan data cuaca yang diperoleh ke dalam file teks
- Memuat data cuaca dari file yang sudah disimpan sebelumnya
- Menambahkan kota favorit ke dalam daftar kota yang sering digunakan
- Antarmuka pengguna yang sederhana dan interaktif

## Komponen Utama

- **JFrame, JPanel, JLabel, JTextField, JComboBox, JButton** untuk membuat antarmuka pengguna yang interaktif.
- **ItemListener** pada ComboBox untuk memilih kota favorit dan menampilkan cuaca.
- **ActionListener** pada tombol untuk mengambil data cuaca dan menyimpan/memuat data.
- Menggunakan **HttpURLConnection** untuk mengambil data dari API OpenWeatherMap.
- Penanganan **IOException** dan **JSONException** untuk menangani kesalahan saat mengambil data cuaca atau memproses file.

## Cara Menggunakan

1. Masukkan nama kota pada kolom teks "MASUKAN LOKASI".
2. Klik tombol "CEK CUACA" untuk mendapatkan informasi cuaca terkini untuk kota tersebut.
3. Pilih kota dari daftar kota favorit pada "PILIH LOKASI FAVORIT" untuk melihat cuaca favorit yang telah disimpan.
4. Klik tombol "TAMBAH KE FAVORIT" untuk menambahkan kota yang dipilih ke dalam daftar kota favorit.
5. Klik tombol "SIMPAN" untuk menyimpan data cuaca yang ditampilkan ke dalam file teks.
6. Klik tombol "MUAT DATA" untuk memuat data cuaca dari file yang telah disimpan sebelumnya.
7. Klik tombol "HAPUS" untuk menghapus data cuaca yang ada di tabel.
8. Klik tombol "KELUAR" untuk menutup aplikasi.

## Authors

Muhhammad Ikhya 2210010405

## DEMO

![DEMO GIF](img/cuacademo.gif)
