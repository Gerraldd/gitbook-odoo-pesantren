---
icon: list
---

# Kategori Produk

Video \[]

## Master Data - Kategori Produk

Data **Kategori Produk** berfungsi untuk mengelompokkan berbagai jenis produk yang digunakan atau dijual dalam lingkungan pesantren. Pengelompokan ini penting untuk memudahkan pengelolaan inventaris, penjualan, pembelian, maupun distribusi produk kepada santri atau unit lain.

### Menambahkan Kategori Produk

Berikut adalah langkah-langkah untuk menambahkan kategori produk pada Odoo Pesantren.

1. Login menggunakan akun administrator. Jika Anda belum memahami cara login sebagai admin, silakan lihat panduan [**Login Admin** di sini](../../panduan-login/login-admin.md).
2.  Buka modul **Stok Persediaan**, lalu klik menu **Konfigurasi** kemudian pilih submenu **Kategori Produk**.

    <figure><img src="../../.gitbook/assets/images-202.png" alt=""><figcaption></figcaption></figure>


3.  Klik tombol **“Baru”** untuk membuat kategori produk baru.&#x20;

    <figure><img src="../../.gitbook/assets/images-203.png" alt=""><figcaption></figcaption></figure>


4.  Akan tampil halaman form, isi inputan yang tersedia seperti:

    * **Kategori** (isi dengan nama kategori produk yang akan di tambahkan).
    * **Kategori Induk** (opsional, bisa diisi dengan jika ada jalur distribusi atau alur logistik khusus).
    * **Logistik** (opsional, )
    * Akun Properti, pilih akun-akun berikut sesuai dengan kebijakan keuangan:
      * Akun Laba: Akun yang mencatat penjualan (misal: 41000010 Penjualan)
      * Akun Beban: Akun yang mencatat HPP (misal: 51000010 Harga Pokok Penjualan)
    * Metode Penetapan Biaya (umumnya untuk pesantren, cukup pilih Standar Harga jika stok tidak terlalu fluktuatif).

    <figure><img src="../../.gitbook/assets/images-204.png" alt=""><figcaption></figcaption></figure>


5.  Setelah semua inputan diisi dengan benar, klik icon **Simpan** di sebelah kanan icon **Gear** agar data kategori produk tersimpan di sistem.

    <figure><img src="../../.gitbook/assets/images-205.png" alt=""><figcaption></figcaption></figure>


6. Data Kategori Produk berhasil disimpan dan siap digunakan untuk mengelompokkan produk.

### Edit dan Hapus Data Kategori Produk

Untuk mengedit suatu data kategori produk, silahkan pilih terlebih dahulu data mana yang akan diedit. Editlah data kategori produk dan klik icon **Simpan** untuk menyimpan data perubahan tersebut.

Untuk menghapus suatu data kategori produk adalah dengan pilih data mana yang akan dihapus, kemudian klik icon **Gear** atau **Action** lalu pilih opsi **Hapus**, maka akan tampil dialog konfirmasi apakah anda ingin menghapus data tersebut. Jika ya, klik **Hapus** jika tidak maka klik **Tidak, tetap simpan**.

***

{% hint style="danger" %}
Data **Kategori Produk** tidak dapat dihapus apabila sudah terdapat transaksi yang berhubungan dengan data tersebut. Jika belum ada transaksi yang tercatat, maka data masih dapat dihapus dari sistem.
{% endhint %}
