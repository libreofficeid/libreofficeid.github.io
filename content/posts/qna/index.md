---
title: "Kelas Jaminan Kualitas (QA) LibreOffice ID"
date: 2019-12-06T22:46:31+07:00
image: assets/thumb.svg
author: LibreOffice ID
kategori: [kegiatan]
tags: [kontribusi, kualitas]
description: Panduan Ringkas untuk Menjadi Bagian dari Tim QA LibreOffice
---

### Apa itu QA?

QA adalah singkatan dari Quality Assurance atau Jaminan Kualitas. Tugas seorang QA adalah mengidentifikasi masalah dalam perangkat lunak (dalam hal ini LibreOffice), mengonfirmasi masalah yang dilaporkan oleh pengguna dan memvalidasi perbaikan dan peningkatan yang diusulkan sehingga setiap versi baru LibreOffice menjadi lebih baik dan maksimal dari versi-versi sebelumnya. Para pengembang dan komunitas melakukan QA dengan berbagai cara selama pengembangan rilis baru.

Tujuan utama dari QA sendiri adalah untuk menemukan atau mengonfirmasi bug yang paling mengganggun dan genting untuk kemudiad diserahkan kepada pengembang. Dengan kata lain, tim QA adalah jembatan antara pengguna dan pengembang dan mencoba untuk memandu setiap laporan bug ke solusi yang tepat. Beberapa tugas dari seorang QA misalnya adalah mencoba mereproduksi bug, menetukan prioritas tiap-tiap laporan, menemukan duplikat, memvalidasi perbaikan yang diusulkan, dan sebagainya.

### Panduan Ringkas untuk Pemula

Panduan ini dibuat seringkas mungkin agar para pemula tidak "kaget dan shock" sebelum mencoba. Berikut merupakan beberapa tahapan yang dapat dilakukan untuk memulai debut sebagai QA. 

-  [Unduh dan pasang](https://www.libreoffice.org/download/download/) LibreOffice stable terbaru (dari baris "Fresh")

-  [Unduh dan pasang](https://wiki.documentfoundation.org/QA/Testing_Daily_Builds) master build terbaru dari LibreOffice

-  [Buat akun di TDF](https://bugs.documentfoundation.org/createaccount.cgi) Bugzilla

-  [Buka daftar antrean bug](https://bugs.documentfoundation.org/buglist.cgi?bug_status=UNCONFIRMED&chfield=%5BBug%20creation%5D&chfieldfrom=-1M&chfieldto=Now&f1=bug_severity&f2=keywords&f3=component&list_id=1036324&n1=1&n2=1&n3=1&o1=substring&o2=anywords&o3=anywordssubstr&order=bug_id&product=Document%20Liberation%20Project&product=LibreOffice&query_format=advanced&resolution=---&v1=enhancement&v2=needsUXEval%2C%20needsDevAdvice&v3=Android%20iOS) bulan lalu yang belum dikonfirmasi (permintaan peningkatan sengaja diabaikan, beberapa hal lain juga difilter)

-  Pilih bug yang menarik

-  [Cari duplikat](https://wiki.documentfoundation.org/QA/BugTriage#Step_3:_Search_for_Duplicates)

-  Jika bug tersebut bukan duplikat, tetapi memiliki deskripsi yang membingungkan atau tidak memiliki sesuatu yang penting, [atur status ke NEEDINFO](https://wiki.documentfoundation.org/QA/GetInvolved#Try_to_reproduce_the_bug)

-  Setelah mencoba mereproduksinya dengan stabil dan master build Anda, atur status ke [NEW atau biarkan UNCONFIRMED](https://wiki.documentfoundation.org/QA/GetInvolved#Try_to_reproduce_the_bug)

Apa yang tercantum di atas memang seolah sangat panjang, tapi percayalah semakin sering dilakukan dan menjadi rutinitas, maka hal-hal yang disebutkan di atas akan terasa sangat mudah.

Untuk Anda yang ingin membaca detail mengenai QA, silakan merujuk ke [halaman wiki QA](https://wiki.documentfoundation.org/QA/GetInvolved#Quick_start_guide_for_beginners).

### Kelas Rutin QA

LibreOffice Indonesia mengadakan kelas rutin QA tiap Selasa malam. Kelas ini dilakukan bersama para pakar dari LibreOffice dan menggunakan bahasa Inggris sebagai pengantar. Namun jangan khawatir, karena akan banyak juga member dari Komunitas LibreOffice Indonesia yang siap untuk membantu Anda apabila menemukan kesulitan.

