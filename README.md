# ExcelPP58Tahun2023
File Excel untuk mensimulasikan perhitungan Take Home Pay dan PPh Menurut PP Nomor 58 Tahun 2023 baik secara Gross maupun Gross-Up
<br>
<br>
Klik pada button [<>Code], pilih download, maka file spreadsheet
akan terdownload dalam bentuk ZIP.
<br>
<br>
Penerbitan PP Nomor 58 Tahun 2023 tentang Tarif Pemotongan
PPh 21 menggunakan Tarif Efektif (TER) bertujuan untuk
menyederhanakan perhitungan PPh 21 atas Penghasilan
Sehubungan dengan Pekerjaan, Jasa, atau Kegiatan
Wajib Pajak Orang Pribadi.

Untuk kesesuaian dengan Peraturan Pemerintah, penyederhanaan
perhitungan ini menyebabkan tim payroll masing-masing
perusahaan perlu menyesuaikan aplikasi maupun spreadsheet
yang selama ini digunakan untuk menghitung PPh Bulanan
dari Januari s/d November, sedangkan PPh masa terakhir
(Desember) adalah berdasarkan pengurangan atas PPh setahun
menggunakan tarif Pasal 17 ayat (1) huruf a terhadap Total PPh
yang sudah dipotong pada Januari s/d November yang menggunakan Tarif Efektif.

## Metode GROSS UP
Pada metode Gross Take home pay yang diterima oleh karyawan
adalah setelah dipotong PPh 21 oleh pemberi kerja.
Untuk meningkatkan produktifitas karyawan, adalah tidak
jarang perusahaan memberikan tunjangan PPh 21 kepada
karyawannya dan agar tunjangan tersebut dapat
diakui sebagai beban usaha yang deductible,
maka tunjangan tersebut harus menjadi
penghasilan bruto bagi penerimanya dan
dihitung dengan menggunakan metode Gross-Up.

Perhitungan tunjangan PPh 21 Gross-Up adalah
sulit dilakukan tanpa bantuan Spreadsheet karena
membutuhkan iterasi sampai selisih antara
nilai tunjangan PPh 21 dengan PPh 21 dipotong adalah
mendekati nol.

Pada Spreadsheet, perhitungan tunjangan PPh 21 Gross-Up
dilakukan dengan menggunakan Circular References Formula yang
merupakan formula Close Loop yang dapat menyebabkan iterasi
tidak terbatas. Untuk menghindari iterasi yang tidak terbatas,
maka perlu diaktifkan [Enable Iterative Calculation] untuk
membatasi jumlah iterasi. Fitur [Enable Iterative Calculation]
dapat diakses melalui menu File->Options->Formula.

## Tarif PPh21 Lebih Tinggi
Berdasarkan UU Nomor 36 Tahun 2008 Pasal 21 Ayat 5a,
UU Nomor 36 Tahun 2008 Pasal 20 Ayat 1, dan PER-16/PJ/2016,
wajib pajak yang tidak memiliki NPWP adalah dikenakan tarif pajak 20 persen lebih tinggi dari tarif yang seharusnya berlaku.
PP Nomor 58 Tahun 2023 dan PMK 168 Tahun 2023 juga mengatur bahwa selain
pada masa pajak terakhir, pemotongan PPh 21 adalah dengan menggunakan Tarif Efektif Rata-Rata (TER). 

Menyambung postingan sebelumnya, saya dan Hendra Soewarno mengembangkan model spreadsheet
yang menghitung PPh 21 Karyawan berdasarkan Tarif Efektif dan juga mempertimbangkan pengenaan
tarif pajak sebesar 20 persen lebih tinggi dari tarif yang seharusnya berlaku bagi wajib pajak yang tidak memiliki NPWP.

Nb. <b>Menjelang diberlakunya NIK sebagai NPWP, maka pengenaan tarif pajak 20 persen lebih tinggi bagi pegawai yang tidak
memiliki NPWP adalah tidak efektif lagi.</b>

## Otomatisasi perhitungan Potongan PPh 21 Pegawai Tetap
enurut PP Nomor 58 Tahun 2023 Pasal 2 ayat 1 
bahwa Tarif pemotong PPh Pasal 21 terdiri atas:
(a) tarif perdasarkan Pasal 17 ayat 1 huruf a UU PPh dan;
(b) tarif efektif pemotongan PPh 21.

Mengenai masa pajak pemakaian masing-masing tarif tersebut
diatas adalah diperjelas oleh PMK 168 Tahun 2023 Pasal 15 ayat 1 bahwa PPh 21 yang
wajib dipotong bagi Pegawai Tetap:
(a) setiap Masa Pajak selain Masa  Pajak Terakhir dihitung menggunakan
tarif efektif bulanan;
(b) Masa Pajak Terakhir yaitu sebesar selisih antara PPh 21 yang terutang
selama 1 (satu) Tahun Pajak atau bagian Tahun Pajak dengan PPh 21
yang telah dipotong pada Masa Pajak selain Masa Pajak terakhir.
PPh 21 yang terhutang selama 1 (satu) Tahun atau bagian Tahun Pajak dihitung
menggunakan tarif Pasal 17 ayat (1) huruf a UU PPh.

Berdasarkan peraturan tersebut diatas, tim payroll 
masing-masing perusahaan perlu mempersiapkan spreadsheet
yang mampu menghitung potongan PPh 21 selain masa Pajak
terakhir dengan menggunakan Tarif Efektif Rata-Rata (TER)
dan juga mampu menghitung potongan PPh 21 menggunakan
tarif berdasarkan Pasal 17 ayat 1(a) untuk Masa
Pajak Terakhir.

Untuk keperluan tersebut diatas, sebagai Mahasiswa Jurusan Akuntansi,
saya tertarik untuk mengembangkan suatu model spreadsheet yang mampu
menghitung potongan PPh 21 pegawai tetap secara otomatis pada satu sheet tunggal
baik menggunakan TER ataupun tarif berdasarkan Pasal 17 ayat 1(a).

Semoga spreadsheet ini bermanfaat.
