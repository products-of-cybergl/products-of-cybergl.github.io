---
layout: post
aplikasi: dasar-gov2
permalink: gov2/komponen/gov2notification
---

{% include image.html 
    img="gov2/komponen/gov2notification.jpg"%}


Unduh kode sumber di : [github.com/wibisastro/gov2notification](https://github.com/wibisastro/gov2notification).

Berikut contoh tag dan penggunaannya.

#### Tag

`<gov2notification></gov2notification>`

#### Property

Karena notif biasa dipanggil di Javascript, data tidak dikirim dari property.

#### Function

* .openNotif(): Parameternya adalah `Array` dengan terdapat key `notification` untuk teksnya & `class` untuk pemilihan warnanya (menggunakan prefix is-. Contoh: is-info).