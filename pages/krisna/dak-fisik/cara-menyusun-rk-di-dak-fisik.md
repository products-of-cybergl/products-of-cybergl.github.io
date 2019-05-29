---
layout: post
aplikasi: dak-fisik
permalink: krisna/cara-menyusun-rk-di-dak-fisik
---

Pada manual ini dijelaskan mengenai proses dan potongan gambar setiap aktivitas terkait. Manual ini menjabarkan setiap tahapan secara berurutan. Tidak bisa dilakukan proses tertentu jika tidak melalui tahap sebelumnya.

#### 1. DJPK Kemenkeu dapat melakukan set Max Pagu (oleh user admin portal)

Dalam rangka melihat hasil penilaian yang ada pada fase sebelumnya yaitu fase Sinkronisasi. Fase dimana daerah dan pusat melakukan kesepakatan data usulan. Hasil sinkronisasi tersebut dibawa ke Multilateral Meeting dan rapat ke DPR  RI (Komisi & Banggar) berdasarkan nilai pagu alokasi yang sudah ditetapkan per daerah. Pada fase ini Krisna DAK ada dalam fase Pasca Sinkron.

Setelah sudah ada kesepakatan dengan DPR, maka Krisna DAK memasuki fase Pra Usulan RK. Yaitu fase dimana DJPK Kemenkeu melakukan pengaturan nilai batas atas pagu per daerah per bidang per jenis DAK. Disebut juga dengan istilah Max Pagu.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58482491-ad078f80-8188-11e9-8a3b-78871c0a664b.png"
    caption="Gambar 1.1. Klik menu Pagu DAK, Max Pagu, dan pilih daerah"
    max-width="500px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58485435-408f8f00-818e-11e9-84be-837fc3849fa8.png"
    caption="Gambar 1.2. Tampil table, klik tombol Ubah Batas Pagu"
    max-width="850px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58485618-982dfa80-818e-11e9-80d6-fb7ceff46b03.png"
    caption="Gambar 1.3. Isi nominal per Bidang, Sub bidang dan Jenis"
    max-width="850px"
%}

#### 2. Daerah harus melakukan set role RK (oleh user admin)

Setelah DJPK Kemenkeu selesai melakukan set nilai Max Pagu, maka fase Krisna DAK diubah menjadi Fase Usulan RK atau URK. Pada fase ini user di daerah harus di set menjadi role Bappeda RK agar dapat melihat data usulan yang ada di level detail rincian. Dan User di pusat harus klik checkbox di kolom RK agar dapat melakukan aksi di fase RK.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58485878-0f638e80-818f-11e9-9827-c7869b9cb30f.png"
    caption="Gambar 2.1. Admin daerah melakukan set user role Bappeda RK
"
    max-width="700px"
%}

#### 3. Daerah dapat melihat nilai Max Pagu & hasil penilaian

Setelah di set role Bappeda RK oleh admin, maka user tersebut dapat melihat data usulan dan hasil penilaian.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58486321-d8da4380-818f-11e9-9830-9ffe06a96278.png"
    caption="Gambar 3.1. Daerah dapat melihat hasil Max Pagu dan penilaian RK"
    max-width="800px"
%}

#### 4. Daerah dapat melakukan ubah data usulan (oleh user Bappeda RK)

User role Bappeda RK dapat melakukan aksi ubah data, dalam rangka menyesuaikan antara usulan sebelumnya dengan nilai pagu alokasi yang baru saja ditetapkan. Sehingga akan ada perubahan volume, unit cost dan metode pengadaan. Caranya adalah user dapat klik icon gembok di sudut kanan, kemudian pilih ubah.


{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58486443-16d76780-8190-11e9-826e-4246ea97643f.png"
    caption="Gambar 4.1. Bappeda RK dapat melakukan ubah data"
    max-width="400px"
%}

Setelah pilih ubah, maka akan tampil pop up form ubah data. Data Lokus tidak dapat diubah. Daerah juga sudah tidak dapat melakukan tambah data lagi.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58486791-b98fe600-8190-11e9-88dd-1a4edc260535.png"
    caption="Gambar 4.2. Bappeda RK dapat melakukan ubah data"
    max-width="800px"
%}

#### 5. Pusat dapat menambah dan ubah data usulan daerah (dengan user Planner RK di portal K/L)

User Planner RK yang ada di portal K/L dapat melakukan tambah data. Data yang ditambah oleh user role Planner RK akan tampil di table detail rincian, dan dapat dilihat juga oleh user daerah melalui portal nya. Data yang baru ditambah tersebut memiliki informasi bahwa data dibuat oleh user Planner RK.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58486973-112e5180-8191-11e9-8293-e75627ce8c96.png"
    caption="Gambar 5.1. User KL dapat melakukan tambah data"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58487298-8863e580-8191-11e9-9abe-ed313947721c.png"
    caption="Gambar 5.2. Form tambah data (form sama dengan form user daerah)"
    max-width="450px"
