# Panduan Pengguna GitHub untuk MCTs

Layanan cloud, seperti Microsoft Azure, sering diperbarui sehingga menimbulkan tantangan bagi Pelatih Bersertifikat Microsoft (MCT) karena mereka mengajarkan kursus dan langkah lab yang tidak lagi sesuai dengan layanan cloud kami. . Karena frekuensi perubahan dan fakta bahwa mungkin tidak ada pemberitahuan ketika perubahan terjadi, mungkin sulit bagi tim pengembangan kursus untuk mengidentifikasi dan menyesuaikan perubahan lab dengan cepat.

Untuk mengatasi masalah ini, kami menggunakan GitHub untuk mempublikasikan langkah-langkah lab dan skrip lab untuk kursus yang mencakup layanan cloud seperti Azure. Penggunaan GitHub memungkinkan penulis kursus dan MCT untuk menjaga konten lab tetap terbaru dengan perubahan layanan cloud. Penggunaan GitHub memungkinkan MCT memberikan umpan balik dan saran untuk perubahan lab. Kemudian, penulis kursus dapat segera memperbarui skrip dan langkah-langkah lab dengan segera.

Saat bersiap untuk mengajarkan kursus ini, Anda harus memastikan bahwa Anda menggunakan langkah-langkah dan skrip lab terbaru dengan mengunduh file yang sesuai dari GitHub.

Panduan pengguna ini ditujukan untuk MCT yang baru menggunakan GitHub. Panduan ini memberikan langkah-langkah untuk menyambungkan ke GitHub, mengunduh dan mencetak materi kursus, memperbarui skrip yang digunakan siswa di lab, dan menjelaskan bagaimana Anda dapat membantu memastikan bahwa konten kursus tetap terkini.

> **Catatan**: Dukungan Microsoft Learning untuk mengakses file di GitHub dan dukungan untuk navigasi situs GitHub terbatas pada MCT yang mengajarkan kursus ini saja.

GitHub tidak boleh digunakan untuk mendiskusikan konten teknis dalam kursus, atau cara mempersiapkan kursus atau lab-nya. Hal ini khusus untuk mengatasi perubahan di lab.

 
> **Catatan**: Untuk menjawab komentar umum tentang kursus dan demo, atau cara mempersiapkan kursus, gunakan forum MCT.

## Bagian

