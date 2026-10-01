# Netflix Data Cleaning with Power Query

## Project Overview
Project ini berfokus pada proses data cleaning dan transformation menggunakan Power Query pada Netflix Titles Dataset.

## Objective
Membersihkan dan menyiapkan data agar lebih terstruktur, konsisten, dan siap digunakan untuk analisis lebih lanjut.

## Data Cleaning Process
- Memeriksa missing values
- Memeriksa duplikasi berdasarkan `show_id`
- Mengubah `date_added` menjadi tipe Date
- Mengubah `release_year` menjadi Whole Number
- Memisahkan informasi `duration` menjadi:
  - `duration_min`
  - `seasons`
- Memeriksa data errors
- Memvalidasi hasil akhir dataset

## Tools
- Power BI
- Power Query

## Dataset
Netflix Titles Dataset

## Project Files
| File | Description |
|---|---|
| `Netflix_Data_Cleaning.pbix` | Power BI project |
| `Before_Cleaning.png` | Data sebelum proses cleaning |
| `After_Cleaning.png` | Data setelah proses cleaning |

## Result
Dataset berhasil melalui proses cleaning dan transformation sehingga lebih siap digunakan untuk exploratory data analysis (EDA) dan visualisasi.
