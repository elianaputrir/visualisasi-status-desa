<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->





<!-- Pendahuluan -->
<details>
  <summary>Pendahuluan</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Status Desa Berdasarkan Indeks Desa Membangun (IDM) 2021 Provinsi Kalimantan Barat 

![Product Name Screen Shot][product-screenshot]

Indeks Desa Membangun (IDM) adalah indeks yang dibuat oleh Kementrian Desa, Pembangunan Daerah Tertinggal, dan Transmigrasi Republik Indonesia untuk mengetahui status perkembangan setiap desa dari aspek ekonomi, ekologi dan sosial. Pembuatan IDM bertujuan untuk menjadi alat ukur pemerataan pembangunan di seluruh wilayah Indonesia. Indeks ini dapat dikelompokkan menjadi 4 kategori status yaitu tertinggal, berkembang, maju ,dan mandiri.

Provinsi Kalimantan Barat dipilih sebagai fokus penelitian adalah karena adanya banyak potensi ekonomi yang mampu dimanfaatkan untuk pembangunan daerah, tapi justru memiliki pertumbuhan ekonomi dan pembangunan manusia yang masih dibawah rata-rata. 

Sehingga, digunakan Tableau sebagai software visualisasi untuk memberikan visualisasi yang dapat memberikan cara eksplorasi yang cepat dan mudah.

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- VISUALISASI -->
## Langkah Visualisasi

Berikut ini adalah langkah-langkah untuk melakukan visualisasi data Status Desa berdasarkan Indeks Desa Membangun dengan Tableau.

1. Load dataset ke tableau   
   Data dikumpulkan dari website resmi satu data pemerintah yaitu
   http://data.kalbarprov.go.id/dataset/status-desa-berdasarkan-indeks-desa-membangun-menurut-kabupaten-kota-se-kalbar-tahun-2021/resource/cc38669d-da6d-439d-bb6e-d70410180632

   Karena data merupakan hasil dari data publikasi, maka tidak terdapat missing value dengan asumsi daerah yang tidak ada datanya adalah daerah perkotaan dan tidak termasuk dalam objek penelitian yaitu pedesaan.

   ![step1-one-screen-shoot][step-1-screenshoot]

2. Load shapefile peta desa Kalimantan Barat
   File shapefile didapat dari http://geospasial.kalbarprov.go.id/pencarian.html?kategori=Batas%20Wilayah&keyword=&walidata=&bbox=

    ![step-two-screen-shoot][step-2-screenshoot]

3. Memasukkan variabel status desa, nama desa dan nilai idm
   ![step-three1-screen-shoot][step-3-1-screenshoot]

   Pallete warna yang digunakan adalah red-gold       
   ![step-three2-screen-shoot][step-3-2-screenshoot]
  
4. Menambahkan judul dari visualisasi            
   ![step-four-screen-shoot][step-4-screenshoot]

<p align="right">(<a href="#top">back to top</a>)</p>

Sehingga hasil dari visualisasi dari data Status Desa berdasarkan Indeks Desa Membangun (IDM) Tahun 2021 di Provinsi Kalimantan Barat adalah sebagai berikut:

![final-choropleth][final-choropleth]

Jika, kursor diarahkan pada satu daerah dari desa akan menampilkan detail dari desa beserta dengan status desanya.

![hover][hover]


<!-- Author -->
## Author

Eliana Putri Ramadani (221911174) - 3SD2 - 221911174@gmail.com

<p align="right">(<a href="#top">back to top</a>)</p>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/idm.png
[step-1-screenshoot]: images/step%201.jpeg
[step-2-screenshoot]: images/step%202.jpeg
[step-3-1-screenshoot]: images/step%203-1.jpeg
[step-3-2-screenshoot]: images/step%203-2.jpeg
[step-4-screenshoot]: images/step%204.jpeg
[final-choropleth]: images/choropleth.jpeg
[hover]: images/hover.jpeg