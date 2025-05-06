Untuk menghitung gerakan push-up menggunakan Teachable Machine, kamu bisa memanfaatkan model pose detection (deteksi pose) dan JavaScript. Berikut langkah-langkah umumnya:

🔧 Alat yang Dibutuhkan:
1. Teachable Machine Pose Project
2. Webcam
3. HTML + JavaScript (untuk menjalankan model di browser)

Logika penghitung (counter)
🧠 Latih Model di Teachable Machine
1. Buka Teachable Machine - Pose.
   https://teachablemachine.withgoogle.com/train/pose
2. Buat 2 kelas:
-> Down – posisi saat dada mendekati lantai
-> Up – posisi saat tangan lurus, tubuh terangkat
3. Rekam video untuk masing-masing pose menggunakan webcam (ambil beberapa sudut untuk akurasi).
4. Klik Train Model, lalu Export Model → pilih TensorFlow.js dan salin link model
5. Masukkan link model pada Skrip pushUp.html

🔁 Logika Prinsip Kerja:
Deteksi transisi Dari "Down" ke "Up" sebagai 1 push-up.

📝 Tips:
1. Gunakan pencahayaan yang cukup.
2. Kamera harus bisa melihat tubuh bagian atas dengan jelas.
3. Semakin banyak contoh pelatihan, semakin akurat model
4. Berlaku untuk semua GERAKAN OLAH RAGA
