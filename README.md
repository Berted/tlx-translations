# TLX Translations Project

## Tentang Project Ini

Project ini bertujuan untuk menerjemahkan kontes-kontes lokal yang ada di TLX ke Bahasa Inggris.

Semua penerjemahan akan dilakukan pada *repository* ini. \
Apabila Anda ingin berkontribusi, harap mengikuti Cara Kerja yang ada di bawah.

## Cara Kerja

1. Bikin [issue](https://github.com/prabowo02/tlx-translations/issues) untuk problemset yang ingin diterjemahkan. Judul issue adalah "Penerjemahan [nama-problemset]". Sebagai contoh: "Penerjemahan BNPCHS 2019 - Final". Deskripsi dari issue adalah judul-judul soal yang ada.

2. Penerjemah akan menerjemahkan soal-soal dalam bentuk **HTML**. Apabila format deskripsi Bahasa Indonesianya berbentuk pdf, maka terjemahan bahasa Inggrisnya tetap berbentuk **HTML**. Bisa saja terdapat lebih dari satu penerjemah untuk sebuah problemset, dan penerjemah tidak harus sama dengan yang orang yang membuka issue penerjemahan. Contoh HTML bisa dilihat dalam folder `contoh`.

3. Nama file terjemahan sebisa mungkin relevan (sebagai contoh: `bnpchs-final-2019-3-plus-1.html`) dan disimpan di dalam folder `translations`. Apabila sudah selesai diterjemahkan, buka [pull request](https://github.com/prabowo02/tlx-translations/pulls) dengan judul "Terjemahan [nama-problemset]: [judul-soal]". Sebagai contoh: "Terjemahan BNPCHS 2019 - Final: 3 Plus 1".

4. Setelah di-review, Pull Request akan dimerge oleh pemilik repository. Setelah semua problemset direview, maka ditunggu agar penerjemahannya dimasukkan ke TLX.

### Catatan

Beberapa catatan yang perlu diperhatikan:

- Untuk setiap baris pada file HTML, banyaknya karakter sebaiknya tidak melebihi 100. Hal ini dilakukan untuk mempermudah review.
- Apabila Anda ingin menggunakan inline equation, gunakan `$$$`.
- Apabila ingin menambahkan gambar, gunakan tag html `<img src="render/nama_gambar.png" />` dan tambahkan `nama_gambar.png` ke dalam pull request yang sama.
- Nama kontributor akan ditulis pada repo ini di bagian Credits.
