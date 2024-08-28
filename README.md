# soal untuk pretest-data-engineer

namespace kestra = https://kestra-magang.t-dev.site/ui/namespaces/edit/argyaja

## Knowledge Base
1. Apa yang Anda ketahui tentang Data Engineer ?
2. Ceritakan pengalaman Anda dalam mengolah data?
3. Apa yang kamu ketahui tentang AI
4. Mengapa Data menjadi sesuatu yang sangat penting sekarang, dan apa dampak dari kebocoran data
5. Apa yg anda ketahui mengenai model generative AI ? da apa saja penerapannya

jawaban : 
1. bertugas menyiapkan data yang dikoleksi dari berbagai sumber sehingga ada bisa digunakan untuk keperluan perusahaan.

2. Melakukan data cleaning hasil review hotel lalu dilanjutkan dengan sentiment analysis. Melakukan data cleaning hasil tes kesehatan seseorang pasien, yang nanti digunakan untuk memprediksi apakah seseorang terkena penyakit jantung atau tidak.

3. salah satu bidang ilmu komputer yang dikhususkan untuk memecahkan masalah yang bisa diselesaikan dengan kecerdasan manusia.

4. Seseorang yang terkena dampak kebocoran data akan mengalami kekhawatiran terkait keamanan informasi pribadinya, contoh nya terkait finansial. Selain itu, dapat menyebabkan pencurian identitas, pemasangan ransomware dan sebagainya.

5. tipe AI yang dapat membuat konten dan ide, mulai dari teks, gambar, hingga audio, berdasarkan apa yg sudah dipelajari dari konten-konten yang sudah ada. 

## Soal Coding
studi kasus = 
seorang data engineer diharuskan oleh klien untuk membuat
blueprint data orchestration di sebuah tools yaitu Kestra.
klien ingin memproses data review lazada (review-lazada.csv).

kami sudah menyediakan akses kestra di
[Kestra](https://kestra-magang.t-dev.site/) - https://kestra-magang.t-dev.site/ 
silahkan pelajari kestra lihat dokumentasinya 
dan silahkan lakukan proses dibawah ini:

1. satu flows untuk proses data cleansing dimana bersihkan data reviewnya kemudian export ke csv
2. satu flows untuk proses menghitung sentiment analysis berdasarkan kolom rating

Keterangan :
flow kestra dan script python sertakan dalam git kalian ketika pelaporan
