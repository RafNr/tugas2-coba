# Pengenalan Aplikasi Django dan Models View Template (MVT) pada Django

## Bagan yang berisi request client ke web aplikasi berbasis Django beserta responnya dan jelaskan pada bagan tersebut kaitan antara urls.py, views.py, models.py, dan berkas html

![Untitled Diagram drawio](https://user-images.githubusercontent.com/90234027/191789446-0a8be683-73ca-409c-840b-c00a95163c65.png)


1. Permintaan masuk pada server Django akan diproses melalui urls.py dan diteruskan ke views.py
2. Jika diperlukan database views.py akan memanggil models.py melalui fungsi show_wishlist kemudian show_wishlist meminta semua object BarangWishlist dari models.py
3. Pada BarangWishlist terdiri dari nama, harga, dan deskripsi barang kemjdan data akan dikembalikan ke views.py
4. Hasil proses tersebut akan di mapping di html yang sudah didefinisikan kemudian html akan menjadi respon user


## Virtual Environment
Virtual Env dibutuhkan agar masing masing aplikasi memiliki modulnya sendiri, jika membuat aplikasi web berbasis Django tanpa menggunakan virtual environment maka tidak bisa berjalan dengan modul versi baru

## Cara Implementasi

1. Permintaan masuk pada server Django akan diproses melalui urls.py dan diteruskan ke views.py
2. Jika diperlukan database views.py akan memanggil models.py melalui fungsi show_wishlist kemudian show_wishlist meminta semua object BarangWishlist dari models.py
3. Pada BarangWishlist terdiri dari nama, harga, dan deskripsi barang kemjdan data akan dikembalikan ke views.py
4. Hasil proses tersebut akan di mapping di html yang sudah didefinisikan kemudian html akan menjadi respon user


## Link Heroku

https://tugas2-coba.herokuapp.com/
