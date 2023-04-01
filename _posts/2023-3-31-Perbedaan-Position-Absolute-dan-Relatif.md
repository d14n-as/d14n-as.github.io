---
layout: post
title: Memposisikan Elemen (CSS Layout)
---


![memulai menulis]({{ site.baseurl }}/images/css.jpg)

## Apa Perbedaan Posisition Absolute dan Relatif?

'Position' merupakan properti dari CSS, dipakai menentukan posisi elemen html. Ada 5 value dari properti tersebut, yaitu:

- Static
- Relative
- Fixed
- Absolute
- Sticky

## Position Static

`.example {
    position: static;
}
`

Secara default, posisi elemen HTML adalah static. Elemen yang menggunakan properti ini tidak bergantung pada properti top, right, bottom, left. Jika ditambahkan properti left, right, bottom, dan top, elemen htmlnya tidak akan berubah posisi.

Contoh:

`.example {
    position: static;
    left: 20px;
}
`

Posisi elemen tidak akan berubah sedikitpun.

## Position Relative

`.example {
    position: relative;
}`

Elemen html dengan position:relative, mampu mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.


Contoh:

`.example {
    position: relative;
    left: 20px;
}
`

Posisi elemen akan mempunyai jarak/gap senilai 20px dari kiri.

## Position Fixed 

`.example {
    position: fixed;
}`

Elemen html dengan position:fixed akan tetap berada ditempat, meskipun halaman discroll.  Relatif terhadap viewport, mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.


Contoh:

`.example {
    position: relative;
    left: 20px;
}
`

Posisi elemen akan fixed dan mempunyai jarak/gap ke viewport senilai 20px dari kiri.

## Position Absolute

`.example {
    position: absolute;
}`

Elemen html dengan position; absolute akan tumpang tindih dengan elemen yang lainnya. Value ini biasanya dimix dengan value relative untuk menentukan posisi elemen child-parent yang diinginkan. mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.


Contoh:

`.exampleParentELement {
    position: relative;
}
`

`.exampleParentELement .exampleChildELement {
    position: absolute;
    left: 30px;
    top: 50px;
}
`

Posisi elemen dengan selector.exampleChildELement akan mempunyai jarak ke elemen parentnya yaitu selector .exampleParentELement dari kiri senilai 30px dan dari atas senilai 50px

## Position Sticky

`.example {
    position: sticky;
    position: -webkit-sticky; /* Safari */
}`

Value ini hampir sama dengan value fixed, bedanya, value sticky ini akan menjadikan elemennya ke posisi fixed ketika discroll. Mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.


Contoh:

`.sticky {
  position: -webkit-sticky;
  position: sticky;
  top: 10px;
}
`

Elemen dengan selector .sticky ketika discroll akan berada fixed ke viewport dengan jarak dari atas senilai 10px

CMIIW.