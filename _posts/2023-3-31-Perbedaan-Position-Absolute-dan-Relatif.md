---
layout: post
title: Perbedaan Position Absolute dan Relatif (CSS Layout)
---


![memulai menulis]({{ site.baseurl }}/images/write.jpg)

'Position' merupakan properti dari CSS, dipakai menentukan posisi elemen html. Ada 5 value dari properti Position, yaitu:

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

## Position Relative

`.example {
    position: relative;
}`

Elemen html dengan position:relative, mampu mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.

## Position Fixed 

`.example {
    position: fixed;
}`

Elemen html dengan position:fixed akan tetap berada ditempat, meskipun halaman discroll.  Relatif terhadap viewport, mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.

## Position Absolute

`.example {
    position: absolute;
}`

Elemen html dengan position; absolute akan tumpang tindih dengan elemen yang lainnya. Value ini biasanya dimix dengan value relative untuk menentukan posisi elemen child-parent yang diinginkan. mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.

## Position Sticky

`.example {
    position: sticky;
    position: -webkit-sticky; /* Safari */
}`

Value ini hampir sama dengan value fixed, bedanya, value sticky ini akan menjadikan elemennya posisi fixed ketika discroll. Mengubah posisi elemen tersebut dengan menambahkan properti left, right, bottom, dan top.

CMIIW.