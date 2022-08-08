# serba-serbi-odoo
Repo ini berisikan langkah2 tentang Odoo

## Daftar Isi
* [Setting Warehouse](#setting-warehouse)
* mengubah settingan nota
* setting printer
* setting kertas

### Setting Warehouse
1. Masuk ke Inventory.  
![inventory](/src/image/odoo-001.jpg)
2. Masuk ke Menu Configuration (yang ditandai nomer 2)  
![inventory](/src/image/odoo-002.png)
3. Klik menu Warehouse (yang ditandai nomer 3)  
![inventory](/src/image/odoo-002.png)
4. Tinggal setting warehouse sesuai yang diinginkan.

### Mengubah setting nota
1. Pastikan masuk ke odoo menggunakan __debug__ mode.
2. Masuk ke menu __Technical__  
![nota](/src/image/teknikal-001.png)
3. Pilih __Reports__ (dibawah sub menu Action)  
![nota](/src/image/teknikal-002.png)
4. Ketikkan pada kolom search, nama dari nota yang mau diubah. Misal ketikkan nota
5. Maka dibagian bawahnya akan muncul Nota SO ( sesuai contoh ), kemudian klik pada Nota SO tersebut
6. Setelah diklik maka akan muncul tombol dibagian kanan form tersebut bertuliskan QWeb Views. __Klik QWeb Views__.
7. Setelah itu klik pada __nota_so_reports_template__
8. Untuk mengubah tinggal klik __Edit__, setelah itu di bagian __Architecture__, cari yang mau diubah, misal footer dari nota tersebut akan diubah sesuai keinginan.
9. Jika sudah tinggal Save dan coba refresh. 

### Settingan kertas
1. Pengaturan settingan kertas printer menggunakan kertas 2 ply NCR PRS
2. Settingan di printer menggunakan kertas custom, dengan width = 9.5 cm x height = 14 cm
3. Dengan pengaturan margin minimal atau bahkan tidak ada
