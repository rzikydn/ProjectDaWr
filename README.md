# QUERY TUGAS PROJECT DATA WRANGLING
**1. IMPORT FILE DAN MENAMPILKAN 5 BARIS PERTAMA**

![Query1](https://github.com/user-attachments/assets/7d5b5e1a-3835-4436-a69f-20ce4d4467de)

PENJELASAN TERKAIT QUERY DIATAS :
- **import pandas as pd** : Berguna untuk mengimpor libray **pandas** kedalam python

- **df = pd.read_excel("Kependudukan_dki.xlsx")** : Berguna untuk membaca file yang ingin di import

- **df.head()** : Berguna untuk menampilkan 5 baris pertama

**2. MENGETAHUI DETAIL LENGKAP DATA FILE YANG DI UPLOAD**

![Query2](https://github.com/user-attachments/assets/384e0891-d458-4bb7-90af-acaddd63b51b)

PENJELASAN TERKAIT QUERY DIATAS :
- Mengetahui jumlah baris
- Tipe data tiap kolom
- Cek apakah ada nilai kosong di setiap baris

**3. PENGECEKAN PENULISAN PADA ISI FILE YANG DIUPLOAD**

![Query3](https://github.com/user-attachments/assets/2d0789d8-fcfe-4e70-a017-17cee67fddd6)

PENJELASAN TERKAIT QUERY DIATAS :
- Menghilangkan spasi di awal/akhir
- Ubah huruf jadi kapital semua supaya seragam

**4. PENGECEKAN DUPLIKASI**

![Query4](https://github.com/user-attachments/assets/0b5aa0c1-5798-4ddc-8835-c26e40ce020b)

PENJELASAN TERKAIT QUERY DIATAS :
- **df.duplicated().sum()** : Lihat berapa baris duplikat

- **df = df.drop_duplicates()** : Menghapus data yang duplikat

**5. MEMASTIKAN TIDAK ADA KOLOM YANG KOSONG**

![Query5](https://github.com/user-attachments/assets/4bec37eb-b7d1-4413-8788-25c6c1c5c2fe)

PENJELASAN TERKAIT QUERY DIATAS :
- Untuk memastikan tidak ada kolom yang kosong

**6. MENGHITUNG NILAI MINIMUM, MAKSIMUM, DAN RATA-RATA**

![Query6](https://github.com/user-attachments/assets/ef9a6b48-04d7-407b-9ab2-b2a72193341e)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk cek statistik dasar tergantung statistik apa yang digunakan

**7. FUNGSI PIVOT**

![Query7](https://github.com/user-attachments/assets/52c52c3b-f60a-4db8-adc8-52157af6827a)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk menggantikan fungsi pivot table Excel untuk total jumlah penduduk per kecamatan

**8. MENAMPILKAN SEMUA BARIS DAATA**

![Query8](https://github.com/user-attachments/assets/d415d2fe-5dcd-4d6e-9cba-325718cf3b69)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk menampilkan semua baris data



