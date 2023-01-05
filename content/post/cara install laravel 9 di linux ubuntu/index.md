---
title: "Cara Install Laravel 9 Di Linux Ubuntu"
date: 2023-01-05T21:35:43+07:00
draft: false
comments: true
readingTime: true
image: img/laravel-9.jpg
keywords: ["laravel", "laravel 9", "linux", "ubuntu"] 
tags: ["laravel", "ubuntu"]
categories: ["tutorial"]
---

# Apa itu laravel?
Laravel adalah framework PHP yang dirancang untuk membuat aplikasi web dengan cepat. Laravel menyediakan berbagai fitur yang memudahkan developer untuk membuat aplikasi web dengan cepat, seperti routing, authentication, database migration, dan sebagainya. Laravel juga menggunakan bahasa pemrograman PHP modern yang membuatnya mudah dipelajari bagi developer yang sudah terbiasa dengan PHP. Jadi, Laravel adalah salah satu pilihan populer bagi developer yang ingin membuat aplikasi web dengan cepat dan mudah.
# Cara install
## Persiapan
pastikan anda memiliki php dan dependensi yang dibutuhkan laravel pada komputer anda, jika belum anda bisa menginstallnya dengan cara membuka terminal lalu menjalankan perintah berikut ini

```bash

 sudo apt update
 sudo apt-get install php php-common php-mbstring php-xml php-zip

```

untuk mengecek versi php kamu dapat menjalankan command ini 

```bash

 php --version

```

begitu pula dengan composer, kamu dapat menginstallnya dengan menggunakan perintah

```bash

 sudo apt-get install composer

```

## instalasi

jalankan perintah berikut untuk melakukan instalasi laravel

```bash
 
 composer global require laravel/installer

```

### tags: 