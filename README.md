# Komponen-Dasar
## Penjelasan Komponen Dasar pada Activity Android

### Activity <br>
Merupakan satu komponen yang berhubungan dengan pengguna. Activity menangani window (tampilan) mana yang akan di tampilkan ke dalam interface (antarmuka). Activity memiliki daur hidup (life cycle) tersendiri yang dimulai dari onCreate hingga onDestroy. <br>

### Intent <br>
Komunikasi antar komponen di dalam sebuah aplikasi merupakan hal yang sangat sering dilakukan. Inilah peran dari suatu intent. Beberapa fungsi dari intent adalah dapat digunakan untuk menjalankan sebuah activity, mengirimkan pesan ke broadcast receiver, dan dapat juga digunakan untuk berkomunikasi dengan service yang sedang berjalan. <br>

### Views and ViewGroup 
Pada dasarnya semua elemen antar pengguna di aplikasi Android dibangun menggunakan dua buah komponen inti, yaitu view dan viewgroup. Sebuah view adalah obyek yang menggambar komponen tampilan ke layar yang mana pengguna dapat melihat dan berinteraksi langsung. <br>
Contoh komponen turunan dari view seperti : <br>

o	**TextView**, komponen yang berguna untuk menampilkan teks ke layar. <br>
o	**Button**, komponen yang membuat pengguna dapat berinteraksi dengan cara ditekan untuk melakukan sesuatu. <br>
o	**ImageView**, Komponen untuk menampilkan gambar. <br>
o	**ListView**, komponen untuk menampilkan informasi dalam bentuk list. <br>
o	**GridView**, komponen untuk menampilkan informasi dalam bentuk grid. <br>
o	**RadioButton**, komponen yang memungkinkan pengguna dapat memilih satu pilihan dari berbagai pilihan yang disediakan. <br>
o	**Checkbox**, komponen yang memungkinkan pengguna dapat memilih lebih dari satu dari pilihan yang ada. <br>

### Style and Theme
Prinsip dasar dalam merancang antarmuka aplikasi Android harus mematuhi kaidah yang ditetapkan oleh Design Guideline. Guideline ini dibuat oleh tim Android di Google. Beberapa prinsipnya adalah: <br>
o	Menampilkan informasi yang hanya dibutuhkan. <br>
o	Jika aplikasi meminta izin pengguna untuk melakukan sebuah aksi, maka pengembang harus menyediakan mekanisme untuk membatalkan izin tersebut. <br>
o	Lakukan interupsi jika diperlukan. <br>
o	Menggunakan teks secara singkat. Gunakan gambar untuk menjelaskan informasi secara lebih deskriptif. <br>
o	Jaga data pengguna. <br>
o	Permudah pengguna untuk melakukan sesuatu yang penting secara cepat. <br>
o	Jika terlihat sama, maka perilaku haruslah sama. <br>
o	Bantu pengguna untuk membuat keputusan tapi tetap biarkan pengguna menentukan keputusannya. <br>

### RecyclerView
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime). <br>
o	**RecyclerView dan LayoutManager**: Komponen antarmuka yang bertugas untuk menampilkan data set yang dimiliki di dalamnya. Layoutmanager akan mengatur posisi tampilan data baik itu secara list (vertikal), grid (baris dan kolom) atau staggered grid (grid yang memiliki susunan tak seragam / tak beraturan). <br>
o	**Adapter**: Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. Di sinilah terjadi proses pengisian tampilan (ViewInflate) dari file layout xml untuk tiap elemen dari data yang sebelumnya terpasang (bind) ke dalam RecyclerView. <br>
o	**Dataset**: Kumpulan data yang dimiliki dan ingin ditampilkan. Bisa berupa array, list maupun obyek map. <br>
o	**Item Animator**: Ini yang spesial. Kita bisa pasang animasi untuk tiap item di dalamnya. Contoh animasi yang umum seperti penambahan (add) dan penghapusan (removal) item. Kita akan mempelajari hal ini pada materi terpisah. <br>





