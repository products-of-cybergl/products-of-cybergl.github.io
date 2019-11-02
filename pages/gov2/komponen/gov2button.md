---
layout: post
aplikasi: dasar-gov2
permalink: gov2/komponen/gov2button
---

{% include image.html 
    img="gov2/komponen/gov2button.jpg"%}


Unduh kode sumber di : [github.com/wibisastro/gov2button](https://github.com/wibisastro/gov2button).

Berikut contoh tag dan penggunaannya.

#### Tag

`<gov2button button-label="Pilih Data"></gov2button>`

#### Property
- buttonLabel **type: String** fungsinya untuk memberi label button
- buttonSize: **type: String** fungsinya untuk memberi ukuran button

#### Data
- isPressed: false

#### Methods
- toggleClick fungsinya mengubah nilai var **isPresed** ke nilai selain yang sedang terkandung
- resetButton fungsinya mengubah nilai var **isPresed** ke false

#### Created
- resetButton listen event dengan value **resetButton**, jika ada eksekusi method resetButton di atas
