Untuk menghitung gerakan push-up menggunakan Teachable Machine, kamu bisa memanfaatkan model pose detection (deteksi pose) dan JavaScript. Berikut langkah-langkah umumnya:

Alat yang Dibutuhkan:
1. Teachable Machine Pose Project
2. Webcam
3. HTML + JavaScript (untuk menjalankan model di browser)

Logika penghitung (counter)
1. Latih Model di Teachable Machine
2. Buka Teachable Machine - Pose.
3. Buat 2 kelas:
-> Down – posisi saat dada mendekati lantai
-> Up – posisi saat tangan lurus, tubuh terangkat
4. Rekam video untuk masing-masing pose menggunakan webcam (ambil beberapa sudut untuk akurasi).
5. Klik Train Model, lalu Export Model → pilih TensorFlow.js dan salin link model
6. Masukkan link model pada Skrip pushUp.html


Berlaku untuk semua GERAKAN OLAH RAGA
