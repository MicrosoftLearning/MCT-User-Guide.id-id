# Panduan Pengguna GitHub untuk MCTs

Layanan cloud, seperti Microsoft Azure, sering diperbarui yang menyebabkan tantangan bagi Microsoft Certified Trainers (MCTs) saat mereka mengajar kursus dan langkah-langkah lab tidak lagi cocok dengan layanan cloud kami. . Karena frekuensi perubahan dan fakta bahwa mungkin tidak ada pemberitahuan ketika perubahan terjadi, mungkin sulit bagi tim pengembangan kursus untuk dengan cepat mengidentifikasi dan menyesuaikan perubahan lab.

Untuk mengatasi masalah ini, kami menggunakan GitHub untuk menerbitkan langkah-langkah lab dan skrip lab untuk kursus yang mencakup layanan cloud seperti Azure. Menggunakan GitHub memungkinkan penulis kursus dan MCTs untuk menjaga konten lab tetap terkini dengan perubahan layanan cloud. Menggunakan GitHub memungkinkan MCT untuk memberikan umpan balik dan saran untuk perubahan lab, dan kemudian penulis kursus dapat segera memperbarui langkah dan skrip lab.

Ketika Anda bersiap untuk mengajar kursus ini, Anda harus memastikan bahwa Anda menggunakan langkah-langkah dan skrip lab terbaru dengan mengunduh file yang sesuai dari GitHub.

Panduan pengguna ini adalah untuk MCT yang baru menggunakan GitHub. Ini menyediakan langkah-langkah untuk menyambungkan ke GitHub, mengunduh dan mencetak materi kursus, memperbarui skrip yang digunakan siswa di laboratorium, dan menjelaskan bagaimana Anda dapat membantu memastikan bahwa konten kursus tetap terkini.

> **Catatan**: Dukungan Microsoft Pembelajaran untuk mengakses file di GitHub dan dukungan untuk navigasi situs GitHub terbatas pada MCTs yang hanya mengajar kursus ini.

GitHub tidak boleh digunakan untuk membahas konten teknis dalam kursus, atau cara mempersiapkan kursus atau laboratoriumnya. Ini khusus untuk mengatasi perubahan di laboratorium.

 
> **Catatan**: Untuk mengatasi komentar umum tentang kursus dan demo, atau cara mempersiapkan kursus, silakan gunakan forum MCT.

## Bagian

