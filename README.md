
```
# Pertemuan 06 - Nested Loop Python
# Nama : Ajeng Azmira Nur
# NIM  : 2225250120
# Kelas: 3E

n = int(input("Masukkan nilai n: "))

total_semua = 0
count_genap = 0

print("\nTabel Perkalian")
print("-" * 40)

for i in range(1, n + 1):
    total_baris = 0

    for j in range(1, n + 1):
        hasil = i * j

        print(f"{hasil:4}", end="")

        total_baris += hasil
        total_semua += hasil

        if hasil % 2 == 0:
            count_genap += 1

    print(f"  | Jumlah baris = {total_baris}")

print("-" * 40)

print(f"Total seluruh hasil : {total_semua}")
print(f"Banyak hasil genap  : {count_genap}")
print(f"Banyak pasangan     : {n * n}")
```

### Contoh ketika dijalankan

Jika input:

```
Masukkan nilai n: 3
```

hasilnya:

```
Tabel Perkalian
----------------------------------------
   1   2   3  | Jumlah baris = 6
   2   4   6  | Jumlah baris = 12
   3   6   9  | Jumlah baris = 18
----------------------------------------
Total seluruh hasil : 36
Banyak hasil genap  : 5
Banyak pasangan     : 9
```


Lalu masukkan ke GitHub dengan:

```
git add .
git commit -m "Menambahkan tugas nested loop dan statistik"
git push -u origin main
```