%}

Data Lokus tidak bisa diisi bebas, tetapi harus menggunakan data referensi Lokus. Seperti data Dapodik yang mana data nya telah terintegrasi dengan aplikasi Dapodik milik Kemendikbud. User hanya bisa memilih data Lokus. Setelah data berhasil ditambahkan, maka informasi-informasi terkait data usulan tersebut tersimpan di dalam database, dan dapat dilihat detail nya dengan cara klik icon + di samping nomor. Ketika di klik maka akan expand, dan menampilkan informasi detail nya. Termasuk si penambah data usulan / Created by : Planner. Artinya bahwa data ini ditambah oleh user Planner RK (oleh KL)

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58487667-3079ae80-8192-11e9-86bf-836a8e69a603.png"
    caption="Gambar 5.3. Informasi detail data usulan ketika di klik icon +"
    max-width="800px"
%}

Semua data dapat dilakukan proses ubah data oleh user Planner RK. Proses nya sama seperti ubah data yang dilakukan oleh user daerah dalam melakukan ubah data usulan. Yaitu klik icon gembok disebelah kanan, pilih ubah. Maka akan tampil form ubah data. Lakukan perubahan sesuai yang diinginkan kemudian klik save.

#### 6. Daerah dapat melakukan aksi konfirmasi daerah (oleh user role Bappeda RK)

Setelah data dapat dilihat oleh user Bappeda RK, maka dapat dilakukan checklist konfirmasi daerah. Artinya adalah bahwa daerah tersebut sanggup melaksanakan proyek tersebut. Karena bisa jadi user pusat menginginkan bahwa daerah tersebut melakukan proyek tertentu, berdasarkan usulan yang ditambah oleh user planner RK. Tapi tidak dapat disanggupi oleh daerah dikarenakan perihal administrasi, kesiapan teknis dan lain sebagainya. Jadi user Bappeda berhak menolak usulan tersebut dengan cara melakukan aksi “ditolak” pada kolom konfirmasi daerah. Atau pilih aksi “diterima” jika usulan dinyatakan disetujui oleh daerah.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58512790-1e1a6780-81c8-11e9-800e-2a773067ff1e.png"
    caption="Gambar 6.1. Tampilan kolom konfirmasi daerah"
    max-width="600px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58512872-5c178b80-81c8-11e9-9fc9-edb60d18e0bc.png"
    caption="Gambar 6.2. Form konfirmasi rekomendasi daerah"
    max-width="600px"
%}

Jika “Nilai Usulan RK data ini” melebihi nilai dari “Nilai yang dapat diterima (penugasan), maka data tidak dapat disimpan. Seharusnya daerah menurunkan nilai usulan RK, agar sesuai atau lebih kecil dari “Nilai yang dapat diterima (penugasan)”.

#### 7. Daerah dapat input Kegiatan Penunjang (oleh user role Bappeda RK)

Daerah dapat melakukan input kegiatan penunjang, yang mana daftar nomenklatur kegiatan penunjang telah ditentukan oleh sistem berdasarkan undang-undang. Daerah hanya bisa mengisi Volume dan Nilai nya. Yang mana nilai maksimalnya adalah 5% dari total nilai usulan yang ada dibawahnya.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58513349-7736cb00-81c9-11e9-9c12-5a6123d57d0f.png"
    caption="Gambar 7.1. Tombol tambah data Kegiatan Penunjang"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58513415-9cc3d480-81c9-11e9-9e80-8f208a741b2c.png"
    caption="Gambar 7.2. Form isian Kegiatan Penunjang"
    max-width="500px"
%}

Dalam form ini, lakukan : pilih referensi penunjang, isi volume, dan nilai kegiatan penunjang.

#### 8. Daerah dapat melakukan Lock data level Sub Bidang (oleh user role Bappeda RK)

Setelah dilakukan konfirmasi daerah dan mengisi kegiatan penunjang, maka Bappeda RK dapat mengunci Sub Bidang. Tujuannya adalah agar tidak ada lagi proses ubah data baik oleh daerah maupun oleh pusat. Lock data juga merupakan syarat agar data dapat dilakukan proses approval oleh pusat.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58513590-fd531180-81c9-11e9-8a00-56b604615c55.png"
    caption="Gambar 8.1. Lock data oleh Bappeda RK di level Sub Bidang"
    max-width="600px"
%}

