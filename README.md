# flutter_plugin_pubdev

#22 | Pengenalan Plugin di Pub.Dev

## Langkah 2: Menambahkan Plugin

Tambahkan plugin `auto_size_text` menggunakan perintah berikut di terminal
![langkah 2](images/2.jpg)

## Langkah 3: Buat file red_text_widget.dart

Buat file baru bernama `red_text_widget.dart` di dalam folder lib<br>
<img src="images/3.jpg" width="700">

## Langkah 4: Tambah Widget AutoSizeText

Ubahlah kode `return Container()` menjadi seperti berikut<br>
<img src="images/4.jpg" width="700"><br>
Terdapat error pada baris ke-8 karena method `AutoSizeText` tidak terdefinisi dan cara memperbaikinya yaitu dengan menambahkan `import 'package:auto_size_text/auto_size_text.dart';`. Lalu pada baris ke-9 error karena variabel `text` tidak terdefinisi dan akan diperbaiki pada langkah ke 5.

## Langkah 5: Buat Variabel text dan parameter di constructor

Tambahkan variabel text dan parameter di constructor seperti berikut<br>
<img src="images/5.jpg" width="700"><br>

## Langkah 6: Tambahkan widget di main.dart

Buka file `main.dart` lalu tambahkan di dalam `children:` pada class `_MyHomePageState`<br>
<img src="images/7.jpg" width="800"><br>

## Output

![output](images/6.jpg)
