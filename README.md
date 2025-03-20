Pemilihan
Pemilihan dalam algoritma digunakan untuk menentukan tindakan berdasarkan suatu kondisi.
Satu kasus:
Notasi algoritmik untuk analisis dengan satu kasus adalah menggunakan kontruksi IF-THEN
dalam bentuk pernyataan:
If kondisi then
Aksi
Endif
Contoh:
PROGRAM huruf_vokal
{mencetak pesan “huruf vokal” bila sebuah karakter yang dibaca merupakan huruf hidup}
DEKLARASI C: char
ALGORITMA: Read (c)
If (c=`a’) or (c=`I’) or (c=`u’) or (c=`e’) or (c=`o’) then write (`huruf vokal’)
endif
Dua Kasus:
Konstruksi IF-THEN hanya menyediakan satu alternatif aksi jika suatu persyaratan (kondisi)
dipenuhi. Kita perlu juga memilih melakukan aksi alternatif jika suatu kondisi tidak memenuhi.
Jika ada dua kasus, tetapi hanya salah satu dari keduanya yang harus dipilih satu untuk
dikerjakan.
If kondisi then aksi1
else
aksi2 endif
Tiga Kasus:
Masalah yang mempunyai tiga buah kasus atau lebih dapat dianalisis dengan konstruksi IFTHEN-
ELSE bertingkat-tingkat
if kondisi1 then aksi1
else
if kondisi2 then
aksi2 else
if kondisi3 then aksi3
endif
endif endif