#### 9. Pusat dapat melakukan Unlock data level Sub Bidang (oleh user Approver RK)

Setelah berjalan nya proses approval, ternyata Approver RK menilai ada hal yang harus diubah kembali oleh user Bappeda RK, agar sesuai harapan Approver RK. Jadi Approver RK harus melakukan Unlock data level Sub Bidang yang dimaksud, agar Bappeda RK dapat melakukan ubah data. Untuk kemudian Bappeda RK harus melakukan proses Lock data lagi agar dapat dilakukan proses approval oleh user Approver RK.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58513717-5327b980-81ca-11e9-8f24-63b0fb3aa27b.png"
    caption="Gambar 9.1. User Approver RK dapat melakukan aksi Unlock data level Sub Bidang"
    max-width="800px"
%}

#### 10. Pusat dapat melihat hasil konfirmasi daerah

Hasil konfirmasi daerah dapat dilihat oleh pusat, sehingga pusat / user Approver RK dapat melakukan proses approval terbatas hanya pada usulan yang dilakukan konfirmasi daerah. Tidak bisa dilakukan aksi approval pada usulan yang tidak dikonfirmasi daerah (icon x merah).

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58513902-c4676c80-81ca-11e9-80a5-3ee6cd78d05f.png"
    caption="Gambar 10.1. Tampilan konfirmasi daerah di portal daerah"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520262-216e1d00-81e1-11e9-8cce-44e7744644e9.png"
    caption="Gambar 10.1. Tampilan konfirmasi daerah di portal K/L"
    max-width="800px"
%}

#### 11. Pusat dapat melakukan aksi approval RK (oleh ser Approver RK)

Hanya usulan yang checklist hijau konfirmasi daerah yang dapat dilakukan aksi approval oleh user Approver RK.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520318-6c883000-81e1-11e9-8dba-44149aebc86e.png"
    caption="Gambar 11.1. Tampilan kolom approval KL"
    max-width="800px"
%}

Klik box pada kolom approval K/L untuk dapat melakukan aksi approval : No Action, Approve, Reject.

Jika Pilih aksi Reject maka mandatory isi keterangan.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520531-74949f80-81e2-11e9-973d-08f8033a703f.png"
    caption="Gambar 11.2. Form approval oleh user Approver RK"
    max-width="500px"
%}

#### 12. Pusat melakukan Lock Approval RK (oleh user Approver RK)

Setelah proses approval / penilaian dinyatakan sudah selesai. Maka user Approver RK harus melakukan Lock Approval. Tujuannya adalah agar tidak dapat dilakukan perubahan status Approval KL tidak berubah-ubah lagi. Dan data siap dikirim ke OMSPAN untuk laporan penyerapan anggaran.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520428-f20be000-81e1-11e9-8621-2268db20a57a.png"
    caption="Gambar 12.1. Tampilan Lock Approval"
    max-width="800px"
%}

Caranya: Ke level Sub Bidang, klik icon gembok, pilih Lock Approval. Jika sudah Lock Approval,maka icon akan menjadi gembok berwarna abu-abu. Artinya siapapun tidak dapat mengubah hasil approval dan tidak dapat membuka Lock approval (kecuali super admin Krisna).

#### 13. Semua user di portal manapun dapat melihat & simpan Rekapitulasi

Semua data yang ada di usulan akan ada di rekap data. Format Rekap berbeda-beda sesuai dengan masing-masing jenis. Data yang ditampilkan berasal dari data yang diinput oleh user.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520474-35fee500-81e2-11e9-9bd4-963a491a6b6f.png"
    caption="Gambar 13.1. Tampilan rekapitulasi"
    max-width="600px"
%}

User dapat melakukan isi kolom pejabat, yaitu nama, jabatan dan NIP. Klik checkbox NIP untuk menampilkan NIP pada Surat.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520618-d228ec00-81e2-11e9-9da0-da109dbfbbd0.png"
    caption="Gambar 13.2. Tampilan rekap surat lampiran"
    max-width="800px"
%}

Data yang tampil di bagian bawah kanan surat sesuai dengan data yang ditulis pada parameter Pejabat yang berwenang, pada penjelasan diatas.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520671-03a1b780-81e3-11e9-8ec4-becbb6d4cd52.png"
    caption="Gambar 13.3. Tampilan simpan surat lampiran ke format pdf"
    max-width="800px"
%}

Klik tombol print, maka akan menyimpan dokumen surat tersebut ke dalam format pdf.

#### 14. Daerah dapat melihat & unduh Laporan (Oleh user Bappeda RK)

