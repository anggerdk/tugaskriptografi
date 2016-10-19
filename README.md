# tugaskriptografi
Tugas mata kuliah Kriptografi, Dosen Pengampu : Bu Afiahayati

Implementasi algoritma DES.
Algoritma DES (Data Encryption Standart) yang didasarkan dari algoritma lucifer.
Merupakan algoritma simetri dan tergolong dalam jenis cipher block.

Algoritma general dari DES adalah :
1. Blok plaintext dipermutasi dengan matriks permutasi awal (Initial Permutation)
2. Hasil permutasi di awal kemudian en-chipering sebanyak 16 kali (16 putaran). Setiap putaran menggunakan kunci internal yang berbeda
3. Hasil en-chipering kemudian dipermutasi dengan matriks permutasi balikan menjadi blok chipertext

# KONTRIBUSI di kelompok 7 - Kelompok Christian Ade Yanuar
Membantu memahami algoritma DES secara teori, pada bagian PC 1 dan PC 2 membantu sedikit coding (tidak sepenuhnya).
Pada PC 1 diperoleh dari permutasi 56 bit, kemudian dibagi menjadi 2, C[0] dan D[0]. 
kemudian C[0] dan D[0] di left-shift. kemudian hasilnya disusun lagi dan di permutasi menjadi PC 2 48 bit

Membantu dalam presentasi di hadapan kelas
