### Tours Section

#### Sesi pertama
- Membuat grid 3 bagian.
- Membuat card dengan 2 section.
- Ketika di-hover akan me-rotate 2 section yang kita buat.

###### perspective: 
properti ini kita gunakan saat kita membuat efek rotate 3 dimensi. Sedangkan valuenya akan menentukan panjang rotate (semakin kecil nilai value maka semakin panjang juga ukuran section saat me-rotate).

###### backface-visibility:
Sebenarnya ini untuk menyembunyikan bagian belakang saat melakuka rotate. Misal ada dua section (section1 dan secion2) dan ketika kita hover maka akan berputar. Saat section berputar (misal dari section1 ke section2) kita tidak ingin section1 terlihat. Di sinilah property "backface-visibility:hidden" berguna karena akan menyembunyikan bagian section1 ketika berputar ke section2. 


#### Sesi kedua
Sesi kali ini adalah kita apply image dan kita kombinasikan dengan linear-gradient menggunakan properti "background-blend-mode". background-blend-mode digunakan untuk mencampur/menggabungkan warna dan gambar.

Selain itu kita juga berkenalan dengan properti CSS baru yaitu "box-decoration-brake:clone". Sejauh yang saya pahami fungsi dari properti tersebut adalah untuk menyamaratakan padding ketika ada text yang seharusnya satu baris tetapi kita jadikan lebih dari satu baris. Jadi misal text tersebut memiliki padding 10px dan kita jadikan lebih dari 1 baris maka paddingnya akan berantakan. Untuk menyamakan padding tersebut kita beri properti "box-decoration-break:clone".

Selebihnya kita styling untuk bagian frond-side dan back-side nya.
