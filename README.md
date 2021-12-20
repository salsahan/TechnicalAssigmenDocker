1.Jelaskan apa yang dimaksud dengan container pada docker !
Container pada docker adalah Wadah untuk mengemas dan menjalankan aplikasi. Wadah ini mencakup kode, runtime, system tools, dan pengaturan

2.Jelaskan apa perbedaan antara konsep container dengan virtual machine !
Container memberikan abstraksi pada bagian aplikasi saja dan berjalan pada satu os dasar yang sama sedangkan virtual machine mengabstraksi bagian physical hardware, jadi setiap vm akan menyertakan salinan lengkap sistem operasi, aplikasi, binari, dan library yang diperlukan sedangkan container hanya akan menyertakan aplikasi beserta library yang diperlukan saja.

3.Apa yang dimaksud dengan docker file ?
Dockerfile adalah file teks yang berisi semua perintah yang bisa dijalankan user pada baris perintah untuk membuat image. Ini mencakup semua instruksi yang diperlukan oleh docker untuk membangun image.

4.Apa yang dimaksud dengan docker registery ?
Docker registery adalah wadah atau tempat untuk menyimpan sebuah Docker image. Yang mana akan memberikan output sesuai dengan perintah yang diberikan.  

5.Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung !
Dengan cara membuat setup di satu file docker-compose.yml yang nantinya akan mengelompokkan container yang berbeda menjadi satu container sehingga dapat terhubung dan dijalankan secara bersamaan
