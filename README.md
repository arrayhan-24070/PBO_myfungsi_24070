# PBO_myfungsi_24070
PROJEK PBO UNTUK MEMENUHI MATA KULIAH PBO 
1. Apa itu fungsi di Python?

Fungsi adalah sekumpulan kode yang dibuat untuk melakukan tugas tertentu dan bisa digunakan berulang kali tanpa menulis ulang kodenya.
Fungsi membantu:

Membuat kode lebih rapi

Lebih mudah dipahami

Menghindari pengulangan kode

2. Cara membuat fungsi di Python

Fungsi dibuat menggunakan kata kunci def.

Contoh dasar:
def sapa():
    print("Halo, selamat datang!")

Penjelasan:

def → untuk mendefinisikan fungsi

sapa → nama fungsi

() → tempat parameter

: → awal blok kode

print(...) → isi fungsi

3. Cara memanggil fungsi
sapa()

Output:

Halo, selamat datang!

4. Fungsi dengan parameter
Parameter adalah data yang dikirim ke fungsi.
Contoh:
def sapa(nama):
    print("Halo", nama)

Pemanggilan:
sapa("Budi")
Halo Budi

5. Fungsi dengan lebih dari satu parameter
def tambah(a, b):
    print(a + b)
Pemanggilan:
tambah(5, 3)

6. Fungsi dengan return

return digunakan untuk mengembalikan nilai dari fungsi.

def kali(a, b):
    return a * b

Pemanggilan:
hasil = kali(4, 5)
print(hasil)

7. Perbedaan print dan return
print	return
Menampilkan hasil	Mengembalikan nilai
Tidak bisa disimpan	Bisa disimpan ke variabel
8. Contoh fungsi dalam kehidupan nyata
def hitung_luas_persegi(sisi):
    return sisi * sisi


Pemanggilan:

print(hitung_luas_persegi(6))