- [Terminologi GitHub](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [Menerima pemberitahuan pembaruan dan berkolaborasi pada proyek](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- Menyarankan perubahan atau mengirimkan masalah ke instruksi lab

## Terminologi GitHub

GitHub memperkenalkan terminologi yang mungkin baru untuk Anda. Daftar berikut ini mencakup istilah dan konsep yang digunakan di seluruh dokumen ini. Namun, untuk daftar lengkap istilah GitHub, lihat [Glosarium](https://docs.github.com/en/get-started/quickstart/github-glossary) GitHub.

| Term| Penjelasan |
| - | - |
| Git dan GitHub| Git adalah program sumber terbuka, pelacakan perubahan, dan GitHub adalah situs/solusi yang dibangun di Git. Ada situs web dan solusi lain yang menggunakan Git sebagai backend mereka. Anda akan menggunakan GitHub terutama untuk proyek pengembangan sumber terbuka (publik), dan gratis untuk proyek-proyek tersebut. Namun, jika Anda ingin menggunakan GitHub untuk proyek yang bersifat privat dan tidak sumber terbuka, Anda harus mendaftar untuk versi berbayar. |
| Repositori atau Repositori| Setiap proyek di GitHub berada di repositori, atau repositori. Repositori berisi semua file untuk proyek, termasuk dokumentasi, dan mendukung riwayat revisi. Repositori dapat bersifat publik atau privat. Anda dapat memiliki salinan lokal repositori di hard drive komputer Anda, atau Anda dapat menggunakan repositori dalam GitHub. |
| Markdown| Ini adalah format file teks yang dapat digunakan untuk membuat dokumentasi. Ini berbasis teks dan sangat sederhana untuk diperbarui, yang membuatnya mudah digunakan selama kolaborasi. GitHub kemudian merendernya sebagai HTML. |
| Markdown rasa GitHub (GFM)| Ada banyak variasi, atau ragam, dari format file Markdown. Versi GitHub, umumnya disebut sebagai GFM, adalah salah satu variasi Markdown yang paling umum. Untuk informasi selengkapnya tentang GFM dan bagaimana Anda dapat menggunakan format Markup untuk dokumen GFM Anda, lihat "Mulai menulis dan memformat di GitHub" di https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. |
| Fork| Ini adalah salinan repositori lain yang berada di akun GitHub Anda, dibandingkan dengan cabang, yang tinggal di repositori asli. Lihat "Cabang" langsung di bawah ini. |
| Cabang| Ini adalah salinan repositori yang berada di repositori yang sama dengan aslinya. Anda dapat menggabungkan cabang dengan yang asli. |
| Ambil| Ini adalah proses pengambilan salinan perubahan terbaru dari repositori online. Namun, pengambilan tidak menggabungkan perubahan. |
| Penarikan| Ini adalah proses mengambil perubahan terbaru dari repositori online dan menggabungkannya dengan perubahan lokal. |
| Penggabungan| Ini adalah proses pengambilan perubahan dari satu cabang dan menerapkannya ke cabang lain. Ini termasuk mengambil perubahan dari repositori online, lalu menerapkannya ke versi lokal repositori tersebut. |
| Permintaan penarikan| Ini adalah serangkaian perubahan yang diusulkan pada repositori yang dikirimkan pengguna, dan pemilik atau kolaborator repositori kemudian dapat menerima atau menolak permintaan pull. |
| Push| Ini adalah proses pengiriman atau pengiriman perubahan lokal Anda ke repositori online. |
| Rekan kerja| Ini adalah pengguna GitHub yang memiliki izin untuk menambahkan, menghapus, atau mengubah konten repositori. |

## Menerima pemberitahuan pembaruan, menyarankan perubahan, dan berkolaborasi pada proyek

Anda dapat mengonfigurasi pengalaman GitHub sehingga Anda menerima pemberitahuan saat pembaruan terjadi pada repositori GitHub. Ada beberapa cara di mana Anda dapat mendaftar untuk pemberitahuan, dan banyak dari mereka berkaitan dengan banyak cara Anda dapat berkolaborasi pada proyek. Untuk menerima pemberitahuan, Anda dapat melakukan tindakan berikut.

| Tindakan| Deskripsi |
| - | - |
| [Tonton repositori](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| Saat Anda menonton repositori, GitHub secara otomatis berlangganan Anda ke pemberitahuan untuk permintaan pull atau masalah baru yang dibuat untuk repositori tertentu tersebut. Anda secara otomatis menonton repositori apa pun yang Anda buat atau di mana Anda adalah kolaborator. |
| [Permintaan penarikan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Saat Anda membuat permintaan pull dan mengusulkan agar pemilik repositori menerima perubahan yang Anda buat, Anda secara otomatis berlangganan untuk menerima pemberitahuan untuk diskusi terkait tentang permintaan pull. Untuk membuat permintaan Pull, Anda harus terlebih dahulu membuat cabang. |
| [Komentar](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Ketika Anda membuat komentar tentang permintaan pull orang lain, GitHub berlangganan Anda secara otomatis ke forum yang berkaitan dengan komentar tersebut, atau Anda dapat berlangganan forum secara manual. |
| [Terbitan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Masalah adalah saran, pertanyaan, atau permintaan yang berkaitan dengan repositori. Setiap masalah memiliki diskusinya sendiri, dan Anda dapat berlangganan masalah, atau GitHub secara otomatis berlangganan Anda untuk masalah yang Anda buat. |
| [Menyebutkan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| Ketika pengguna lain menyebut Anda dalam percakapan, menggunakan nama pengguna GitHub Anda ([@username](https://github.com/username)), GitHub secara otomatis berlangganan Anda ke diskusi. |

> **Catatan**: Anda dapat memodifikasi bagaimana dan kapan Anda menerima pemberitahuan, dan Anda juga dapat berhenti berlangganan ke salah satu atau semua diskusi.

## Mengirimkan Masalah atau menyarankan perubahan pada instruksi lab

Jika Anda memiliki saran atau mengalami kesalahan di lab, Anda dapat mengirimkan permintaan pull dan mencatat masalah. Jika Anda sudah mengetahui perbaikan untuk kesalahan tersebut, kami sarankan Anda mengirimkan permintaan pull; jika tidak, kirimkan masalah.

| Tindakan| Deskripsi |
| - | - |
| [Permintaan penarikan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Saat Anda membuat permintaan pull dan mengusulkan pemilik repositori menerima perubahan yang Anda buat, Anda secara otomatis berlangganan untuk menerima pemberitahuan untuk diskusi terkait tentang permintaan pull. Untuk membuat permintaan Pull, Anda harus terlebih dahulu membuat cabang. |
| [Komentar](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Ketika Anda membuat komentar tentang permintaan pull orang lain, GitHub secara otomatis berlangganan Anda ke forum yang berkaitan dengan komentar tersebut, atau Anda dapat berlangganan forum secara manual. |
| [Terbitan](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Masalah adalah saran, pertanyaan, atau permintaan yang berkaitan dengan repositori. Setiap masalah memiliki diskusi sendiri. Anda dapat berlangganan masalah, atau GitHub secara otomatis berlangganan Anda untuk masalah yang Anda buat. |
