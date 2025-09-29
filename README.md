FANDI NURREZKY
2411102441175

1. Mengapa memilih konfigurasi col tertentu untuk tiap breakpoint?
alasan utamanya supaya nyaman dilihat dan nyaman dipakai di semua perangkat dari hp smpai ke layar monitor yang lebi besar
- Di HP (col-12): Layar HP kan sempit Jadi, aku pasang 1 kolom aja biar fotonya kelihatan jelas dan gede
- Pengguna tinggal scroll ke bawah aja, persis kayak pakai aplikasi Instagram beneran.
- Di Desktop (col-lg-3): Di laptop atau PC, layarnya paling luas. Pakai 4 kolom itu udah pas
- Pengguna bisa langsung lihat banyak foto sekaligus.

2. Gimana caranya tombol Follow/Edit Profile dibikin gampang diakses di HP?
Kunci dari pertanyaan ini adalah ergonomi, terutama kemudahan jangkauan ibu jari disaat memakai ponsel, pengguna umumnya memegangnya dari bawah sehingga area bawah layar adalah yang paling mudah diakses.
jadi cara pendekatannya yang baik adalah memindahkan tombol-tombol tersebut ke bawah bio pada tampilan mobile, tetapi tetap menempatkannya di samping nama profil pada layar yang lebih besar.
Anda dapat mencapainya dengan menggunakan utilitas (ORDER) dari Bootstrap.

3. Jika postingan bertambah jadi 50, apa potensi masalah dan bagaimana solusi gridmu mengatasinya?
kalau ada 50 postingan lebih, bakal ada dua masalah besar:
- Loading-nya Lemot: Halaman web bakal berat banget karena harus memuat 50+ gambar sekaligus.
- Bikin Capek Scroll: Bayangin harus scroll sepanjang apa untuk lihat foto paling bawah atau sampai ke footer ga praktis

grid Bootstrap ga secara langsung menyelesaikan masalah ini, tapi grid ini jadi pondasi buat solusinya. Solusinya pake Pagination (penomoran halaman).
jadi, postingannya aku pecah, misalnya 12 foto per halaman. Nanti di bagian bawah galeri ada tombol angka 1, 2, 3, 4, 5... untuk pindah halaman.
