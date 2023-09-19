# Project_Simple_ETL_with_Pandas
Project yang Akan Dikerjakan
Pada proyek kali ini, Anda diminta untuk mengolah data pendaftar hackathon yang diselenggarakan oleh DQLab bernama DQThon.

Dataset ini terdiri dari 5000 baris data (5000 pendaftar) dengan format CSV (Comma-separated values) dan memiliki beberapa kolom diantaranya:

participant_id: ID dari peserta/partisipan hackathon. Kolom ini bersifat unique sehingga antar peserta pasti memiliki ID yang berbeda
first_name: nama depan peserta
last_name: nama belakang peserta
birth_date: tanggal lahir peserta
address: alamat tempat tinggal peserta
phone_number: nomor hp/telepon peserta
country: negara asal peserta
institute: institusi peserta saat ini, bisa berupa nama perusahaan maupun nama universitas
occupation: pekerjaan peserta saat ini
register_time: waktu peserta melakukan pendaftaran hackathon dalam second
Namun pada proyek ini nantinya Anda diminta untuk menghasilkan beberapa kolom dengan memanfaatkan kolom-kolom yang ada, sehingga akhir dari proyek ini berupa hasil transformasi data dengan beberapa kolom baru selain dari 10 kolom diatas.

A. Extract
Extract merupakan proses meng-ekstraksi data dari sumber, sumber data ini bisa berupa relational data (SQL) atau tabel, nonrelational (NoSQL) maupun yang lainnya.

Tugas Anda adalah baca terlebih dahulu dataset ini sebagai CSV agar nantinya bisa diolah. Gunakan live code editor untuk menampilkan dataset.

File tersebut bisa diakses melalui URL: https://storage.googleapis.com/dqlab-dataset/dqthon-participants.csv.
import pandas as pd
df_participant = pd.read_csv('https://storage.googleapis.com/dqlab-dataset/dqthon-participants.csv')
