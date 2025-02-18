# Atenuasi pada gelombang
---
**Atenuasi** merupakan kondisi dimana sinyal yang terekam pada stasiun mengalami peluruhan amplitude yang diakibatkan oleh medium tempat gelombang tersebut merambat. Secara umum, atenuasi merupakan salah satu parameter dari pengaruh medium yang ikut mempengaruhi perilaku dari sinyal yang mana jika dalam domain frekuensi, sinyal yang terekam pada stasiun merupakan perkalian dari pengaruh sumber gempa `S(f)`, jalur medium merambat `B(f)`, kondisi sekitar stasiun perekaman `R(f)`, dan pengaruh instrumen/alat perekam tersebut `I(f)`. Secara matematisnya dapat dituliskan sebagai berikut:

<div class="code-example" markdown="1">
![persamaan sinyal dalam domain frekuensi](https://raw.githubusercontent.com/yudhastyawan/catatan-yudha/6931c1b18228952258df96ee1e0d9d05dee16931/assets/images/atenuasi-1.svg)
{: .text-center }
</div>

Pada persamaan tersebut, atenuasi merupakan bagian dari `B(f)` yang diwakilkan oleh kebalikan dari faktor kualitas `Q`. Sebelum itu, perlu diperhatikan bahwa persamaan tersebut memiliki variabel `i` dan `j` yang mana merupakan index sumber gempa dan stasiun. Dari persamaan tersebut, kita dapat mengetahui bahwa nilai fungsi `S(f)` hanya dipengaruhi oleh kondisi dari gempa tersebut, sehingga jika beberapa stasiun merekam sumber gempa yang sama, maka nilai `S(f)` akan tetap sama di semua stasiun tersebut. Kondisi tersebut dapat diterapkan juga pada `R(f)` dan `I(f)` untuk stasiun yang sama. Lainnya, `B(f)`, memiliki nilai yang berbeda pada setiap pasangan sumber gempa dan stasiun.

Kembali ke atenuasi, parameter `Q` dijabarkan oleh parameter atenuasi `t*` pada fungsi jalur medium `B(f)` yang secara matematis dapat dituliskan sebagai berikut:

<div class="code-example" markdown="1">
![persamaan B(f)](https://raw.githubusercontent.com/yudhastyawan/catatan-yudha/6931c1b18228952258df96ee1e0d9d05dee16931/assets/images/atenuasi-2.svg)
{: .text-center }
</div>

dimana `t*` merupakan fungsi dari:

<div class="code-example" markdown="1">
![persamaan tstar](https://raw.githubusercontent.com/yudhastyawan/catatan-yudha/6931c1b18228952258df96ee1e0d9d05dee16931/assets/images/atenuasi-3.svg)
{: .text-center }
</div>

Pada persamaan `B(f)`, didapati variabel `f` yang merupakan nilai rentang frekuensi pada sinyal. Adapun persamaan `t*`, parameter `V` merupakan model kecepatan medium yang dilalui oleh setiap segmen jalur rambatan `ds` gelombang tersebut (*raypath*).
