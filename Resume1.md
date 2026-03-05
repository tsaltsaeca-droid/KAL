# **Resume**
# **Sistem Persamaan Linear**
Persamaan Linear  Sebuah ekspresi linear dalam $n$
perubahan tak diketahui (atau variabel)
$x_1, x_2, ..., x_n$ adalah ekspresi berbentuk

$$
a_1 x_1 + a_2 x_2 + \cdots + a_n x_n
$$

dengan $a_1, a_2, ..., a_n$ adalah bilangan real tetap.

Sebuah persamaan linear dalam perubahan $x_1, x_2, ..., x_n$ 
adalah persamaan yang dapat menyeimbangkan hanya menggunakan penjumlahan dan pengurangan menjadi bentuk

$$
a_1 x_1 + a_2 x_2 + \cdots + a_n x_n = b
$$

**Sistem Persamaan Linear**  Sebuah sistem persamaan linear (atau sistem linear ) adalah himpunan persamaan linear.
Suatu sistem linier disebut **homogen** jika seluruh persamaannya homogen.

Saat menampilkan sistem yang terdiri atas $m$ persamaan dalam $n$ perubahan $x_1, x_2, ..., x_n$,
biasanya kita menuliskan setiap persamaan dalam bentuk baku dan mengesampingkan suku-suku yang sesuai dengan dalam kolom:

$$
\begin{aligned}
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n &= b_1 \\
a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n &= b_2 \\
\vdots \\
a_{m1}x_1 + a_{m2}x_2 + \cdots + a_{mn}x_n &= b_m
\end{aligned}
$$

Sistem homogen biasanya ditulis sebagai:
$$
\begin{aligned}
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n &= 0 \\
a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n &= 0 \\
\vdots \\
a_{m1}x_1 + a_{m2}x_2 + \cdots + a_{mn}x_n &= 0
\end{aligned}
$$

Himpunan solusi berisi tak hingga banyak elemen; artinya, terdapat tak hingga solusi.Contoh:
$$
x - y = 0\\
x - y = 1\\
x - y = 0\\
x + y = 0\\
x - y = 1\\
2x - 2y = 2
$$

memiliki koefisien matriks:

$$
A =
\begin{bmatrix}
2 & 4 & -3 & 5 & 1 \\
3 & 1 & 0 & 1 & -3 \\
-2 & 7 & -5 & 2 & 2
\end{bmatrix}
$$

dan vektor konstantanya: 

$$
b =
\begin{bmatrix}
9 \\
0 \\
-3 
\end{bmatrix}
$$

**Augmentasi Matriks**
Matriks augmentasi (augmented matrix) adalah matriks yang dibentuk dengan menggabungkan dua matriks yang memiliki jumlah baris sama, biasanya matriks koefisien ($A$) dan vektor konstanta ($b$), menjadi satu kesatuan [$A|b$] untuk mempermudah penyelesaian sistem persamaan linear, sering kali menggunakan metode eliminasi Gauss atau Gauss-Jordan.

Contoh Augmentasi Matriks:
$ x_1-x_2+2x_3= 1 \\
 x_1+x_2+x_3= 8 \\
 x_1+x_2= 5$

Berikut adalah matriks augmentasinya:

$$
A =
\begin{bmatrix}
1 & -1 & 2 & 1\\
2 & 1 & 1 & 8\\
1 & 1 & 0 & 5
\end{bmatrix}
$$

A = matrix(QQ, 3, 3, [[1, -1, 2],
                      [2,  1, 1],
                      [1,  1, 0]])
b = vector(QQ, [1, 8, 5])
M = A.augment(b)
M

# **Persamaan Linear Dua Variabel**
Persamaan Linear Dua Variabel (PLDV) adalah persamaan dengan dua variabel (biasanya ($x$) dan ($y$)) yang memiliki pangkat tertinggi satu dan dihubungkan tanda sama dengan (($=$)), berbentuk umum ($ax+by=c$). Sistem Persamaan Linear Dua Variabel (SPLDV) terdiri dari dua persamaan tersebut untuk mencari nilai variabel yang sama. 
# **Persamaan Linear Tiga Variabel**
Sistem Persamaan Linear Tiga Variabel (SPLTV) adalah kumpulan tiga persamaan linear yang masing-masing memiliki tiga variabel berpangkat satu (umumnya $ x, y, z$) dan dihubungkan oleh tanda sama dengan ($=$). SPLTV mencari nilai-nilai variabel yang sama untuk semua persamaan, umumnya diselesaikan melalui metode eliminasi, substitusi, gabungan, atau matriks.
# **Aritmatika Matriks**
Matriks adalah susunan bilangan berbentuk persegi atau persegi panjang yang diatur. Matriks adalah array (daftar) bilangan yang terdiri dari baris-baris dan
kolom-kolom. Aljabar matriks adalah aljabar khusus untuk array tersebut.
Setiap array diperlakukan sebagai satu entitas yang membuatnya sangat
berguna dalam menganalisa data, terutama data yang multi variabel.