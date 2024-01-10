# Data Engineering Challenge

## Overview

### 🔊 Sebagai seorang **Data Engineer**, kamu memiliki tugas untuk mengolah data dari berbagai sumber, melakukan proses **Extract, Transform, Load (ETL)**,sampai dengan mempresentasikannya dalam bentuk yang dapat digunakan oleh stakeholder. Kamu akan diberikan challenge dalam beberapa area, yaitu proses **Extract** dari berbagai sumber, seperti melakukan **Web Scraping** dan mengintegrasikan **API**, kemudian melakukan **Data Cleansing** dari data yang sudah kita kumpulkan, serta melakukan **Data Transformation** menjadi format yang sesuai dengan kebutuhan.
---

### Berikut merupakan tantangan yang harus kamu selesaikan:
1. Melakukan **Web Scraping** untuk mendapatkan Gross Domestic Product (GDP) dari
   provinsi - provinsi di Indonesia di tahun 2022. Kamu bisa mendapatkan data
   tersebut dari page berikut:
   https://en.wikipedia.org/wiki/List_of_Indonesian_provinces_by_GDP

<img width="578" alt="Screenshot 2024-01-10 at 09 57 04" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/021fe991-bea7-45a4-bbee-c49172b7bd3d">

   

2. Setelah data tersimpan dalam bentuk DataFrame, kamu perlu melakukan beberapa
   **Data Cleansing**.
   
   a. Data yang mengandung **null values**
   
<img width="556" alt="Screenshot 2024-01-10 at 09 57 35" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/eaa0c2f5-249c-4dd7-a438-07a761372e06">

   b. Membersihkan data yang bukan merupakan data provinsi (data pulau maupun
      negara)

<img width="551" alt="Screenshot 2024-01-10 at 09 57 57" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/e409a241-ae63-45e1-afe0-e8934e04283f">


   c. Bersihkan juga nama kolom agar lebih mudah digunakan pada proses
     selanjutnya

<img width="551" alt="Screenshot 2024-01-10 at 09 58 22" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/bbd46dae-aeda-4a02-b757-be86d82c9673">

     

3. Setelah mendapatkan data GDP masing - masing provinsi di Indonesia, kamu perlu
   untuk mendapatkan koordinat latitude dan longitude dari provinsi - provinsi tersebut
   dengan menggunakan **Application Programming Interface (API)**.
   
   a. Kamu bisa menggunakan Geocoding API dari website ini:
      https://opencagedata.com/


<img width="514" alt="Screenshot 2024-01-10 at 09 58 42" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/be5c6cae-4447-4ac0-bdce-07a8190e2fcc">


   b. Setelah sign up dan bereksplorasi dengan API tersebut, kamu bisa
      mendapatkan data latitude dan longitude dari masing - masing provinsi yang
      kita dapatkan dari web scraping.


<img width="550" alt="Screenshot 2024-01-10 at 09 59 46" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/d5a57ddb-08f5-4439-977a-d7afa800c487">


4. Selanjutnya, perlu melakukan Data Transformation dari data
   yang sudah kita dapatkan sebelumnya.
   
   a. Lakukan Data Integration dengan cara menggabungkan data dari berbagai
      sumber menjadi satu.


<img width="553" alt="Screenshot 2024-01-10 at 10 00 31" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/86c8b636-c5a9-43e8-8b46-c2c74e31d7ba">


   b. Lakukan Data Cleansing sekali lagi, sesuaikan tipe kolom sesuai dengan
      kegunaannya.


<img width="278" alt="Screenshot 2024-01-10 at 10 00 55" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/4e8997e7-8988-4225-9bad-3837675d8ee8">

   
   c. Terakhir, lakukan Data Enrichment dengan menambahkan kolom `lat_long` yang
      berisi gabungan dari kolom `latitude` dan `longitude`


<img width="553" alt="Screenshot 2024-01-10 at 10 01 15" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/bd093741-a1d2-49ae-85fc-c1017dbfcd0f">

   

5. 🎁 **Bonus Challenge** 🎁
       
    Buatlah report dengan memanfaatkan data yang sudah kita buat dengan
    melakukan Data Load dan Data Visualization

<img width="534" alt="Screenshot 2024-01-10 at 10 01 55" src="https://github.com/keiziapurba/DataEngineeringChallenge_dibimbing_ETL-Visualization/assets/91368463/9e79c9fb-23c2-4653-a371-c1168890f8b9">

