tools ini bertujuan untuk mengecek Valid atau tidaknya CC
yang berbasis CLI (Command Line Interface)
untuk menggunakan tools ini 
harus disertakan semicolon dan kurung kurawal (tanda ; dan { })
diahkir setiap info
for example

{
CC Number:4561416613125005;
Exp      :12|2024;
CVV      :215;
Name     :Zharkaev Sarajeva;
Address  :1123 Zarved lazikh;
Country  :Russia;
poscode  :35454;
}

Silahkan siapkan
-CC list beserta informasinya seperti contoh lalu simpan dengan nama cclist.txt disatu folder Tools ini
-Proxy (tidak wajib)
-VPN (siapkan ketika loe mau CO)
-Laptop atau PC ataupun yang bersistem operasi Linux atau aplikasi Termux
-Jika tidak ada laptop/pc silahkan gunakan termux di android

Usage 
-Masukan cclist (list kartu kredit yang ingin di periksa) dibagian (Input your CClist {for example cclist.txt} :cclist)
-Masukan letak direktory proxy anda (jika diperlukan)
-Lalu tekan Y dan Enter
-Jika CC valid akan keluar Saved namelist YourOrder.txt
-lalu buka dan anda akan menemukan 2 Boelan
{
true;valid
Status => Valid
} => menandakan CC anda Valid 
jika 
{false;null
Status => Error
} => menandakan CC anda error alias Salah (dimohon periksa kembali)


Untuk mendapatkan Versi Premium pada tools ini silahkan hubungin developer Tools ini

Dev by:ada wong
