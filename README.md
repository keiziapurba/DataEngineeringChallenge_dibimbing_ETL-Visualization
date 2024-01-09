# Data Engineering Challenge

## Overview

Sebagai seorang Data Engineer, kamu memiliki tugas untuk mengolah data
dari berbagai sumber, melakukan proses Extract, Transform, Load (ETL),
sampai dengan mempresentasikannya dalam bentuk yang dapat digunakan
oleh stakeholder. Kamu akan diberikan challenge dalam beberapa area, yaitu
proses Extract dari berbagai sumber, seperti melakukan Web Scraping dan
mengintegrasikan API, kemudian melakukan Data Cleansing dari data yang
sudah kita kumpulkan, serta melakukan Data Transformation menjadi
format yang sesuai dengan kebutuhan.


*Berikut merupakan tantangan yang harus kamu selesaikan:*
1. Melakukan Web Scraping untuk mendapatkan Gross Domestic Product (GDP) dari
   provinsi - provinsi di Indonesia di tahun 2022. Kamu bisa mendapatkan data
   tersebut dari page berikut:
   https://en.wikipedia.org/wiki/List_of_Indonesian_provinces_by_GDP

2. Setelah data tersimpan dalam bentuk DataFrame, kamu perlu melakukan beberapa
   Data Cleansing.
   
      a. Data yang mengandung null values
      
      b. Membersihkan data yang bukan merupakan data provinsi (data pulau maupun
         negara)
         
      c. Bersihkan juga nama kolom agar lebih mudah digunakan pada proses
         selanjutnya
     

3. Setelah mendapatkan data GDP masing - masing provinsi di Indonesia, kamu perlu
   untuk mendapatkan koordinat latitude dan longitude dari provinsi - provinsi tersebut
   dengan menggunakan Application Programming Interface (API).
   
      a. Kamu bisa menggunakan Geocoding API dari website ini:
         https://opencagedata.com/
         
      b. Setelah sign up dan bereksplorasi dengan API tersebut, kamu bisa
         mendapatkan data latitude dan longitude dari masing - masing provinsi yang
         kita dapatkan dari web scraping.
         

4. Selanjutnya, perlu melakukan Data Transformation dari data
   yang sudah kita dapatkan sebelumnya.
   
      a. Lakukan Data Integration dengan cara menggabungkan data dari berbagai
         sumber menjadi satu.

      b. Lakukan Data Cleansing sekali lagi, sesuaikan tipe kolom sesuai dengan
         kegunaannya.
   
      c. Terakhir, lakukan Data Enrichment dengan menambahkan kolom lat_long yang
       berisi gabungan dari kolom latitude dan longitude
   

6. 🎁 Bonus Challenge 🎁
       
    Buatlah report dengan memanfaatkan data yang sudah kita buat dengan
    melakukan Data Load dan Data Visualization
