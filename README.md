<h1> DATABASE NORMALIZATION - FROM FORMS to 3NF</h1>

<h2>UNF</h2>
<h3>UNF (Unnormalized Form) adalah data mentah yang diperoleh dari form. </h3>

<p>Tabel masih mentah, seringkali berisi nilai ganda (repeating groups) atau data yang belum terstruktur dalam bentuk baris dan kolom yang rapi.</p>
<p>Contoh pada kolom Data Nasabah, Agen, Branch Manager, dan Transaksi. Dapat dilihat bahwa 1 kolom tabel memiliki banyak data yang bercampur. Inilah yang dimaksud sebagai UNF</p>
<h3> Cara 🛠 Memperbaiki dan 🚀Naik Level ke 1NF </h3>
<p>Pisahkan tiap-tiap data menjadi 1 kolom sendiri dan 1 row sendiri. </p>

##


<h2>1NF</h2>
<h3>1NF (First Normalized Form) adalah olahan dari UNF yang dipecah menjadi 1 data per kolom. </h3>

<p>Tabel akan memunculkan redudansi data (duplikasi data) dari tiap row, namun tidak akan bercampur satu dengan lainnya. Dengan kata lain tabel ini harus memiliki sifat unik (primary key)</p>
<p>Contoh pada kolom Data Nasabah, data terpisah-pisah menjadi NasabahKode, NasabahNama,	NasabahMTBI, dan Nasabah_Tgl_TTD</p>

<h3> Cara 🛠 Memperbaiki dan 🚀Naik Level ke 2NF </h3>
<p> Pisahkan Primary Key / Id/ Kode yang penting menjadi 1 tabel lainnya demi menghilangkan grup yang berulang dan memastikan data berbentuk tabel dua dimensi yang sederhana.</p>

##
``
