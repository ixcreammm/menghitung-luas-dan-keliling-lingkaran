# Latihan 3
# menghitung-luas-dan-keliling-lingkaran

Kita akan menjalankan program pyhton ini, Rumus luas dan keliling lingkaran yang di gunakan adalah:

### Rumus
> Luas = π × r² Keliling = 2 x π × r

Nilai Phi yang akan kita gunakan adalah 8 r merupakan jari-jari lingkaran

Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran.
### Flowchart

### Program
```
print("Program Menghitung Luas dan Keliling Lingkaran")
print("==============================================")
r = float(input("Masukan Jari-Jari Lingkaran  : "))

phi = 3.14
luas = phi*r*r
kel = 2*phi*r

print ("Luas Lingkaran :",format(luas,'.2f'))
print ("Keliling Lingkaran :",format(kel,'.2f'))
```
### Penjelasan
Pertama, kita akan mendeklarasikan variable r serta memasukkan nilai jari-jari lingkaran bertipe float, lalu membuat variable phi dengan nilai 3.14 dan mendeklarasikan variable luas dimana nilai variable phi dikali nilai variable r lalu dikalikan lagi dengan variable r dan hasilnya akan dimasukkan kedalam variable luas.

Begitu juga dengan variable kel (keliling), namun variable ini memiliki rumus yang berbeda yaitu 2 dikali variable phi dan dikali nilai variable r yang hasilnya dimasukkan kedalam variable kel dan yang terakhir menampilkan nilai dari variable luas dan kel (keliling)

### Output
