# Quis 2017-1

Soal Quis Bootcamp

Buat lah program sederhana dengan kasus seperti berikut:

Studi Kasus:

Terdapat seorang nasabah datang ke customer service, lalu customer service tersebut menanyakan 'ada yang bisa saya bantu?' 
nasabah tersebut menjawab 'saya ingin membuat tabungan di sini, ada produk tabungan apa saya?', customer menjawab

- Produk TabunganKu dengan bunga/anum 3,5%, biaya admin Rp.1000/bulan, setoran awal minimal Rp.100,000,-.
- Produk Tabungan Mapan dengan bunga/anum 4%, biaya admin Rp.4500/bulan, setoran awal minimal Rp.500,000,-.
- Produk Tabungan Umroh dengan bunga/anum 2,5%, biaya admin Rp.100/bulan, setoran awal minimal Rp.100,000,-.

itu kata customer service lalu bertanya kembali 'jadi mau pilih yang mana pak?', nasabah tersebut menjawab 'saya pilih yang TabunganKu' ok klo gitu 'boleh minta data dirinya?' ok berikut data diri nasabah:

- Nama : Sulaeman Hasim
- alamat: Jl. Bojongsoang no 110
- kota : Bandung
- kec : Ciparay
- No hp: 081123123543

OK kami buatkan dulu ya pak... setelah menjelang beberapa saat, nomor rekening sudah jadi mau setoran berapa pak?
Rp.250,000,- ok pak. boleh ke kasir untuk melakukan setoran awal. setelah itu transaksi tercetak berikut cetakan buku tabunganya:

| kode           | Tanggal    | Debet           |  Kredit       | Saldo       |
| :------------- |:--------   | :-------------  | :-----------  | :---------- |
| 001            | 2017-08-01 | 250.000         | 0             | 250.000     |

Setelah itu terdapat transaksi setoran dan penarikan seperti berikut:


| kode           | Tanggal    | Debet           |  Kredit       | Saldo       |
| :------------- |:--------   | :-------------  | :-----------  | :---------- |
| 001            | 2017-08-20 | 250.000         | 0             | 500.000     |
| 001            | 2017-08-21 | 50.000          | 0             | 550.000     |
| 002            | 2017-08-22 | 0               | 250.000       | 250.000     | 

karena terjadi transaksi yang dilakukan oleh nasabah tersebut maka buku tabungan nasabah tersebut menajdi seperti berkut:


| kode           | Tanggal    | Debet           |  Kredit       | Saldo       |
| :------------- |:--------   | :-------------  | :-----------  | :---------- |
| 001            | 2017-08-01 | 250.000         | 0             | 250.000     |
| 001            | 2017-08-20 | 250.000         | 0             | 500.000     |
| 001            | 2017-08-21 | 50.000          | 0             | 550.000     |
| 002            | 2017-08-22 | 0               | 250.000       | 250.000     | 

Pertanyaannya:

1. Tentukan inputan apa saja dari studi kasus tersebut?
2. Buat Program menggunakan database berdasarkan kasus tersebut dan inputannya sesuai dengan soal no 1?
3. Buat inputan transaksi berdasarkan buku tabungan nasabah tersebut dan tampilkan outputnya seperti buku tabungan tersebut?

