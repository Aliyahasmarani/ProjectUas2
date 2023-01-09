#pertemuan16 

```s
NAMA    : ALIYAH ASMARANI
NIM     : 312210203
KELAS   : TI.22.A.2
MATKUL  : BAHASA PEMROGRAMAN
```

# DESKRIPSI

## model/daftar_nilai.py

- Modul ini diisi dengan class yang berisi method - method :
    1. **tambah_data()** yang mengimport modul inputan dari input_nilai dan di masukan ke modul data.
    2. **ubah_data()** yang mengimport modul inputan dari input_nilai dan menggunakan pengkondisian jika inputan di dalam modul data lalu memasukan inputan baru dari modul input_nilai ke dalam modul data.
    3. **hapus_data()** yang mengimport modul inputan dari input_nilai dan menggunakan pengkondisian jika inputan di dalam modul data lalu **menghapus** data di dalam modul data yang sesuai dengan modul inputan dari input_nilai.
    4. **cari_data()** yang mengimport modul inputan dari input_nilai dan mencetak data dari modul view_nilai yang sesuai dengan inputan dari modul input_nilai
     contoh program:

```sh
def tambah_data(self):
    # modul input_nilai
    # memasukan input_nilai ke modul data
def ubah_data(self):
    # modul input_nilai
    # pengkondisian jika modul input_nilai di dalam modul data
    # memasukan modul input_nilai baru ke dalam modul data
def hapus_data(self):
    # modul input_nilai
    # pengkondisian jika modul input_nilai di dalam modul data
    # hapus data yang sesuai modul input_nilai
def cari_data(self):
    # modul input_nilai
    # pengkondisian jika modul input_nilai di dalam modul data
    # modul view
def lihat_data(self):
    # modul input_nilai
    # pengkondisian jika modul input_nilai di dalam modul data
    # melihat modul input_nilai
```
### **model/ \__init_.py & view/ \__init_.py**

- Modul ini di isi dengan method Init dan berfungsi sebagai method yang pertama kali di jalankan atau di proses sebelum method-method yang lainnya dan method
  \__init_() berguna untuk melakukan inisialisasi pembuatan object dari class.
  - contoh pembuatan method \__init_()

```sh
def __init__(self, nama, nim):
    self._nama = nama
    self._alamat = nim
```

### **view/input_nilai.py**

- Modul ini di isi class input*data dan di isi dengan method inputan - inputan untuk modul - modul lainnya dan di inisialisasi dari method \_\_init*.
  - contoh pembuatan input:

```sh
self._nama = input('Masukan Nama : ')
self._nim = input('Masukan Nim : ')
```

### **view/input_nilai.py**

- Modul ini di berisi method cetak data mengimport dari modul **model/\_data.py**
  - contoh import dan cetak data:

```sh
# mengimport class data dari modul _data di dalam folder model
from view import input_nilai
# mencetak hasil inputan yang di tampung di class data
print(tabulate(data, headers, showindex=i,tablefmt="rounded_outline"))
```

karena disini saya memakai package **tabulate** jadi sebelum itu silahkan instal di **command prompt**

![gambar1](gambar/aku1.png)

setelah terinstall kita membuat modul yang berisi `from tabulate import tabulate`

![gambar2](gambar/aku2.png)

selanjutnya kita akan mencoba untuk di running atau dijalankan project yang telah dibuat

![gambar3](gambar/aku3.png)

