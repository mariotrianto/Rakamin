# Tentang Dataset

## Konteks

Deposito berjangka adalah sumber pendapatan utama bagi bank. **Deposito berjangka** adalah investasi tunai yang disimpan di lembaga keuangan. Uang Anda diinvestasikan dengan tingkat bunga yang disepakati selama jangka waktu tertentu, atau jangka waktu. Bank memiliki berbagai rencana jangkauan untuk menjual deposito berjangka kepada pelanggan mereka seperti pemasaran email, iklan, pemasaran melalui telepon, dan pemasaran digital.

Kampanye **pemasaran melalui telepon** masih tetap menjadi salah satu cara paling efektif untuk menjangkau orang. Namun, mereka memerlukan investasi besar karena pusat panggilan besar disewa untuk benar-benar menjalankan kampanye ini. Oleh karena itu, sangat penting untuk mengidentifikasi pelanggan yang paling mungkin untuk berkonversi sebelumnya sehingga mereka dapat ditargetkan secara khusus melalui panggilan.

Data ini terkait dengan kampanye pemasaran langsung (panggilan telepon) dari lembaga perbankan Portugis. Tujuan **klasifikasi** adalah untuk memprediksi apakah klien akan berlangganan deposito berjangka **(variabel y)**.

Data ini terkait dengan kampanye pemasaran langsung dari **lembaga perbankan Portugis**. Kampanye pemasaran didasarkan pada panggilan telepon. Seringkali, lebih dari satu kontak dengan klien yang sama diperlukan untuk mengetahui apakah produk (deposito berjangka bank) akan ('ya') atau tidak ('tidak') berlangganan oleh pelanggan atau tidak. Folder data berisi dua dataset:-

train.csv: 45.211 baris dan 18 kolom yang diurutkan berdasarkan tanggal (dari Mei 2008 hingga November 2010)
test.csv: 4.521 baris dan 18 kolom dengan 10% dari contoh (4.521), dipilih secara acak dari train.csv


---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------
# Deskripsi Kolom:

1 - age :(numeric)

2 - job : jenis pekerjaan 
(categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self employed","retired","technician","services")
    
3 - marital : status perkawinan 
(categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
    
4 - education : 
(categorical: "unknown","secondary","primary","tertiary")
    
5 - default: apakah memiliki kredit macet? 
(binary: "yes","no")
    
6 - balance: saldo rata-rata tahunan, dalam euro (numeric)

7 - housing: apakah memiliki kredit rumah?
(binary: "yes","no")
    
8 - loan: apakah memiliki pinjaman pribadi?
(binary: "yes","no")


# Terkait dengan kontak terakhir dari kampanye saat ini:

9 - contact: jenis komunikasi kontak 
(categorical: "unknown","telephone","cellular")

10 - day: hari kontak terakhir dalam bulan (numeric)

11 - month: bulan kontak terakhir dalam tahun
(categorical: "jan", "feb", "mar", …, "nov", "dec")

12 - duration: durasi kontak terakhir, dalam detik (numeric)


# Atribut Lainnya:

13 - campaign: jumlah kontak yang dilakukan selama kampanye ini dan untuk klien ini (numeric, includes last contact)

14 - pdays: jumlah hari yang berlalu setelah klien terakhir dihubungi dari kampanye sebelumnya (numeric, -1 means client was not previously contacted)

15 - previous: jumlah kontak yang dilakukan sebelum kampanye ini dan untuk klien ini (numeric)

16 - poutcome: hasil dari kampanye pemasaran sebelumnya (categorical: "unknown","other","failure","success")

Output variable (desired target):
17 - y - apakah klien berlangganan deposito berjangka? (binary: "yes","no")

---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------
# Isi Konten:

a. Proses Data Cleansing
