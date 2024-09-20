Baik, berikut adalah versi singkat dalam format README sesuai dengan urutan materi yang kamu minta:

---

# Golang Learning Repository

This repository contains code and examples from a Golang learning series. Below is a breakdown of the topics covered:

## Table of Contents

1. [Pendahuluan](#pendahuluan)
2. [Pengenalan Golang](#pengenalan-golang)
3. [Menginstall Golang](#menginstall-golang)
4. [Membuat Project](#membuat-project)
5. [Program Hello World](#program-hello-world)
6. [Multiple Main Function](#multiple-main-function)
7. [Tipe Data Number](#tipe-data-number)
8. [Tipe Data Boolean](#tipe-data-boolean)
9. [Tipe Data String](#tipe-data-string)
10. [Variable](#variable)
11. [Constant](#constant)
12. [Konversi Tipe Data](#konversi-tipe-data)
13. [Operasi Matematika](#operasi-matematika)
14. [Operasi Perbandingan](#operasi-perbandingan)
15. [Operasi Boolean](#operasi-boolean)
16. [Tipe Data Array](#tipe-data-array)
17. [Tipe Data Slice](#tipe-data-slice)
18. [Tipe Data Map](#tipe-data-map)
19. [If](#if)
20. [Switch](#switch)
21. [For](#for)
22. [Break dan Continue](#break-dan-continue)
23. [Function](#function)
24. [Function Parameter](#function-parameter)
25. [Function Return Value](#function-return-value)
26. [Returning Multiple Values](#returning-multiple-values)
27. [Named Return Values](#named-return-values)
28. [Variadic Function](#variadic-function)
29. [Function as Value](#function-as-value)
30. [Function as Parameter](#function-as-parameter)
31. [Anonymous Function](#anonymous-function)
32. [Recursive Function](#recursive-function)
33. [Closure](#closure)
34. [Defer Panic dan Recover](#defer-panic-dan-recover)
35. [Komentar](#komentar)
36. [Struct](#struct)
37. [Struct Method](#struct-method)
38. [Interface](#interface)
39. [Interface Kosong](#interface-kosong)
40. [Nil](#nil)
41. [Type Assertions](#type-assertions)
42. [Pointer](#pointer)
43. [Asterisk Operator](#asterisk-operator)
44. [Operator New](#operator-new)
45. [Pointer di Function](#pointer-di-function)
46. [Pointer di Method](#pointer-di-method)
47. [Package dan Import](#package-dan-import)
48. [Access Modifier](#access-modifier)
49. [Package Initialization](#package-initialization)
50. [Error](#error)
51. [Membuat Custom Error](#membuat-custom-error)

---

## Pendahuluan
Pengantar tentang bahasa Go, tujuan, dan manfaatnya.
Dibuat dari bahsa C. Diluncurkan 2009. Banyak teknologi yang menggunakan golang seperti docker, kubernetes, prometheous dll. Digunakan diperusahaan yang menerapkan microservices. Bahasa yanng sangat sederhana, ga sesusah java bahkan java script. Ada fitur concurency yang merupakan kelebihan golang. Mnedukung garbage collection. Sedang naik daun di indonesia.

Go compiler -> compile file -> main.go dan  produce binary file -> main
## Pengenalan Golang
Membahas fitur utama Golang, seperti garbage collection, built-in concurrency, dan tipenya yang statically typed.

## Menginstall Golang
Langkah-langkah instalasi Golang pada sistem operasi yang berbeda.

## Membuat Project
Panduan untuk membuat dan menginisialisasi project baru di Golang menggunakan `go mod init`.

## Program Hello World
Contoh sederhana mencetak “Hello, World!” menggunakan Golang.

## Multiple Main Function
Menjelaskan bahwa program hanya boleh memiliki satu fungsi `main` sebagai entry point.

## Tipe Data Number
Tipe data numerik di Golang seperti `int`, `float64`, dan `complex`.

## Tipe Data Boolean
Tipe data boolean hanya memiliki dua nilai: `true` dan `false`.

## Tipe Data String
Deklarasi dan penggunaan tipe data string dalam Golang.

## Variable
Membahas cara mendeklarasikan variabel dengan `var` atau menggunakan pendeklarasian instan `:=`.

## Constant
Menjelaskan penggunaan konstanta dengan `const`, yang nilainya tidak bisa diubah.

## Konversi Tipe Data
Panduan untuk mengonversi tipe data secara eksplisit dalam Golang.

## Operasi Matematika
Operasi aritmatika dasar di Golang seperti penjumlahan, pengurangan, perkalian, dan pembagian.

## Operasi Perbandingan
Membandingkan nilai dengan operator seperti `==`, `!=`, `<`, `>`, `<=`, `>=`.

## Operasi Boolean
Operator logika seperti `&&`, `||`, dan `!`.

## Tipe Data Array
Deklarasi array dengan ukuran tetap dalam Golang.

## Tipe Data Slice
Penjelasan tentang slice yang lebih dinamis dibandingkan array.

## Tipe Data Map
Map digunakan untuk menyimpan pasangan kunci-nilai (`key-value`).

## If
Penggunaan statement `if` untuk membuat keputusan logika.

## Switch
Alternatif `if-else` yang lebih efisien untuk memeriksa beberapa kondisi.

## For
Satu-satunya loop di Golang yang bisa digunakan untuk iterasi.

## Break dan Continue
`Break` untuk menghentikan loop, `continue` untuk melewatkan iterasi tertentu.

## Function
Deklarasi fungsi dalam Golang dengan kata kunci `func`.

## Function Parameter
Parameter fungsi yang memerlukan tipe data yang jelas.

## Function Return Value
Pengembalian nilai dari fungsi menggunakan `return`.

## Returning Multiple Values
Fungsi bisa mengembalikan lebih dari satu nilai dalam Golang.

## Named Return Values
Memberi nama pada nilai pengembalian dari fungsi untuk kode yang lebih mudah dibaca.

## Variadic Function
Fungsi yang dapat menerima jumlah argumen yang tidak terbatas menggunakan `...`.

## Function as Value
Fungsi di Golang dapat disimpan dalam variabel dan dipanggil seperti variabel biasa.

## Function as Parameter
Fungsi dapat diteruskan sebagai parameter ke fungsi lain.

## Anonymous Function
Fungsi anonim adalah fungsi yang tidak diberi nama, biasanya digunakan sekali pakai.

## Recursive Function
Fungsi rekursif adalah fungsi yang memanggil dirinya sendiri, biasanya digunakan untuk masalah yang berulang.

## Closure
Closure adalah fungsi yang dapat mengakses variabel dari lingkup luarnya bahkan setelah lingkup tersebut tidak aktif.

## Defer Panic dan Recover
Penggunaan `defer` untuk menunda eksekusi, serta menangani error dengan `panic` dan `recover`.

## Komentar
Cara menulis komentar di Golang, baik untuk satu baris maupun beberapa baris.

## Struct
`Struct` adalah kumpulan tipe data yang berbeda yang digabungkan menjadi satu unit.

## Struct Method
Method adalah fungsi yang terkait dengan `struct`.

## Interface
Interface mendefinisikan sekumpulan method tanpa implementasi.

## Interface Kosong
Interface kosong (`interface{}`) dapat menyimpan nilai dari tipe apapun.

## Nil
`Nil` adalah nilai default untuk tipe data reference seperti pointer, map, slice, dll.

## Type Assertions
Digunakan untuk menegaskan tipe data dari variabel yang disimpan dalam interface kosong.

## Pointer
Pointer menyimpan alamat memori dari variabel.

## Asterisk Operator
Operator `*` digunakan untuk mengakses nilai dari alamat memori (pointer).

## Operator New
`new` digunakan untuk mengalokasikan memori dan mengembalikan pointer.

## Pointer di Function
Fungsi bisa menerima pointer sebagai argumen untuk mengubah nilai dari variabel yang dipoint.

## Pointer di Method
Method pada struct bisa menggunakan pointer untuk mengubah nilai field struct tersebut.

## Package dan Import
Cara mengorganisir kode dengan package dan mengimpor package lain menggunakan `import`.

## Access Modifier
Penentuan aksesibilitas (public atau private) dengan huruf awal nama variabel atau fungsi (huruf besar untuk public, huruf kecil untuk private).

## Package Initialization
Package bisa diinisialisasi dengan fungsi `init()`.

## Error
Penanganan error dalam Golang menggunakan tipe `error`.

## Membuat Custom Error
Cara membuat custom error dengan menggunakan `errors.New()` atau tipe struct.