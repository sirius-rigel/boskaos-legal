# Kebijakan Privasi Bos Kaos

**Aplikasi:** Bos Kaos Katalog Publisher  
**Pengelola:** Bos Kaos Pontianak  
**Terakhir diperbarui:** 20 Oktober 2026  
**Kontak:** boskaospontianak@gmail.com

## Tentang aplikasi

Aplikasi ini digunakan untuk mendukung pengelolaan konten dan pelaporan akun media sosial Bos Kaos sesuai izin yang diberikan pemilik akun.

Fitur pemantauan pesan Instagram dan pemberitahuan Telegram masih dalam tahap persiapan. Ketentuan pemrosesan pesan di bawah berlaku ketika fitur tersebut diaktifkan.

## Data yang diproses

Sesuai fitur dan izin yang diaktifkan, aplikasi dapat memproses:

- Identitas akun media sosial yang terhubung.
- Informasi konten, seperti ID posting, caption, waktu terbit, tautan, dan metrik performa yang tersedia melalui API resmi.
- Untuk pemantauan pesan: ID pesan, akun tujuan, identitas pengirim yang tersedia, waktu pesan, serta teks pesan yang diperlukan untuk membuat cuplikan pemberitahuan.
- Catatan teknis minimum untuk mendeteksi kegagalan dan mencegah pemberitahuan ganda.

Ketersediaan data mengikuti izin akun dan batas API resmi. Aplikasi tidak meminta kata sandi Instagram melalui pesan atau halaman kebijakan ini.

## Tujuan penggunaan

Data digunakan untuk pengelolaan konten yang diizinkan, pelaporan performa akun, pemberitahuan pesan masuk kepada pengelola Bos Kaos, pencegahan duplikasi, dan pemulihan layanan setelah gangguan.

Pada tahap awal, fitur pemantauan pesan hanya memberikan pemberitahuan. Fitur ini tidak dirancang untuk membalas pesan, menerima atau menolak permintaan pesan, menghapus pesan, atau sengaja mengubah status baca.

## Penyimpanan pesan

VPS menyimpan ID pesan, waktu, dan status pemberitahuan paling lama **30 hari sejak pemrosesan**, kemudian menghapusnya.

Isi pesan lengkap tidak disimpan secara permanen di VPS oleh fitur pemantauan. Pesan diproses sementara untuk menghasilkan cuplikan.

Pemberitahuan di Telegram dapat memuat identitas pengirim, waktu, akun tujuan, dan cuplikan pesan. Salinan tersebut tetap berada dalam riwayat Telegram sampai dihapus; penghapusan catatan VPS setelah 30 hari tidak otomatis menghapus riwayat Telegram.

## Layanan pendukung

Pemrosesan melibatkan layanan Meta untuk akses Instagram, penyedia VPS untuk menjalankan pemantauan, dan Telegram untuk mengirim pemberitahuan kepada pengelola yang berwenang.

Halaman kebijakan ini diterbitkan melalui GitHub Pages. GitHub dapat memproses data kunjungan sesuai kebijakan privasinya.

Data pesan tidak diterbitkan dalam repository GitHub. Pemanggilan model AI tidak diperlukan untuk pemberitahuan dasar. Penggunaan AI tambahan akan dibahas dan dijelaskan sebelum diaktifkan.

## Permintaan akses, koreksi, dan penghapusan

Kirim permintaan ke **boskaospontianak@gmail.com** dengan subjek **Permintaan Data Bos Kaos**.

Cantumkan username Instagram dan keterangan yang cukup untuk menemukan data terkait. Jangan mengirim kata sandi, token, atau dokumen identitas sensitif.

Pengelola akan memverifikasi permintaan secara wajar dan menangani data yang berada dalam kendalinya. Permintaan penghapusan dapat mencakup catatan pemantauan dan salinan pemberitahuan Telegram yang dapat dikelola Bos Kaos. Permintaan ini tidak otomatis menghapus pesan asli atau data pada layanan Meta dan Telegram di luar kendali Bos Kaos.

## Perubahan kebijakan

Kebijakan akan diperbarui apabila fitur, tujuan penggunaan, layanan pendukung, atau penyimpanan data berubah. Tanggal pembaruan ditampilkan di bagian atas halaman.