- [Terminologi GitHub](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [Menerima pemberitahuan pembaruan dan berkolaborasi pada proyek](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- Menyarankan perubahan atau mengirimkan masalah ke instruksi lab

## Terminologi GitHub

GitHub memperkenalkan terminologi yang mungkin adalah hal baru bagi Anda. Daftar berikut mencakup istilah dan konsep yang digunakan di seluruh dokumen ini. Namun, untuk daftar lengkap istilah GitHub, lihat [Glosarium GitHub](https://docs.github.com/en/get-started/quickstart/github-glossary).

| Term| Penjelasan |
| - | - |
| Git dan GitHub| Git adalah program pelacakan perubahan sumber terbuka, dan GitHub adalah situs/solusi yang dibangun di Git. Ada situs web dan solusi lain yang menggunakan Git sebagai backend-nya. Anda akan menggunakan GitHub terutama untuk proyek pengembangan sumber terbuka (publik) dan dapat digunakan secara gratis untuk proyek tersebut. Namun, jika Anda ingin menggunakan GitHub untuk proyek yang bersifat pribadi dan bukan sumber terbuka, Anda harus mendaftar untuk versi berbayar. |
| Repo atau Repositori| Setiap proyek di GitHub ada dalam repositori, atau repo. Repositori berisi semua file untuk proyek, termasuk dokumentasi. Repositori juga mendukung riwayat revisi. Repositori dapat bersifat publik atau privat. Anda dapat memiliki salinan repositori lokal di hard drive komputer, atau Anda dapat menggunakan repositori dalam GitHub. |
| Markdown| Hal ini adalah format file teks yang dapat digunakan untuk membuat dokumentasi. Repositori ini berbasis teks dan sangat mudah untuk diperbarui sehingga mudah digunakan selama kolaborasi. GitHub kemudian merendernya sebagai HTML. |
| GitHub flavored markdown (GFM)| Ada banyak variasi, atau ragam, format file Markdown. Versi GitHub, umumnya disebut GFM, adalah salah satu variasi Markdown yang paling umum. Untuk informasi selengkapnya tentang GFM dan bagaimana Anda dapat menggunakan format Markup untuk dokumen GFM Anda, lihat "Memulai menulis dan memformat di GitHub" di https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. |
| Fork| Ini adalah salinan repositori lain yang berada di akun GitHub Anda, dibandingkan dengan cabang, yang berada di repositori asli. Lihat "Cabang" langsung di bawah ini. |
| Cabang| Ini adalah salinan repositori yang berada di repositori yang sama dengan aslinya. Anda dapat menggabungkan cabang dengan yang asli. |
| Ambil| Ini adalah proses pengambilan salinan perubahan terbaru dari repositori online. Namun, pengambilan tidak menggabungkan perubahan. |
| Penarikan| Ini adalah proses mengambil perubahan terbaru dari repositori online dan menggabungkannya dengan perubahan lokal. |
| Penggabungan| Ini adalah proses mengambil perubahan dari satu cabang dan menerapkannya ke cabang lain. In termasuk mengambil perubahan dari repositori online, lalu menerapkannya ke versi lokal repositori tersebut. |
| Permintaan penarikan| Ini adalah serangkaian usulan perubahan pada repositori yang dikirimkan pengguna, dan pemilik atau kolaborator repositori kemudian dapat menerima atau menolak permintaan pull. |
| Push| Ini adalah proses mengirimkan atau menyerahkan perubahan lokal Anda ke repositori online. |
| Rekan kerja| Ini adalah pengguna GitHub yang memiliki izin untuk menambah, menghapus, atau mengubah konten repositori. |

## Menerima pemberitahuan pembaruan, menyarankan perubahan, dan berkolaborasi pada proyek

Anda dapat mengonfigurasi pengalaman GitHub sehingga Anda menerima pemberitahuan ketika pembaruan terjadi pada repositori GitHub. Terdapat beberapa cara untuk mendaftar untuk pemberitahuan, dan banyak di antaranya berkaitan dengan banyak cara Anda dapat berkolaborasi pada proyek. Untuk menerima pemberitahuan, Anda dapat melakukan tindakan berikut.

| Tindakan| Deskripsi |
| - | - |
| [Memantau repositori](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| Saat Anda memantau repositori, GitHub membuat Anda berlangganan secara otomatis ke pemberitahuan untuk masalah atau permintaan pull baru yang dibuat untuk repositori tertentu tersebut. Anda secara otomatis memantau repositori yang Anda buat atau repositori tempat Anda menjadi kolaborator. |
| [Permintaan pull](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Saat Anda membuat permintaan pull dan mengusulkan agar pemilik repositori menerima perubahan yang Anda buat, Anda secara otomatis berlangganan untuk menerima pemberitahuan untuk diskusi terkait tentang permintaan pull. Untuk membuat permintaan Pull, Anda harus terlebih dahulu membuat cabang. |
| [Komentar](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Saat Anda membuat komentar tentang permintaan pull orang lain, GitHub membuat Anda berlangganan secara otomatis ke forum yang berkaitan dengan komentar tersebut, atau Anda dapat berlangganan forum secara manual. |
| [Terbitan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Masalah di sini adalah saran, pertanyaan, atau permintaan yang berkaitan dengan repositori. Setiap masalah memiliki pembahasannya sendiri, dan Anda dapat berlangganan masalah tersebut, atau GitHub membuat Anda berlangganan secara otomatis ke masalah yang Anda buat. |
| [Sebutan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| Saat pengguna lain menyebut Anda dalam percakapan, menggunakan nama pengguna GitHub Anda ([@username](https://github.com/username)), GitHub secara otomatis membuat Anda berlangganan diskusi tersebut. |

> **Catatan**: Anda dapat mengubah cara dan waktu menerima pemberitahuan. Anda juga dapat berhenti berlangganan salah satu atau semua diskusi.

## Mengirimkan Masalah atau menyarankan perubahan pada instruksi lab

Jika memiliki saran atau mengalami kesalahan di lab, Anda dapat mengirimkan permintaan pull dan mencatat masalah. Jika sudah mengetahui perbaikan kesalahan tersebut, sebaiknya Anda mengirimkan permintaan pull. Jika tidak, kirimkan masalah.

| Tindakan| Deskripsi |
| - | - |
| [Permintaan pull](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Saat Anda membuat permintaan pul, dan mengusulkan pemilik repositori menerima perubahan yang Anda buat, Anda secara otomatis berlangganan untuk menerima pemberitahuan untuk diskusi terkait tentang permintaan pull. Untuk membuat permintaan Pull, Anda harus terlebih dahulu membuat cabang. |
| [Komentar](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Saat Anda membuat komentar tentang permintaan pull orang lain, GitHub membuat Anda secara otomatis berlangganan ke forum yang berkaitan dengan komentar tersebut, atau Anda dapat berlangganan forum secara manual. |
| [Terbitan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Masalah di sini adalah saran, pertanyaan, atau permintaan yang berkaitan dengan repositori. Setiap masalah memiliki diskusi sendiri. Anda dapat berlangganan masalah, atau GitHub secara otomatis membuat Anda berlangganan masalah yang Anda buat. |
