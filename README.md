## Experiment 2.1: Kode Asli dan Cara Menjalankannya

Aplikasi broadcast chat menggunakan websocket server dan beberapa websocket client. Pertama, server dijalankan menggunakan:

cargo run --bin server

Setelah server aktif, client dapat dijalankan menggunakan:

cargo run --bin client

Ketika sebuah client mengirim pesan, server menerima pesan tersebut lalu melakukan broadcast ke seluruh client lain yang terhubung. Tutorial ini menunjukkan bagaimana asynchronous programming dapat menangani banyak koneksi secara bersamaan tanpa membuat program menjadi blocking.

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)

