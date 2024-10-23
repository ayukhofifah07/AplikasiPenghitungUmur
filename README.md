# AplikasiPenghitungUmur

## Identitas:
Nama: Ayu Atut Khofifah

NPM: 2210010553

## Penjelasan Program

**Deskripsi Program:**
Program ini memungkinkan pengguna untuk menghitung umur berdasarkan tanggal lahir yang dipilih menggunakan komponen *JDateChooser*. Setelah pengguna menekan tombol "Hitung", program akan menghitung dan menampilkan umur dalam bentuk tahun, bulan, dan hari. Aplikasi ini ditujukan untuk menyediakan perhitungan usia secara otomatis dan cepat berdasarkan input tanggal lahir.

**Komponen GUI:**
- Program menggunakan beberapa komponen GUI dasar dari *Swing* seperti:
  - `JFrame`: Untuk membuat jendela utama dari aplikasi.
  - `JPanel`: Panel untuk menampung komponen-komponen lainnya.
  - `JLabel`: Label untuk memberikan petunjuk atau keterangan pada pengguna.
  - `JDateChooser`: Komponen dari pustaka pihak ketiga untuk memilih tanggal lahir dengan lebih mudah.
  - `JButton`: Tombol untuk mengeksekusi perintah, dalam hal ini tombol "Hitung" digunakan untuk memulai perhitungan umur.
  - `JTextField`: Menampilkan hasil perhitungan umur dalam bentuk teks.

**Logika Program:**
- Logika utama dari program ini adalah manipulasi tanggal menggunakan kelas `LocalDate` dari pustaka *Java 8*. Perhitungan umur dilakukan dengan membandingkan tanggal lahir yang dipilih pengguna dengan tanggal hari ini, sehingga bisa dihitung perbedaan antara kedua tanggal tersebut dalam bentuk tahun, bulan, dan hari.

**Events:**
- Program memanfaatkan event-event berikut untuk interaksi pengguna:
  - *ActionListener* digunakan pada tombol "Hitung" agar program tahu kapan pengguna ingin menghitung umur.
  - *PropertyChangeListener* digunakan pada *JDateChooser* untuk mendeteksi perubahan tanggal yang dipilih pengguna, sehingga input yang diberikan bisa langsung digunakan untuk perhitungan.

**Variasi Tambahan:**
- Program ini bisa dikembangkan lebih lanjut dengan menyediakan informasi tambahan seperti menghitung kapan ulang tahun berikutnya akan tiba.
- Integrasi dengan API eksternal dapat dilakukan untuk menampilkan peristiwa penting yang terjadi pada tanggal lahir pengguna, memberikan informasi yang lebih menarik dan interaktif.

## Keunggulan Program:

1. **Penggunaan Komponen GUI yang Intuitif**: 
   - Program ini memanfaatkan komponen GUI seperti *JDateChooser* yang memudahkan pengguna untuk memilih tanggal tanpa harus mengetik secara manual, sehingga meminimalisir kesalahan input.
   
2. **Akurasi Perhitungan**:
   - Dengan memanfaatkan kelas `LocalDate` dari Java 8, program ini mampu menghitung umur dengan sangat akurat hingga ke hitungan hari, bukan hanya tahun atau bulan. Ini memastikan bahwa hasil perhitungan selalu tepat.

3. **Event-Driven Programming**:
   - Penggunaan *ActionListener* dan *PropertyChangeListener* membuat program lebih interaktif dan responsif. Program secara otomatis mendeteksi perubahan tanggal yang dipilih serta merespons dengan cepat saat tombol *Hitung* ditekan.

4. **Kemudahan Pengembangan**:
   - Program ini memiliki struktur yang modular, sehingga mudah dikembangkan lebih lanjut. Misalnya, dapat ditambahkan fitur baru seperti penghitungan ulang tahun berikutnya atau integrasi dengan API eksternal untuk menampilkan informasi terkait tanggal lahir pengguna.

5. **Dapat Diintegrasikan dengan API Eksternal**:
   - Program ini dirancang dengan fleksibilitas yang tinggi, sehingga bisa dengan mudah dihubungkan dengan API eksternal untuk menampilkan informasi tambahan, seperti peristiwa bersejarah yang terjadi pada tanggal lahir, yang bisa menambah nilai informasi dari aplikasi.

6. **Cocok untuk Berbagai Kebutuhan**:
   - Aplikasi ini dapat digunakan untuk berbagai keperluan, seperti administrasi, pelayanan publik, atau bahkan aplikasi pribadi untuk menghitung umur seseorang secara cepat dan tepat.

7. **Mudah Digunakan**:
   - Antarmuka yang sederhana dan komponen yang familiar seperti tombol dan field input menjadikan program ini mudah digunakan oleh pengguna dari berbagai tingkat keahlian komputer, baik itu pengguna awam maupun pengguna yang sudah berpengalaman.

## Ini dia Screenshot Programnya

**1.**
![ss an AplikasiPenghitungUmur2](https://github.com/user-attachments/assets/9b9cfe5a-13de-47ef-828a-0092f15215d4)


**2.**
![ss an AplikasiPenghitungUmur](https://github.com/user-attachments/assets/5c7fc8f3-435c-41e9-bfb9-bad31dd37f47)

