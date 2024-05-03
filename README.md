# KAS_RT_Apps

**Anggota Kelompok :** <br>

| Nama                    | NIM       | Kelas     | Mata Kuliah       |
| ------------------------| --------- | --------- | ----------------- |
| Frans Putra Sinaga      | 312210046 | TI.22.A.1 | Pemrograman Web 2 |
| Aas Novitasari          | 312210167 | TI.22.A.1 | Pemrograman Web 2 |
| Fathia Wardah S.Djawas  | 312210196 | TI.22.A.1 | Pemrograman Web 2 |

**Aplikasi Laporan Kas RT:** <br>
Aplikasi kas RT yang menggunakan JSON dan API adalah aplikasi yang memanfaatkan format JSON (JavaScript Object Notation) untuk pertukaran data antara aplikasi klien (misalnya aplikasi di perangkat pengguna) dan server atau penyedia layanan. Sedangkan API (Application Programming Interface) digunakan untuk mengizinkan komunikasi antara aplikasi tersebut dengan server atau layanan eksternal.

Penggunaan JSON dalam aplikasi kas RT biasanya untuk menyimpan dan mengirim data transaksi, anggaran, atau informasi keuangan lainnya antara aplikasi klien dan server. Misalnya, ketika pengguna memasukkan data transaksi pembayaran iuran bulanan, data tersebut dapat dikirimkan ke server dalam format JSON untuk diproses dan disimpan.

Sementara itu, API digunakan untuk mengakses dan memanipulasi data yang tersedia di server atau layanan eksternal. Dalam konteks aplikasi kas RT, API mungkin digunakan untuk mengambil data dari sumber daya eksternal, seperti informasi keuangan dari bank atau integrasi dengan layanan pembayaran online.

Jadi, aplikasi kas RT yang menggunakan JSON dan API memungkinkan untuk pertukaran data yang efisien antara aplikasi klien dan server, serta memungkinkan integrasi dengan layanan eksternal untuk meningkatkan fungsionalitas dan efisiensi aplikasi.

**Tampilan :**
- Foto warga
- Nama pertama
- Nama Belakang
- Email
- Alamat rumah
- Jumlah iuran bulanan warga
- Total iuran individu warga
- Total iuran warga pada akhir rekap iuran Bulanan
- Pengeluaran iuran dari hasil iuran warga
- Pemanfaatan dari iuran warga untuk apa saja

**Langkah-langkah Praktikum :**

- Registrasi dan Dapatkan API Key: Daftar dan peroleh API key dari ApiSpreadsheets.
- Identifikasi Spreadsheet: Tentukan ID spreadsheet yang berisi data keuangan KAS RT yang akan diakses oleh aplikasi Anda.
- Buat Proyek Android: Buat proyek baru dalam lingkungan pengembangan Android Studio.
- Desain Antarmuka Pengguna: Rencanakan dan buat desain antarmuka pengguna (UI) yang sesuai dengan rincian yang diberikan.
- Koneksi ke API: Buat logika koneksi ke API menggunakan Retrofit atau pustaka HTTP klien lainnya dalam aplikasi Android Anda.
- Parsing Data JSON: Implementasikan logika parsing JSON untuk mengambil data dari respons API.
- Tampilkan Data: Tampilkan data yang diperoleh dari API ke dalam antarmuka pengguna aplikasi Android sesuai dengan rincian yang diminta.
- Uji Aplikasi: Lakukan pengujian menyeluruh terhadap aplikasi Anda untuk memastikan bahwa semua fitur berjalan dengan baik dan data ditampilkan dengan benar.

  Build Gradle
```
dependencies {

    implementation("androidx.core:core-ktx:1.9.0")
    implementation("androidx.appcompat:appcompat:1.6.1")
    implementation("com.google.android.material:material:1.11.0")
    implementation("androidx.constraintlayout:constraintlayout:2.1.4")
    testImplementation("junit:junit:4.13.2")
    androidTestImplementation("androidx.test.ext:junit:1.1.5")
    androidTestImplementation("androidx.test.espresso:espresso-core:3.5.1")

    implementation("androidx.recyclerview:recyclerview:1.3.2")
    implementation("com.github.bumptech.glide:glide:4.11.0")
    implementation("com.loopj.android:android-async-http:1.4.9")

    implementation("com.google.code.gson:gson:2.8.9")

    implementation("com.squareup.retrofit2:retrofit:2.6.4")
    implementation("com.squareup.retrofit2:converter-gson:2.6.4")

    implementation("com.squareup.okhttp3:logging-interceptor:3.8.0")
    debugImplementation("com.github.chuckerteam.chucker:library:3.3.0")
}

```

Dokumentasi :
1. YouTube : 
2. Pdf : 
