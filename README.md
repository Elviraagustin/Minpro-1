nama : Elvira Agustin

nim : 2409116109

Coding

![Screenshot 2024-10-01 001509](https://github.com/user-attachments/assets/c588993e-5cbe-4696-bbca-0732cefbba28)

Loop while True::

Ini adalah loop tak terbatas yang akan terus berjalan sampai dihentikan oleh perintah break.


Input data:

Program meminta pengguna memasukkan nama dan NIM.
Kemudian meminta harga barang (sebagai float) dan jumlah pembelian (sebagai integer).


Perhitungan total harga:

Total harga dihitung dengan mengalikan harga barang dan jumlah pembelian.


Penentuan diskon:

Menggunakan struktur if-else untuk menentukan apakah pembelian mendapat diskon.
Jika total harga > Rp 250.000, pembeli mendapat diskon 25%.
Jika tidak, tidak ada diskon.


Output:

Program menampilkan total harga, jumlah diskon (jika ada), dan total harga setelah diskon.


Opsi untuk menghitung lagi:

Program bertanya apakah pengguna ingin menghitung lagi.
Jika jawaban bukan 'ya', program akan berhenti dengan pesan terima kasih dan break dari loop.


Penggunaan f-string:

Untuk memformat output angka dengan 2 desimal (contoh: {total_harga:.2f}).


Konversi input:

float() digunakan untuk harga barang agar bisa menerima angka desimal.
int() digunakan untuk jumlah pembelian karena harus bilangan bulat.


Penggunaan lower():

Pada pilihan untuk menghitung lagi, lower() digunakan agar input tidak case-sensitive.

flowchart

![Screenshot 2024-10-01 004500](https://github.com/user-attachments/assets/8780bb0d-6703-45bc-a138-5a77311942cb)

Mulai: Program dimulai.

Input harga barang: Pengguna memasukkan harga per unit barang.

Input jumlah pembelian: Pengguna memasukkan jumlah barang yang dibeli.

Hitung total harga: Program menghitung total harga dengan mengalikan harga barang dan jumlah pembelian.

Cek total harga: Program memeriksa apakah total harga lebih dari Rp. 250.000.


Jika Ya: Lanjut ke perhitungan diskon.

Jika Tidak: Tidak ada diskon yang diberikan.


Hitung diskon (jika berlaku): Jika total harga lebih dari Rp. 250.000, program menghitung diskon sebesar 25% dari total harga.

Hitung total harga setelah diskon (jika berlaku): Program mengurangi jumlah diskon dari total harga awal.

Tampilkan total harga: Program menampilkan total harga akhir (dengan atau tanpa diskon).

Tanya apakah ingin menghitung lagi: Program memberikan pilihan kepada pengguna.


Jika Ya: Kembali ke langkah input harga barang.

Jika Tidak: Program selesai.


Selesai: Program berakhir jika pengguna memilih tidak menghitung total harga lagi.
