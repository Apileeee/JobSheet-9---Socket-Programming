# Socket Programming

Socket Programming memungkinkan komunikasi antarproses melalui jaringan menggunakan soket. Paradigma ini penting dalam pengembangan aplikasi jaringan untuk berbagi informasi dan melakukan komunikasi terdistribusi.

## State Diagram Server dan Client

- Node server dan klien terhubung melalui soket di lapisan transport internet.
- Setelah koneksi terbentuk, node dapat berbagi informasi menggunakan perintah baca dan tulis.
- Setelah pertukaran informasi selesai, node menutup koneksi.

## WebSocket

WebSocket adalah protokol komunikasi dua arah melalui satu koneksi TCP, mendukung komunikasi real-time. Berbeda dengan HTTP, WebSocket memungkinkan koneksi terbuka dan pertukaran pesan kontinu.

## Socket.io

Socket.io adalah library untuk socket programming menggunakan WebSockets di Node.js. Mempunyai fitur seperti rekoneksi otomatis, penyimpanan paket sementara, pengakuan, dan multiplexing.

## Struktur Proyek

1. Buat folder 'ruangobrol' dengan struktur file dan folder yang disediakan.
2. Implementasikan server dan client menggunakan Node.js dan Socket.io.

## File Utama

- **index.js**: Server Node.js dengan Express dan Socket.io.
- **users.js**: Fungsi-fungsi pengelolaan pengguna.
- **messages.js**: Fungsi-fungsi pengelolaan pesan.
- **index.html**: Halaman utama aplikasi.
- **chat.html**: Halaman chat dengan fitur pesan dan lokasi.

## Langkah Pembuatannya

1. Buatlah folder baru dengan nama 'ruangobrol'.
2. Atur struktur file dan folder sesuai dengan petunjuk.
3. Implementasikan server dan client menggunakan Node.js dan Socket.io.
4. Jalankan aplikasi dengan perintah `npm run dev`.
5. Buka `localhost:3000` pada dua tab atau browser berbeda.
6. Gunakan display name yang berbeda untuk login dengan nama room yang sama.
7. Lakukan langkah 5 dan 6 dengan nama room yang berbeda.
