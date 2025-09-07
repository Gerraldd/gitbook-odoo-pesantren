---
icon: notebook
---

# Umur Saldo Mitra

Video \[]

## Umur Saldo Mitra (Aged Partner Balance)

Laporan **Umur Saldo Mitra (Aged Partner Balance)** adalah laporan yang menampilkan rincian saldo piutang maupun hutang mitra (partner) berdasarkan umur atau lamanya waktu tunggakan. Laporan ini biasanya digunakan untuk memantau pembayaran pelanggan dan kewajiban kepada pemasok sesuai periode tertentu, sehingga membantu pengelolaan arus kas dan pengambilan keputusan keuangan.

### Mencetak Laporan Umur Saldo Mitra

Berikut adalah langkah-langkah untuk mencetak laporan umur saldo mitra pada Odoo Pesantren.

1. Login menggunakan akun administrator. Jika Anda belum memahami cara login se bagai admin, silakan lihat panduan [**Login Admin** di sini](../../panduan-login/login-admin.md).
2.  Buka modul **Penagihan**, lalu klik menu **Laporan** kemudian pilih submenu **Umur Saldo Mitra**.

    <figure><img src="../../.gitbook/assets/images-775 (1).png" alt=""><figcaption></figcaption></figure>


3.  Akan tampil sebuah **form konfigurasi laporan**. Pada form ini, lakukan pengaturan berikut:

    * **Tanggal Acuan**: masukkan tanggal yang dijadikan patokan untuk perhitungan umur saldo.
    * **Lama Periode**: tentukan interval periode (misalnya 30 hari) untuk pengelompokan umur saldo.
    * **Partner**: pilih jenis akun yang ingin ditampilkan, yaitu:
      * _Receivable Accounts_ → menampilkan saldo piutang pelanggan.
      * _Payable Accounts_ → menampilkan saldo hutang pemasok.
      * _Receivable and Payable Accounts_ → menampilkan keduanya.
    * **Target Moves**: pilih _All Posted Entries_ untuk hanya menampilkan transaksi yang sudah diposting, atau _All Entries_ untuk menampilkan semua transaksi termasuk draft.

    <figure><img src="../../.gitbook/assets/images-776 (1).png" alt=""><figcaption></figcaption></figure>


4. Setelah semua konfigurasi selesai, klik tombol **"Print"** untuk menghasilkan laporan Umur Saldo Mitra.
5.  Sistem akan menampilkan laporan dalam format **PDF**.

    <figure><img src="../../.gitbook/assets/images-777 (1).png" alt=""><figcaption></figcaption></figure>


6.  Buka file PDF tersebut untuk melihat rincian saldo mitra yang dikelompokkan berdasarkan periode umur piutang/hutang (misalnya: 0–30 hari, 31–60 hari, 61–90 hari, dan seterusnya).

    <figure><img src="../../.gitbook/assets/images-778 (2).png" alt=""><figcaption></figcaption></figure>


7. Jika diperlukan, laporan ini dapat **disimpan** sebagai arsip atau **dibagikan** kepada tim keuangan untuk tindak lanjut lebih lanjut seperti penagihan atau pembayaran.
