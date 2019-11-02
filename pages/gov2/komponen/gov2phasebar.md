---
layout: post
aplikasi: dasar-gov2
permalink: gov2/komponen/gov2phasebar
---

{% include image.html 
    img="gov2/komponen/gov2phasebar.jpg"%}

Proses bisnis di pemerintahan banyak yang menggunakan fase-fase. Oleh karena itu, Gov2 Framework menyediakan komponen phasebar.

Unduh kode sumber di : [github.com/wibisastro/gov2phasebar](https://github.com/wibisastro/gov2phasebar).

Berikut contoh tag dan penjelasan property-nya.

#### Tag

`<gov2phasebar :is-active="true" get-url="json" :state-no="stateNo"></gov2phasebar>`

#### Property

* is-active: Toggle untuk menghidupkan atau mematikan.
* get-url: nama folder yang berisi phases.json & state.json.
* state-no: State awal. Formatnya integer &mdash; ambil acuan dari phases.json & state.json. Isi 'stateNo' jika belum ada.