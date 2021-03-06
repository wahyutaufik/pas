pas - another package management and automation
===============================================

[![License](http://img.shields.io/npm/l/pas.svg?style=flat-square)](https://github.com/xinix-technology/pas/blob/master/LICENSE)
[![Download](http://img.shields.io/npm/dm/pas.svg?style=flat-square)](https://github.com/xinix-technology/pas)
[![NPM](http://img.shields.io/npm/v/pas.svg?style=flat-square)](https://github.com/xinix-technology/pas)

"pas" adalah sebuah Aplikasi package automation control. Tujuannya adalah untuk memberikan kemudahan kepada developer untuk mengatur siklus kerja dari aplikasi yang dibangunnya.

pas secara umum saat ini digunakan secara internal pada PT Sagara Xinix Solusitama untuk membantu dalam pengembangan piranti lunak dan sistem baik untuk bahasa pemrograman PHP maupun Javascript.

Dengan menggunakan pas, mempermudah pekerjaan seperti ini:

- Inisialisasi proyek dengan menggunakan archetype yang telah ada
- Inisialisasi proyek dengan menggunakan proyek lain sebagai archetype
- Satu perintah untuk mengatur ketergantungan pustaka baik itu PHP (composer) maupun Javascript (bower atau npm).
- Menjalankan server development secara internal.
- Mengatur script untuk melakukan migrasi antar versi

## Instalasi

pas di-install secara global untuk menambahkan perintah baru pada terminal / command-line anda. pas dibangun di atas teknologi node.js sehingga anda harus menginstall node.js terlebih dahulu hingga anda dapat menggunakan npm yang dibutuhkan untuk melakukan instalasi.

```bash
npm install -g pas
```

## Archetype

Archetype adalah sebuah konsep scaffolding dari template proyek. Hal ini dapat membantu anda untuk memulai sebuah proyek.

## Bagaimana cara melakukan sesuatu?

Kami menginginkan developer dapat untuk menggunakan pas secara intuitif seperti saat mereka menggunakan npm, bower, composer, dll.

### Inisialisasi proyek

Perintah inisialisasi sedikit berbeda dari npm, bower atau pun composer. Karena pas memiliki archetype untuk melakukan scaffolding pada proyek anda. Pada saat menjalankan perintah init, argumen ke-3 dari perintah ini adalah nama archetype yang ingin digunakan. Selain itu argumen ke-3 ini juga bisa berupa url dari git.

```bash
pas init $ARCHETYPE_URL [$DIRECTORY]
```

### Melakukan tugas tertentu

-- REMOVED FOR REVIEW LATER --

Perintah "task" akan menampilkan tugas-tugas yang ada yang bisa dilakukan dalam sebuah skup proyek tertentu. Untuk menambah tugas-tugas yang baru dapat dilakukan dengan menambah scripting pada file pasfile.js di direktori proyek anda.

-- /REMOVED FOR REVIEW LATER --

```bash
cd $PROJECT_DIR
pas task
```
