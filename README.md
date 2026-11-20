# AI_LOGBOOK.md

# DOKUMENTASI PENGGUNAAN ARTIFICIAL INTELLIGENCE (AI)

**Nama Produk:** NASKARA\
**Jenis Produk:** Website / Aplikasi Berbasis Web\
**Teknologi:** HTML, CSS, JavaScript, dan Node.js\
**Tujuan Proyek:** Membuat website yang dapat membantu pengguna menyusun, mengembangkan, dan memperbaiki makalah dengan bantuan AI.

## 1. Eksplorasi Ide dan Perancangan Solusi

**Tahap: Eksplorasi Ide**

Pada tahap awal, saya menggunakan bantuan AI untuk mencari ide dan menentukan konsep produk digital yang akan dibuat. Saya ingin membuat sebuah website yang dapat membantu siswa dalam mengerjakan tugas makalah, terutama bagi pengguna yang masih kesulitan menyusun materi menjadi tulisan yang terstruktur.

Saya kemudian mengembangkan ide tersebut menjadi sebuah website bernama NASKARA. Website ini dirancang agar pengguna cukup memasukkan materi atau topik singkat, kemudian AI dapat membantu mengembangkannya menjadi sebuah makalah yang memiliki struktur penulisan yang baik.

**Interaksi dengan AI:**

Saya meminta AI memberikan ide fitur yang cocok untuk website pembuat dan pengoreksi makalah. Saya juga meminta saran mengenai tampilan, teknologi, dan cara kerja website tersebut.

**Contoh prompt yang digunakan:**

"Buatkan konsep website berbasis AI yang dapat membantu siswa membuat makalah dari materi singkat. Website harus memiliki fitur pembuat makalah, asisten AI, pemeriksa kesalahan tulisan, peringkas materi, serta fitur untuk mengubah makalah menjadi presentasi PowerPoint."

**Hasil dari AI:**

AI memberikan beberapa ide fitur, seperti AI Paper Generator, AI Assistant, AI Reviewer, AI Summarizer, editor dokumen, unggah file, dan pembuat presentasi.

**Validasi dan Modifikasi Mandiri:**

Setelah mendapatkan saran dari AI, saya memilih fitur yang paling sesuai dengan tujuan proyek. Saya juga menyesuaikan konsep website agar lebih mudah digunakan oleh siswa dan tidak terlalu rumit. Nama produk akhirnya ditetapkan menjadi NASKARA.

## 2. Penyusunan Kerangka Kode dan Pembuatan Website

**Tahap: Penyusunan Kerangka Kode (Scaffolding)**

Pada tahap ini, saya menggunakan AI untuk membantu menyusun struktur dasar website dan membuat kode program. Karena kemampuan pemrograman saya masih dalam tahap dasar, saya meminta AI menjelaskan fungsi setiap bagian kode agar lebih mudah dipahami.

Website NASKARA dikembangkan menggunakan HTML untuk membuat struktur halaman, CSS untuk mengatur tampilan, dan JavaScript untuk mengatur interaksi pengguna. Selain itu, saya juga menggunakan Node.js sebagai bagian dari backend agar website dapat terhubung dengan layanan AI.

**Interaksi dengan AI:**

Saya meminta AI membuat kode website dengan tampilan modern, sederhana, dan nyaman digunakan. Saya juga meminta agar kode HTML, CSS, dan JavaScript dipisahkan ke dalam file masing-masing supaya lebih mudah dipelajari dan diperbaiki.

**Contoh prompt yang digunakan:**

"Buatkan source code website NASKARA menggunakan HTML, CSS, dan JavaScript yang terpisah. Website harus memiliki dashboard, editor makalah, fitur AI Assistant, fitur pemeriksa makalah, dan fitur unggah dokumen. Buat desain yang modern, responsif, serta mudah digunakan oleh siswa."

**Hasil dari AI:**

AI membantu menyusun struktur folder, membuat tampilan halaman utama, menambahkan tombol interaktif, dan menyusun beberapa fungsi dasar website.

**Validasi dan Modifikasi Mandiri:**

Saya memeriksa struktur file dan mencoba menjalankan website melalui browser. Saya juga menyesuaikan beberapa bagian tampilan dan fitur berdasarkan kebutuhan proyek. Saya memilih untuk memisahkan kode HTML, CSS, dan JavaScript agar pengembangan selanjutnya lebih mudah dilakukan.

## 3. Pemecahan Masalah dan Perbaikan Kesalahan

**Tahap: Debugging**

Dalam proses pembuatan NASKARA, saya menemukan beberapa kendala. Salah satu masalah yang muncul adalah fitur pendaftaran akun tidak dapat digunakan dan menampilkan pesan "Permintaan gagal".

