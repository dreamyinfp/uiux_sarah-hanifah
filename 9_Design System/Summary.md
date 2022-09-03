(9) Design System

Pengertian Design System

- Design System adalah sebuah standarisasi yang mengatur setiap elemen desain untuk mengurangi redudansi
- Design System adalah kumpulan prinsip dan praktik bersama yang membantu menginformasikan pekerjaan designer, product manager, dan developer, serta sales dan marketing

Pentingnya Design System
Masalah yang berusaha dipecahkan menjadi lebih jelas saat mendapatkan pemahaman yang lebih baik tentang user base. Saat pemahaman tim tumbuh, ide dan solusi terbentuk. Setiap anggota tim memiliki bagian yang dimainkan untuk menyusun produk pengalaman pengguna (user experience).

Designer

- Memiliki file design, namun tidak bisa diakses dengan mudah oleh Front-end Developer dan Product Manager
- Screenshot dan artboard di share back and forth dan ada perubahan konstan
- Ketiadaan guideline, membuat mereka mempertahankan pilihan dan solusi yang sama secara terus menerus

Front-End Developer

- Banyak menghabiskan waktu men-develop kodingan yang sama, namun dengan konteks berbeda
- Tidak mendapatkan akses file design, sehingga tidak dapat insight mengapa dan bagaimana keputusan design dibuat
- Akhirnya tersadar akan ketidakkonsistenan dalam teks, warna, dan spacing di beberapa mockup mereka. Alhasil code nya jadi berantakan

Product Manager

- Dapat banyak tekanan dari User dan Stackholder dikarenakan panjangnya road map produk serta resource yang sedikit
- Merasa kurang pada resource designer dan developer karena harus meng-handle semua pekerjaannya
- Banyak masalah minor yang ingin mereka solve sendiri, namun tidak mau melangkahi anggota tim lainnya

Perbedaan Style Guide / UI Kit, Component Library, dan Design System

- Style Guide / UI Kit (dokumentasi yang masih bersifat statis. Masih menyingkup color, typography, iconography, dsb)
- Component Library (dokumentasi komponen style dan komponen yang bisa digunakan dan dibagikan ke tim. Bisa juga memasukkan dokumentasi koding dari setiap komponen seperti: button, text field, checkbox, dsb)
- Design System (dokumentasi kumpulan element, component, dan regions yang sudah ditentukan, termasuk guideline dari Designer dan Front-End Developer seperti: kapan button ini digunakan, kenapa pakai warna ini, serta berbagai macam alasan disetiap pemakaian komponen lainnya)

3 Poin Penting Design System

1. Umur dari Perusahaan (karena setiap tahun perusahaan selalu berkembang, otomatis kebutuhan mereka juga bertambah)
2. Ukuran Tim (jika dirasa resource tim akan berkembang kedepannya, maka pertimbangan pemakaian Design System perlu dipikirkan)
3. Beban Pekerjaan (Kerja sebagai UI/UX Designer seringkali bergantian antara brand yang di desain dengan kebutuhan user. Dikarenakan tidak adanya iterasi, UI/UX Designer tidak terlalu melihat adanya kesempatan untuk mengembangkan user experience. Namun Design System bisa digunakan sebagai starting point untuk membuat brand)

3 Tujuan Design System

- Brand Bisa Konsisten
- Menjadi Company Identity
- Mempunyai Nilai yang Sama Antar Pegawai

Cara Membangun Design System
A. Atomic Methodology (merupakan metodologi perancangan yang mengambil inspirasi dari bagaimana sebuah elemen atom membentuk molekul yang lebih kompleks hingga membentuk suatu organisme, dan ini analogikan ke setiap interface halaman situs atau aplikasi)

- Elemen dalam Atomic Design (metode ini designer dituntut mendesain dari komponen terkecil. Uniknya, nama komponennya diambil dari istilah-istilah kimia)

1. Atom (komponen terkecil adalah "atom". Bentuknya berupa tombol, input, label, dll. Salah satu contohnya adalah tombol search)
2. Molekul (merupakan beberapa atom dikumpulkan. Misalnya, menggabungkan atom tombol search dan input search. Semua itu akan membentuk fitur pencarian yang utuh)
3. Organisme (merupakan kumpulan dari molekul. Misalnya, molekul fitur search bar yang ditempel di header. Kemudian ada tombol navigasi dan logo, inilah yang membentuk suatu organisme)
4. Template (merupakan gabungan dari beberapa organisme. Ia merupakan “blueprint” dari sebuah halaman web. Blueprint ini tentu bisa dimodifikasi. Ia sangat mirip dengan wireframe, ditampilkan berupa elemen dan belum punya data nyata)
5. Page/Halaman (merupakan produk akhir dari desain atomis. Ia adalah template yang diisi dengan data nyata)

B. Best Practice to Build a Design System
3 Langkah Membangun Desain Sistem

1. Evaluasi inventaris UI saat ini dan catat inkonsistensi pada desain yang dibuat
2. Bangun sebuah pattern library dari berbagai elemen desain yang sama
3. Dokumentasikan aturan desain, lalu atur juga bagaimana dan kapan elemen-elemen desain itu dapat digunakan
