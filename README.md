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

![WhatsApp Image 2025-07-07 at 14 26 09_af191aea](https://github.com/user-attachments/assets/141e7eb7-0f9d-4436-82a4-5aa466b2a728)

PENJELASAN TERKAIT QUERY DIATAS :
- **for col in df.columns:
    count = df[col].duplicated().sum()
    if count > 0:
        print(f"{col}: {count} duplikat")** : Lihat berapa baris duplikat

![Query10](https://github.com/user-attachments/assets/579083d3-400d-4fc3-9c10-88863dbf69fd)
PENJELASAN TERKAIT QUERY DIATAS :
- **df = df.drop_duplicates(subset=['NamaJudulKolom'])** : Menghapus data yang duplikat

**5. MENGHITUNG NILAI MINIMUM, MAKSIMUM, DAN RATA-RATA**

![Query6](https://github.com/user-attachments/assets/ef9a6b48-04d7-407b-9ab2-b2a72193341e)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk cek statistik dasar tergantung statistik apa yang digunakan

**6. FUNGSI PIVOT**

![query13](https://github.com/user-attachments/assets/3e60d518-2354-4a84-96f5-596a3e7727c7)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk menggantikan fungsi pivot table Excel untuk total jumlah penduduk per kecamatan

**7. MENAMPILKAN SEMUA BARIS DAATA**

![Query8](https://github.com/user-attachments/assets/d415d2fe-5dcd-4d6e-9cba-325718cf3b69)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk menampilkan semua baris data

**8. CEK JUMLAH TOTAL MISSING VALUES DI SELURUH DATAFRAME**

![query12)](https://github.com/user-attachments/assets/7791fd32-3705-4aef-8f20-b56420d35011)

PENJELASAN TERKAIT QUERY DIATAS :
- Berguna untuk cek total missing values di seluruh dataframe yang ada
df.isnull().sum().sum()



