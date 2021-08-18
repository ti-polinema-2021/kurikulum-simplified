# Kombinasi Proposisi

Setelah kita berkenalan dengan apa itu proposisi, kita juga bisa membuat satu proposisi baru, dengan cara mengkombinasikan beberapa proposisi. Kita bisa menggunakan operator perbandingan (and, or, not) untuk menggabungkan beberapa proposisi menjadi proposisi baru. Dan operator tersebut disimbolkan seperti ini :

* p / q atau abjad lain, simbol mewakili sebuah proposisi
* ^, simbol operator and / dan (konjungsi)
* ∨, simbol operator or / atau  (disjungsi)
* ~, simbol operator not / tidak (ingkaran)

#### Contoh kombinasi proposisi :

* p : Hari ini hujan
* q : Hari ini ini dingin
* maka : 
    * p ^ q dibaca : Hari ini hujan **DAN** Hari ini dingin
    * p v q dibaca : Hari ini hujan **ATAU** Hari ini dingin
    * ~q dibaca : **TIDAK** benar Hari ini dingin



### Intermezzo

Di dalam bahasa pemograma nanti, kita akan menggunakan operator logika juga untuk membuat proposisi baru. Namun, simbol dan penggunaannya tentu berbeda, berikut ini simbol operator logikan pada bahasa pemograman (javascript) : 

* &&, simbol operator and / dan (konjungsi)
* ||, simbol operator or / atau  (disjungsi)
* !, simbol operator not / tidak (ingkaran)

#### Contoh dalam bahasa pemograman :

```javascript
umur = 17
bisa_membuat_ktp = umur > 17

uang = 1000
bisa_membeli_mobil = uang > 1500

punya_mobil = bisa_membuat_ktp && bisa_membeli_mobil //operator and
punya_motor = bisa_membuat_ktp || bisa_membeli_mobil //oprator or
kebalikan = !bisa_membuat_ktp //operator not

```



