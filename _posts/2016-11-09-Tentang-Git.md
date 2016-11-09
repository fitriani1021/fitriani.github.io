---
published: true
layout: post
title: Tentang Git
---

Hello, all! Kali ini saya akan membahas mengenai apa itu git secara singkat.

Git adalah <!--more--> tools yang berfungsi sebagai Version Control System (VCS) dan kalau diartikan ke bahasa kita artinya sebuah sistem pelacak perubahan pada file. Git sendiri dibuat oleh orang yang menciptakan Kernel Linux, yup.. dia adalah yang mulia Linus Torvalds.

Untuk menggunakan git, pertama kita harus membuat akun untuk repository di salah satu Source Code Hosting untuk git. Nah, untuk hal ini saya menggunakan Github [www.github.com]. Dan untuk mengoperasikannya, kita bisa mengoperasikannya atau mengaturnya langsung di git via web (dalam hal ini adalah Github), menggunakan git command (CMD), ataupun menggunakan software git yang berbasis GUI, seperti SourceTree.

Nah, dari ketiga versi git diatas, seluruhnya bekerja saling bantu-membantu dan sangat berkaitan. bahkan software git yang berbasis GUI pun menyertakan terminal (basis CMD) juga. Untuk yang basis CMD atau command prompt, meskipun cukup ribet dan melelahkan jari (karena harus always mengetik), git command inilah yang paling penting untuk dipelajari, sebagai pengguna git (dalam hal ini, Github), kita harus mengetahui dan terus mempelajari git command ini lebih dari git GUI ataupun git web. Karena semua kunci pengoperasian git ada di git command ini.

Untuk github sendiri, kita bisa membuat website statis dengan repository yang telah kita buat. Kita juga bisa berkontribusi ke repository pengguna lain. Kontribusi ini dapat berarti perbaikan bug (bisa berbentuk typo atau syntax error). Di Github, kita akan mengenal istilah-istilah seperti Pull Request, Commit, Merge, dan lain-lain. Saya hanya akan membahas mengenai Pull Request dan Commit kali ini.

Pull Request (disingkat PR) adalah suatu fungsi untuk mengajukan perubahan (kontribusi) yang kita lakukan pada repository lain dengan tujuan di-merge (diaplikasikan) ke repository tersebut. Sedangkan commit bisa kita artikan sebagai sebuah perubahan yang kita lakukan terhadap suatu file dalam repository tersebut. Perubahan yang kita lakukan pada PR yang kita buat pun disebut Commit.

Nah, dalam hal ini saya punya sebuah cerita. Jadi saya membuat PR ke sebuat repository yang belum memasang file LICENSE. Sebenarnya tidak apa-apa karena mereka sudah menyertakan keterangan mengenai lisensi tersebut di file lain. Saya pun menambahkan PR ke repository tersebut. Tetapi, commit message saya salah. Ketika itu saya nggak tau tentang git command dan git GUI, saya hanya mengandalkan Github sebagai alat untuk berkontribusi. Yang saya lakukan saay itu hanya mengedit sedikit PR saya tersebut kemudian mengganti commit message dengan yang baru. Saya melakukannya dua kali sehingga jumlah commit dalam PR saya jadi 3 buah. Saya mendapat teguran dari mentor saya karena multi commits dengan hanya sedikit perubahan itu terkesan sangat tidak rapi dan nggak penting.

Makanya, untuk meminimalisir terjadinya multi commits seperti yang saya lakukan diatas, sangat penting untuk mempelajari git command jadi kita bisa mengaturnya melalui terminal tersebut. Dan jika terlanjur melakukan kesalahan seperti itu, kita bisa memperbaiki (amend) hal itu dengan cara menggabungkan multi commits tersebut menjadi satu (rebase)

Nah, sekian dari saya malam ini, maaf jika ada kata-kata yang kurang jelas atau kurang berkenan. Akan saya update lagi jika saya menemukan hal-hal baru mengenai git ini. Blog post tentang git ini hanyalah apa yang saya pahami. Untuk kalimat terakhir, saya ingin menyampaikan, kalau ingin berkontribusi ke sebuah repository git, buatlah commit yang berkelas, dalam artian commit tersebut tidak memiliki arti ganda, simple, dan jelas fungsi dan efek baiknya pada repository tersebut. Hindari membuat membuat commit beberapa kali hanya untuk masalah yang sama dan hindari membuat commit yang tidak berarti. Agar kesalahan saya membuat multi commits tersebut tidak terulang untuk kedepannya.
Sekian, selamat malam! ^^