Saya kemudian meminta bantuan AI untuk mencari kemungkinan penyebab masalah tersebut. Setelah mempertimbangkan kebutuhan proyek, saya memutuskan untuk mengubah sistem website agar tidak lagi menggunakan halaman login dan pendaftaran akun.

Sebagai gantinya, saya memilih sistem penyimpanan sementara menggunakan RAM.

**Interaksi dengan AI:**

Saya meminta AI membantu memeriksa kemungkinan kesalahan pada sistem pendaftaran dan memberikan solusi yang lebih sesuai dengan kebutuhan website.

**Contoh prompt yang digunakan:**

"Perbaiki sistem website NASKARA yang mengalami kegagalan saat membuat akun. Saya ingin menghilangkan halaman login dan registrasi. Sebagai gantinya, buat sistem penyimpanan sementara menggunakan RAM dan berikan peringatan kepada pengguna bahwa dokumen tidak akan tersimpan secara permanen."

**Hasil dari AI:**

AI memberikan solusi berupa penghapusan sistem login dan penggunaan penyimpanan sementara pada backend. AI juga membantu membuat pemberitahuan bahwa dokumen dapat hilang ketika server dihentikan atau dimulai ulang.

**Validasi dan Modifikasi Mandiri:**

Saya memutuskan menggunakan sistem tanpa akun karena lebih sederhana dan sesuai dengan konsep penggunaan NASKARA. Saya juga memastikan adanya pemberitahuan mengenai risiko kehilangan data sehingga pengguna dapat mengunduh hasil pekerjaannya sebelum meninggalkan website.

## 4. Refleksi dan Penjelasan Kode

**Tahap: Refleksi dan Penjelasan Kode**

Setelah proses pembuatan website, saya mempelajari kembali kode yang telah dibuat dengan bantuan AI. Saya mencoba memahami fungsi setiap teknologi dan hubungan antara frontend dengan backend.

Beberapa bagian kode yang saya pelajari antara lain:

1. **HTML:** Digunakan untuk membuat struktur halaman website, seperti dashboard, tombol, formulir, dan area editor makalah.
2. **CSS:** Digunakan untuk mengatur warna, ukuran tulisan, jarak antarbagian, tata letak, dan tampilan website agar lebih menarik.
3. **JavaScript:** Digunakan untuk membuat fitur interaktif, seperti tombol, pengolahan teks, unggah file, dan komunikasi dengan backend.
4. **Node.js:** Digunakan untuk menjalankan backend yang menangani permintaan dari pengguna dan menghubungkan website dengan layanan AI.
5. **Database dan Penyimpanan RAM:** Pada rancangan awal terdapat penggunaan database, tetapi kemudian saya memilih penyimpanan sementara menggunakan RAM agar tidak memerlukan sistem akun.

**Interaksi dengan AI:**

Saya meminta AI menjelaskan fungsi kode dan memberikan penjelasan sederhana agar saya dapat memahami cara kerja website yang dibuat.

**Contoh prompt yang digunakan:**

"Jelaskan fungsi setiap file HTML, CSS, dan JavaScript dalam proyek NASKARA. Jelaskan juga bagaimana frontend berkomunikasi dengan backend dan bagaimana sistem AI memproses permintaan pengguna menggunakan bahasa yang mudah dipahami oleh pemula."

**Hasil dari AI:**

AI memberikan penjelasan mengenai fungsi setiap file dan hubungan antarbagian website. Penjelasan tersebut membantu saya memahami bahwa sebuah website tidak hanya terdiri dari tampilan, tetapi juga membutuhkan proses backend untuk menjalankan fitur tertentu.

**Validasi dan Modifikasi Mandiri:**

Saya mempelajari kembali kode yang diberikan dan mencoba memahami bagian-bagian pentingnya. Saya juga menentukan perubahan fitur berdasarkan kebutuhan proyek, bukan hanya menerima semua saran AI secara langsung.


## 5. Kesimpulan Penggunaan AI

Selama proses pembuatan NASKARA, AI sangat membantu dalam mencari ide, menyusun struktur program, membuat kode awal, dan menemukan solusi ketika terjadi kesalahan.

Namun, AI tidak sepenuhnya menggantikan proses belajar dan pemahaman saya. Saya tetap perlu memeriksa hasil yang diberikan, menentukan fitur yang sesuai, serta melakukan penyesuaian berdasarkan kebutuhan proyek.

Melalui proses ini, saya mendapatkan pengalaman baru mengenai pengembangan website, terutama dalam penggunaan HTML, CSS, JavaScript, dan backend. Saya juga belajar bahwa penggunaan AI harus disertai pemeriksaan dan pemahaman agar hasil akhirnya sesuai dengan tujuan yang ingin dicapai.

**Catatan:** AI digunakan sebagai alat bantu dalam proses pengembangan. Keputusan akhir mengenai fitur, perubahan kode, dan hasil produk tetap disesuaikan dengan kebutuhan proyek.
