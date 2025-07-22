# Aplikasi Tic-Tac-Toe dengan React

Ini adalah aplikasi permainan Tic-Tac-Toe sederhana yang dibuat menggunakan React. Permainan ini memungkinkan dua pemain untuk bermain secara bergiliran sebagai "X" dan "O" di papan berukuran 3x3. Pemain pertama yang berhasil menyusun tiga simbol secara horizontal, vertikal, atau diagonal akan menang.

## Fitur

- Permainan dua pemain secara bergiliran (X dan O)
- Menampilkan status permainan (giliran berikutnya atau pemenang)
- Fitur untuk melihat dan melompat ke langkah-langkah sebelumnya
- Komponen `Square` tanpa status (stateless)
- Manajemen status menggunakan React Hooks

## Komponen

### `Square`
Komponen tanpa status yang merepresentasikan satu kotak pada papan permainan.

### `Board`
Bertanggung jawab untuk merender 9 kotak, menangani logika permainan seperti menentukan pemenang dan giliran pemain.

### `Game`
Komponen utama yang mengelola status permainan, riwayat langkah, dan merender papan serta daftar langkah.

### `calculateWinner`
Fungsi utilitas untuk menentukan apakah seorang pemain telah memenangkan permainan.

## Cara Menjalankan

1. Pastikan Anda sudah menginstal Node.js dan npm.
2. Buat aplikasi React baru menggunakan Vite atau Create React App.
3. Ganti file `App.jsx` atau komponen utama dengan kode ini.
4. Jalankan server pengembangan.

## Contoh Instalasi dengan Vite

```bash
npm create vite@latest tic-tac-toe --template react
cd tic-tac-toe
npm install
# Ganti App.jsx dengan kode yang diberikan
npm run dev
```

## Lisensi

Lisensi MIT. Bebas digunakan dan dimodifikasi.
