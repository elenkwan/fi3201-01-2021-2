# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219039'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
```
File "HelloWorld.py", line 2
    Terdapat kode Python berikut ini yang akan digunakan.
                ^
SyntaxError: invalid syntax
```
tested on https://onecompiler.com/python/3xrcw5u7y
## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
```
1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
3:◻◻◻
9:◻◻◻◻◻◻◻◻◻
```
tested on https://onecompiler.com/python/3xrcwsdxj
## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
```
1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
3:◼◼◼
9:◼◼◼◼◼◼◼◼◼
```
tested on https://onecompiler.com/python/3xrcx42cn
## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ ..
+ Mendifiniskan setiap digit angka pada NIM yang didefinisikan dengan menggunakan kotak hitam dan kotak putih 
+ ..
