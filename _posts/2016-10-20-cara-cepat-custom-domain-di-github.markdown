---
published: true
title: Cara Cepat Custom Domain di Github
layout: post
tags: [custom, domain, github, hosting, gratis, cloudflare, freenom]
categories: [Tutorial]
permalink: cara-cepat-custom-domain-di-github
---
Judulnya sih sebenarnya gimana cara agar custom domain di github propagasinya ga sampai 5 menit. Ini adalah pengalaman untuk [blog ini][1]

Dua hari yang lalu saya ada ide untuk domain baru yang gratisan menggunakan [freenom][5]

Ide domainnya blogue, ternyata yang free cuma ada blogue.cf yawdah langsung ane daftarkan aja. Setelah itu nameservernya langsung saya update agar konek ke DNS cloudflare.

Update name server di freenom lebih cepat lho dibanding domain berbayar (tapi murah di alpnames), saya pernah menulis artikelnya [disini][2]

Setelah update name server ke cloudflare saya tinggal dulu, untuk dikerjakan besok harinya. Kebetulan punya ide buat ngeblog rata-rata sih malam.

Eh ternyata besoknya kelupaan dan baru malam ini bisa update records di cloudflare. Sempat bingung mau pake hosting yang mana. Hosting berbayar milik sendiri, custom domain blogger, hosting gratis atau hosting di github.

Akhirnya saya memilih github sebagai hostingnya.

Pertama, saya daftar dulu akun github baru, verifikasi email dan daftar [tinypress][3], setelah daftar dan setting langsung saya bikin [posting pertama][4] agar blognya aktif.

Setelah publish posting, lalu saya ke menu settings dan mengubah dulu records agar custom domainnya berjalan lancar.

***Begini contoh custom domain di github.io***

<p align="center">
<img src="https://github.com/bloguecf/bloguecf.github.io/blob/master/img/setting-custom-domain-github.io.jpg?raw=true" alt="Custom Domain di Github" title="Custom Domain di Github" />
</p>

Anda tinggal mengganti 'blogue.cf' dibagian A records menjadi domain anda dan 'bloguecf.github.io' dengan alamat github anda

Setelah setting selesai tinggal akses domain anda, jika propagasi dari registrar ke DNS cloudflare sudah selesai prosesnya ga sampai 5 menit lho.

[1]: http://blogue.cf
[2]: http://eka.gdn/masalah-propagasi-domain-gdn
[3]: http://tinypress.co
[4]: http://blogue.cf/posting-pertama
[5]: http://freenom.com
