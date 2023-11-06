# Jawaban Tugas Modul 6

Penjelasan Kode

1.) State

Program ini mendefinisikan sebuah enumerasi yang disebut "State" yang digunakan untuk merepresentasikan berbagai status atau keadaan dalam permainan Tic Tac Toe. Enumerasi "State" ini digunakan dalam permainan Tic-Tac-Toe untuk melacak status saat ini dari permainan, dan ini membantu dalam mengendalikan alur permainan serta menentukan pemenang atau keadaan seri dalam permainan.

2.) Seed

Program ini berisi definisi sebuah enumerasi (enum) yang disebut "Seed." Enum ini digunakan untuk mewakili tiga kemungkinan isi sel pada papan permainan Tic Tac Toe. Tiga nilai yang mungkin untuk enum ini adalah "EMPTY" (sel kosong), "CROSS" (simbol "X"), dan "NOUGHT" (simbol "O"). Enum ini digunakan dalam permainan Tic Tac Toe untuk mengidentifikasi isi setiap sel pada papan permainan, memungkinkan permainan untuk melacak dan mengelola status sel-sel pada papan dengan jelas. Dengan menggunakan enum ini, program dapat dengan mudah mengidentifikasi pemilik setiap sel dan memutuskan pemenang dalam permainan berdasarkan kombinasi simbol "X" atau "O" yang muncul di papan permainan. Ini adalah komponen penting dalam logika permainan Tic Tac Toe yang membantu dalam pemrograman permainan ini.

3.) Game State

Program ini mendefinisikan sebuah enumerasi yang disebut GameState. Enumerasi ini digunakan untuk menggambarkan berbagai kemungkinan status permainan dalam permainan Tic Tac Toe. Dengan menggunakan enumerasi GameState, program dapat mengikuti dan mengidentifikasi status permainan saat ini, yang memungkinkan untuk mengambil tindakan yang sesuai dalam logika permainan Tic-Tac-Toe, seperti menentukan pemenang atau menangani kondisi seri. Ini membantu memisahkan dan mengatur logika permainan dengan lebih baik.

4.) Cell

Program ini digunakan untuk merepresentasikan setiap sel (cell) pada papan permainan. Kelas Cell ini merupakan bagian penting dari permainan Tic Tac Toe yang bertanggung jawab untuk menampilkan dan mengelola isi setiap sel pada papan permainan. Dengan demikian, program ini mendukung representasi visual dari permainan dan memberikan logika yang berkaitan dengan menggambar simbol "X" dan "O" pada sel papan permainan.

5.) Board

Program ini merupakan bagian dari implementasi permainan Tic Tac Toe. Fokus utama dari program ini adalah kelas Board, yang digunakan untuk memodelkan papan permainan dengan sel-selnya. Papan permainan direpresentasikan oleh matriks sel (cells) yang berisi sel-sel permainan. Setiap sel dapat berisi salah satu dari tiga nilai: Seed.CROSS, Seed.NOUGHT, atau Seed.EMPTY. Selain itu, program juga mengatur penampilan papan permainan dengan menggambar grid-lines dan sel-selnya sesuai dengan properti yang telah didefinisikan sebelumnya, seperti ukuran sel, lebar grid-line, dan warna-warna yang digunakan.

6.) Game Main

Kelas GameMain adalah panel yang digunakan untuk menggambar papan permainan, mengelola logika permainan, dan berinteraksi dengan pemain. Program ini memanfaatkan pemrograman berorientasi objek dan paradigma pemisahan kelas untuk menciptakan permainan Tic Tac Toe yang interaktif dan mudah dimengerti bagi pemain. Pemain dapat bermain dengan mengklik sel pada papan, dan program secara otomatis mengelola logika permainan, termasuk penentuan pemenang, hasil imbang, dan perubahan giliran pemain.
