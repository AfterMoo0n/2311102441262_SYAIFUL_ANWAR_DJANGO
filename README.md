<<<<<<< Updated upstream
1
=======
Bagaimana cara menjadi pengembang Backend ?
    - Pemrograman back end ( Python , Ruby, Java, Go dll)
    - Pemahaman dasar -> menengah
    - Mempelajari penggunaan Git dan GitHub
    - Pengelolaan packet ( mengikuti bahasa yang digunakan)
    - Cara memasang dan menggunakan paket eksternal ke dalam projek
    - Pelajari beberapa basis data relasional ( PostgreSQL, Mysql)
    - Pelajari cara menjalankan operasi CRUD sederhana.
    - Pelajari penggunaan framework ( mengikuti bahasa yang digunakan)
    - Pelajari cara membangun API RESTful sederhana 
    - Pelajari penerapan Autentikasi/Otorisasi sederhana
    note' Gelar dalam ilmu komputer atau bidang terkait tidak selalu di perlukan, tetapi membangun network, membangun 
        portofolio, dan secara aktif mencari magang, posisi pengembang junior, atau konsultasi dapat memulai dan memajukan
        karir sebagai pengembang backend'
    note' ingatlah untuk membuat banyak proyek saat kamu belajar untuk memperkuat pemahaman kamu tentang konsep-konse. 
        selain itu, penting untuk memiliki sikap belajar terus-menerus untuk meningkatkan keterampilan kamu dan bersiap 
        menghadapi evolusi teknologi yang cepat dalam industri ini.
reverensi 'https://roadmap.sh/backend?authuser=0'

Apakah pengembang Frontend benar-benar coding?
    - Pemahaman mendalam (HTML, CSS, dan JavaScript)
    - Tingkatkan keterampilan melalui projek mini di platform seperti LeetCode, digunakan untuk membuat portofolio 
    pengembang web
    - Pelajari framework modern seperti React, Angular, atau Vue.js
    - Kuasai sistem , versi dari control systems, testing, dan build tools, yang penting untuk semua jenis pengembangan
    - memahami prinsip UI/UX , terkait aksebilitas , desain responsif, dan antarmuka intuitif
    - Meningkatkan ketermapilan komunikasi 
Reverensi 'https://roadmap.sh/frontend?authuser=0'

Progres 1 "Cara menggunakan Git dan Github"
    git adalah sebuah kontrol system, tetapi yang dimaksut adalah sistem for managging file .building software adalah
bagian fo small milestones dimana setiap mailstone adalah menulis code dan banyaknya file yang berbeda. file akan secara
constantly bergerak dari kekacauan besar error to stability dan dengan ini akan membantu untuk melacak semua perubahan 
dan memunkinkan untuk membuat beberapa branch atau jalur yang dapat di turunkan dan digabungkan nantinya yang 
memfasilitasi collaborate di antara kelompok developer yang lebih besar..
    - for visual studio code disarankan untuk menginstal GitLens ( mudahin untuk melihat direktori pada code, dan akan
    memberikan panel baru untuk memudahkan menavigate git history kamu).
    - hal penting ketika mengsetting a ithub repo adalah untuk membuat git ignore file supaya key sensitif seperti key
    API priavte. ( bisa di buat denagn touch .gitignore, add .gitignore atau b isa juga automatically dengan plugin 
    untuk environtmen)   
    - git add . untuk menambahkan mana file yang akan kita tambahkan sebelum mengcommit atau push, kamu juga bisa
    bisa membatalkannya dengan menggunakan git reset . ( hati hati dengan git reset --hard karna akan menghapus semua
    dan akan membuat mu mengulang dari awal ) 
    - make small commit untuk mencegah kesalahan coding yang kacau dan memudahkan untuk melihat log pada perubahan code 
    ketika kita mengdevelop
    - step by step commit
        - git add .
        - git commit -m "🚀 first commit
            > 
            > This is my first commit
            > make index.html
            > menambahkan gitignore
            > "
    - git branch , ketika ada kesalahan atau ingin mencoba sesuatu sebelum di publis pada aplikasi utama bisa 
        mengunakan cabang yang berbeda jadi bisa di gunakan banyak programer untuk 1 projek utama, yang nanti 
        keseluruhan cabang akan digabungkan pada cabang utama yaitu master
        - git branch ( untuk melihat sedang ada di branch apa, untuk melihat daftar branch)
        - git branch -v ( untuk meilhat log historu commit )
        - git checkout -b (nama branch) ( untuk membuat branch baru, dan switch ke branch yang sebelumnya belum ada)
        - git switch (nama branch) ( untuk berpindah ke branch yang sudah dimiliki)
        - git switch -c ( nama branch) ( untuk membuat brnch baru dan berpindah ke branch yan sebelumnya belum ada )
    - git push
        - git push --set-upstream origin master (perintah ini untuk set remote as upstream (berarti branch tidak 
            terhubung ke repositori jarak  jauh pada github karna biasanya branch tersebut di buat pada lokal) , Updated upstream
            bisa menggunakan push.autoSetupRemote in git help config supaya ga minta ini terus)