Dalam rangka mencapai keterbukaan data, maka semua parameter data yang ada di database portal tersebut ditampilkan pada menu Laporan. Tujuannya agar adanya keterbukaan informasi. Pusat dan daerah mempunyai data yang sama, berdasarkan aksi-aksi yang telah dilakukan pada proses tahapan ini.

Caranya adalah dengan klik menu Rekap DAK, pilih Laporan. Kemudian klik view. Maka tampil data di table. Klik pivot table jika ingin mengubah tampilan menjadi tampilan pivot table.

Klik tombol csv untuk unduh data dalam format csv.

Klik tombol cls untuk unduh data dalam format xls.

Klik Show Column, kemudian akan tampil semua parameter data yang tampil. Un checklist parameter data jika tidak ingin parameter data tersebut ditampilan pada table.

Klik tombol print untuk menyimpan table dalam format pdf.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58520727-62ffc780-81e3-11e9-8afe-ecb525e9e219.png"
    caption="Gambar 14.1. Tampilan Laporan DAK"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58526191-62bdf700-81f8-11e9-82cd-6a569629804e.png"
    caption="Gambar 14.2. Tampilan Laporan dalam format pivot table"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58526303-b7fa0880-81f8-11e9-91a2-abbc929bb249.png"
    caption="Gambar 14.3. Tampilan parameter data yang ingin ditampilkan pada table"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58526345-e24bc600-81f8-11e9-8888-f69accfdb0f1.png"
    caption="Gambar 14.4. Tampilan simpan laporan data table dalam format pdf"
    max-width="800px"
%}

#### Daerah melihat Rekap RK

Daerah dapat melihat Rekap RK. Hasil Rekap RK sesuai dengan penilaian terakhir. Data ini yang nantinya akan digunakan untuk di upload ke Krisna. Caranya adalah klik menu Rekap RK, kemudian tampil pilihan sub-bidang. Lalu kli view.

Tombol print untuk download Rekap RK ke dalam format pdf. Tombol History untuk melihat user yang melakukan tambah, reset, edit tandatangan yang ada di Rekap RK.

Rekap RK ini yang akan menjadi dokumen tanggungjawab daerah ke pihak manapun dalam melakukan aktivitas kegiatan detail rincian.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58526435-263ecb00-81f9-11e9-879e-33f262427ea2.png"
    caption="Gambar 15.1. Tampilan Rekap RK"
    max-width="800px"
%}

#### Daerah dapat melakukan Sign document online (dengan user Kepala Bappeda atau Admin portal daerah)

Secara ideal, daerah melakukan print Rekap DAK, kemudian ditandatangan basah oleh kepala daerah, untuk kemudian di scan dan di upload ke Krisna. Tapi dikarenakan ada beberapa daerah yang mengalami kesulitan fasilitas, sehingga diadakan fitur Sign Documen online. User Bappeda RK dapat unggah tandatangan online agar masuk ke dalam surat.

Syaratnya user Bappeda RK juga harus di checklist kolom Signer. Agar dapat memasukan tanda tangan online.

Caranya : Klik menu Rekap DAK, klik view. Tampil laporan. Kemudian klik tombol re-sign document. Lalu muncul form sign document dan isi nama, nama jabatan, NIP, dan klik tombol upload untuk upload gambar tanda tangan.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58526497-56866980-81f9-11e9-9756-b7ca89b8319a.png"
    caption="Gambar 16.1. Checklist kolom signer"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58528136-96e8e600-81ff-11e9-9c67-a613f30f0a02.png"
    caption="Gambar 16.2. Pilih Sub bidang Rekap RK"
    max-width="800px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58528201-db748180-81ff-11e9-9519-3d9892b8244e.png"
    caption="Gambar 16.3. Form Sign Document"
    max-width="500px"
%}

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58528289-31e1c000-8200-11e9-9678-8127cdd3bbe7.png"
    caption="Gambar 16.4. Tampilan Rekap RK dengan tanda tangan online"
    max-width="800px"
%}

#### 17. Daerah melakukan upload dokumen Rekap RK (oleh user Kepala Bappeda atau admin portal daerah)

Hanya user role Kepala Bappeda dan admin portal yang dapat melakukan upload dokumen Rekap RK. Dengan menggunakan Krisna DAK, maka telah memperbaiki beberapa hal termasuk dalam hal tidak perlu print kertas Rekap, cukup upload di Krisna DAK. Dan Kemenkeu lebih mudah memantau administrasi dokumen. Karena hanya tinggal melihat data-data surat dengan format pdf yang ada di menu Upload Dokumen.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/58528409-9270fd00-8200-11e9-94af-20c7bfb180a2.png"
    caption="Gambar 17.1. Form upload document oleh user role Admin & Kepala Bappeda"
    max-width="800px"
%}

