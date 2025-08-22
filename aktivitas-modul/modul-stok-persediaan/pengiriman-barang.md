---
icon: truck
---

# Pengiriman Barang

Video \[]

## Pengiriman Barang

Pada Odoo Pesantren, proses pengiriman barang umumnya terjadi secara otomatis ketika transaksi penjualan dilakukan melalui modul **Point of Sale (POS)**. Sistem akan langsung membuat dan memproses dokumen pengiriman tanpa perlu tindakan manual.\
Namun, dalam kondisi tertentu, pengguna dapat melakukan pengiriman barang secara manual, misalnya untuk pesanan penjualan di luar POS atau kebutuhan khusus lainnya.

### Melakukan Proses Pengiriman Barang

Berikut adalah langkah-langkah untuk melakukan proses pengiriman barang pada Odoo Pesantren.

1. Login menggunakan akun administrator. Jika Anda belum memahami cara login sebagai admin, silakan lihat panduan [**Login Admin** di sini](../../panduan-login/login-admin.md).
2.  Buka modul **Stok Persediaan**, lalu pilih menu **Operasi** dan klik submenu **Pengiriman**.

    <figure><img src="../../.gitbook/assets/images-668 (2).png" alt=""><figcaption></figcaption></figure>


3.  Klik tombol **"Baru"** untuk membuat dokumen pengiriman barang baru.

    <figure><img src="../../.gitbook/assets/images-669 (2).png" alt=""><figcaption></figcaption></figure>


4.  Pada halaman formulir pengiriman barang, isikan **alamat tujuan** atau pilih **pelanggan** yang akan menerima barang.

    <figure><img src="../../.gitbook/assets/images-670 (3).png" alt=""><figcaption></figcaption></figure>


5.  Pilih tanggal terjadwal dan lokasi sumber barang. Di **Tab Operasi**, tambahkan **produk** yang akan dikirim beserta **kuantitas** yang sesuai.

    <figure><img src="../../.gitbook/assets/images-671 (1).png" alt=""><figcaption></figcaption></figure>


6.  Pindah ke **Tab Informasi Tambahan** untuk menentukan **penanggung jawab** atas operasi pengiriman barang tersebut.

    <figure><img src="../../.gitbook/assets/images-672 (2).png" alt=""><figcaption></figcaption></figure>


7.  Jika diperlukan, buka **Tab Catatan** untuk menambahkan keterangan atau informasi penting terkait pengiriman. Setelah semua informasi terisi, klik tombol **"Tandai sebagai To Do"** untuk menandai bahwa pengiriman siap diproses.

    <figure><img src="../../.gitbook/assets/images-673 (2).png" alt=""><figcaption></figcaption></figure>


8. Status pengiriman barang akan menyesuaikan dengan **tanggal terjadwal** yang diinput:
   * Jika **tanggal terjadwal** sama dengan tanggal saat ini, status pengiriman akan berubah menjadi **"Siap"** (_Ready_).
   * Jika **tanggal terjadwal** masih berada setelah tanggal saat ini ini, status pengiriman akan tetap **"Menunggu"** (_Waiting_).
9.  Kembali ke **Tab Operasi** dan pastikan produk, kuantitas, dan detail lainnya sudah benar. Lalu klik tombol **"Validasi"** untuk mengonfirmasi bahwa proses pengiriman barang telah selesai.

    <figure><img src="../../.gitbook/assets/images-674 (3).png" alt=""><figcaption></figcaption></figure>
