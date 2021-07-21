# Aplikasi Iuran Kas Rt CodeIgniter4

Program sederhana Aplikasi Iuran Kas RT menggunakan Ajax dengan CodeIgniter4.

# Installation

### Clone the repository:

```
git clone https://github.com/ibrahimnovrizain/iuran_kas.git
```

### Pindah ke directory iuran_kas:

```
cd iuran_kas
```

### Install dependency composer dengan git bash atau terminal:

```
composer install
```

### Buat database baru. Kemudian rename file .env.example ke .env selanjutnya sesuaikan dengan konfigurasi database:

```
database.default.hostname = localhost
database.default.database = iuran_kas
database.default.username = root
database.default.password =
database.default.DBDriver = MySQLi
```

### Migrasi database:

```
php spark migrate
```


### Jalankan aplikasi dengan perintah:

```
php spark serve
```

Sekarang buka browser dengan alamat address http://localhost:8080/

# Screenshoot | Demo on [Iuran-kas](http://iuran-kas.xyz/)



[Dashboard][1](https://user-images.githubusercontent.com/81977333/126478057-7549f794-0ab6-4241-bd88-8e07e874f19c.png)

[Warga][2](https://user-images.githubusercontent.com/81977333/126478125-7464d4f6-575d-441d-93c4-296f00fd565b.png)

[Update][3](https://user-images.githubusercontent.com/81977333/126478172-6b72c5fc-441c-4a2f-8215-b3129737cb5c.png)

[Delete][4](https://user-images.githubusercontent.com/81977333/126478192-2580498d-1bc9-4ae7-9be9-49a60586147a.png)

[Iuran][5](https://user-images.githubusercontent.com/81977333/126478211-2a25d293-7cb9-4780-bdf0-77edafc33ca1.png)

[Laporan][6](https://user-images.githubusercontent.com/81977333/126478233-d82f3545-f81a-43fd-b690-3c7cd79d5b9d.png)
