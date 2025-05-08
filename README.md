# Customer Spending Analysis Outline

## Repository Outline
1. README.md - Penjelasan gambaran umum project
2. notebook.ipynb - Notebook yang berisi pengolahan data dan analisis data dengan python
3. spending_patterns_detailed.csv - Dataset yang digunakan


## Problem Background
**Latar Belakang:**<br>
Sebagai tim data analitik di sebuah bank, tim data diminta untuk mendukung tim promosi membuat promo untuk kartu kredit dengan menganalisis data transaksi dari sebuah supermarket. Bank berencana menjalin kolaborasi promosi dengan supermarket tersebut, dan tugas tim data analitik adalah menganalisis berbagai transaksi

**Problem Statement:**<br>
Bagaimana cara meningkatkan nasabah baru sebesar 10% dalam 3 bulan dengan menggunakan hasil analisis data untuk penyusunan promo pembayaran melalui kartu kredit baru?


## Project Output
Output project ini adalah sebuah dashboard untuk data storytelling menggunakan tableau public

## Data
Sumber Data: https://www.kaggle.com/datasets/ahmedmohamed2003/spending-habits<br><br>
Jumlah Kolom: 9 <br>
Jumlah Baris: 10000 <br>
Missing Value: 0 <br>
Kategorikal Kolom: 6 <br>
Numerikal Kolom: 3<br><br>
**Deskripsi Kolom**
|Kolom|Deskripsi| 
|-----|---------|
|`Customer ID`|Unique identifier for each customer (e.g., CUST_0001).|
|`Category`|The spending category (e.g., Groceries, Shopping, Travel).|
|`Item`|The specific item purchased within the category (e.g., Milk, Plane Ticket).|
|`Quantity`|Number of units purchased. For specific categories (e.g., Subscriptions, Housing and Utilities, Transportation, Medical/Dental, Travel), this is always 1.|
|`Price Per Unit`|The price of one unit of the item (in USD).|
|`Total Spent`|Total expenditure for the transaction (Quantity × Price Per Unit).|
|`Payment Method`|The payment method used (e.g., Credit Card, Cash).|
|`Location`|Where the transaction occurred (e.g., Online, In-store, Mobile App).|
|`Transaction Date`|The date of the transaction (YYYY-MM-DD format).|

## Method
Metode untuk memecahkan masalah adalah visualisasi menggunakan library python seperti plotly, matplotlib, dan seaborn.

## Stacks
Bahasa Pemrograman: Python<br>
<br>Library:<br>
1. pandas
2. matplotlib
3. seaborn
4. plotly
5. scipy

<br>
Tools dan Source lain: <br>
1. tableasu public

## Reference

- ### Dataset:
    [Dataset](https://www.kaggle.com/datasets/ahmedmohamed2003/spending-habits)

 - ### Deploy:
    [Tableau](https://public.tableau.com/views/Milestones1_17393585197170/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
---