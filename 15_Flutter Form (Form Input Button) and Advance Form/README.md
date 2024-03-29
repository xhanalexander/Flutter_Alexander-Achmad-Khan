# (15) Flutter Form (Form Input Button) and Advance Form

## Summaries

### Flutter Forms

Dalam setiap aplikasi pentingnya ada sebuah interaksi antara user, maka ada sebuah widget yaitu `Form` yang bisa user berinteraksi seperti mengisi sebuah formulir dalam aplikasi kita untuk sebuah feedback atau fungsionalitas lainnya. Flutter menyediakan berbagai widget untuk class form seperti `TextFormField` yang Widget ini sangat berguna untuk memungkinkan pengguna untuk memasukkan teks atau data dalam bentuk formulir. Selain TextFormField, terdapat pula beberapa widget lain yang sering digunakan dalam pembuatan form di Flutter, seperti `TextField`, `Checkbox`, `Radio`, `DropdownButton`, dan `Switch`. Masing-masing widget tersebut memiliki fungsi dan kegunaan yang berbeda-beda.

Dalam penggunaannya, TextFormField dapat diatur untuk menampilkan placeholder, validasi input menggunakan `validator` dalam method-nya yang harus mempeljari regex untuk validasi form-nya, dan berbagai properti lainnya yang berguna untuk mengontrol interaksi pengguna dengan form. Selain itu, pengembang juga dapat menambahkan fungsi atau event handler pada widget ini untuk mengatur tindakan yang dilakukan ketika pengguna mengisi form. Penggunaan widget form pada aplikasi sangat penting untuk mempermudah pengguna dalam memberikan feedback atau input data pada aplikasi. Dengan adanya form, pengguna dapat dengan mudah memasukkan data secara sistematis dan terstruktur, sehingga memudahkan aplikasi dalam memproses dan mengelola data yang diterima dari pengguna.

### Flutter Advanced Forms

Form pada umum-nya hanya bisa handle beberapa input seperti `TextField`, `Checkbox`, `Radio`, `DropdownButton`, dan `Switch`. Namun ada beberapa library yang bisa lebih advanced dalam menginput Form, salah satunya sepert __Date Picker__, __Color Picker__, dan __File Picker__. 

Untuk widget date picker ini user memungkinkan membuat aplikasi untuk input fungsi seperti tanggal kelahiran, waktu pemesanan pada tiket (_Penerbanngan, hotel check in, meeting_), dan waktu reservasi tempat restoran. 

Kemudian juga ada widget Color Picker, yang memungkinkan user bebas memilih kostum warna pada aplikasi yang ingin diinput, untuk Library-nya juga sudah disediakan dalam pub [package](https://pub.dev/packages/flutter_colorpicker) dokumentasinya sudah juga tersedia, yang bisa memilih berbagai kostum.

Dan juga tersedia Widget File Picker, yang memungkinkan user ingin menginput file ke aplikasi kita. Hanya cukup membutuhkan library [File Picker](https://pub.dev/packages/file_picker) dan [Open File](https://pub.dev/packages/open_file).


### Form Validation

Form pada umumnya memiliki sebuah validasi yang Fitur ini memungkinkan pengembang untuk menentukan aturan validasi untuk memastikan bahwa data yang dimasukkan ke dalam formulir memenuhi kriteria tertentu. Dengan validasi formulir, pengembang dapat memastikan bahwa data yang dikirim ke server atau penyimpanan pada lokal akan valid dan aman digunakan, sehingga mencegah kesalahan atau kerusakan data. Fitur ini juga memudahkan pengisian formulir dengan memberikan pesan kesalahan yang jelas dan akurat untuk informasi yang salah, meminimalkan kemungkinan kesalahan input.

____

#### Task Documentation Issues

Beberapa kendala mengenai di task eksplorasi di soal Advanced Forms di file _contentPicker.dart_, yaitu menyimpan variable controller untuk warna dan file  dengan menggunakan TextFormFields, namun bisa untuk menyimpan controller untuk __DatePicker__, mungkin untuk kedepannya ada solusinya dari soal ini namun sudah diusahakan semaksimalnya.