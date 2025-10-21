# PBOPertemuan10
Dalam pengolahan data berbasis database, proses input data secara manual sering memakan waktu lama dan rawan kesalahan. Untuk mengatasi hal ini, dibutuhkan cara yang lebih efisien yaitu dengan mengimpor data dari file eksternal seperti CSV (Comma Separated Values).

Pada praktikum ini dilakukan pembuatan fitur Upload File CSV menggunakan Java GUI (NetBeans) yang terhubung dengan database PostgreSQL. Dengan adanya tombol upload, data dapat dimasukkan ke tabel database secara otomatis hanya dengan memilih file CSV yang berisi data minuman.  

# CSV (Comma Separated Values)  
CSV adalah format file teks sederhana yang digunakan untuk menyimpan data dalam bentuk tabel, di mana setiap kolom dipisahkan oleh tanda koma atau titik koma (;). CSV sering digunakan karena mudah dibaca oleh manusia maupun program.

# JFileChooser
JFileChooser adalah komponen di Java Swing yang digunakan untuk membuka dialog pemilihan file. Dengan komponen ini, pengguna dapat memilih file dari sistem lokal untuk diolah oleh program.  

# BufferedReader
Kelas BufferedReader digunakan untuk membaca teks dari input stream secara efisien, termasuk membaca baris demi baris dari sebuah file.  

# Langkah - Langkah Project
1.	Buka project yang ingin di tambahkan button upload 
 <img width="376" height="210" alt="image" src="https://github.com/user-attachments/assets/f5ce34b9-312d-4cc8-80e4-b11fb920292d" />

2.	Buat button upload pada design jframe 
 <img width="732" height="507" alt="image" src="https://github.com/user-attachments/assets/8ffb60eb-cdae-488e-a239-90761f997917" />

3.	Kemudian pada button upload tambahkan source code berikut
 <img width="940" height="523" alt="image" src="https://github.com/user-attachments/assets/7674e41e-90b6-4b5a-9aba-7c59497d66a7" />
 <img width="896" height="658" alt="image" src="https://github.com/user-attachments/assets/6e6cae69-efa8-4f84-b49d-584cc22bd55c" />

Jangan lupa tambahkan juga import berikut pada bagian atas program   
 <img width="481" height="173" alt="image" src="https://github.com/user-attachments/assets/9b65b63a-10f1-4dc3-a603-069e5778db48" />

4.	Buat 9 data di excel dengan format csv 
 <img width="557" height="372" alt="image" src="https://github.com/user-attachments/assets/ab7221f2-40a9-471f-bf28-553dfec07cda" />

5.	Coba run programnya 
 <img width="814" height="609" alt="image" src="https://github.com/user-attachments/assets/aff9c306-777e-4d32-b412-8f43528fdf9f" />

6.	Klik button upload 
 <img width="816" height="613" alt="image" src="https://github.com/user-attachments/assets/3d9630a8-6715-4a45-bd73-4d7704c4016c" />

7.	Pilih file dengan format csv yang telah dibuat dan klik open Ketika sudah
 <img width="799" height="589" alt="image" src="https://github.com/user-attachments/assets/f78c52a8-d56a-472a-b466-3e034f2b5c1c" />

8.	Maka tabel akan secara otomatis terisi data file csv tanpa menggunakan button insert
 <img width="805" height="597" alt="image" src="https://github.com/user-attachments/assets/400ef177-b874-42bd-9660-f54ffbd805ae" />





