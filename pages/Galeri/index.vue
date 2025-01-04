
<template>
    <div class="gallery-container">
        <div class="gallery-item">
            <img src="/assets/img/Praktek-Safety-Riding.jpg" alt="Kegiatan 1">
            <p>Kegiatan Ekstrakulikuler Safety Riding ( Astra Honda )</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/Expo-Creanova.jpg" alt="Kegiatan 2">
            <p>Expo Creanova sebagai ajang adu kreativitas dan inovasi</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/upacara.jpeg" alt="Kegiatan 3">
            <p>kegiatan upacara bendera setiap hari senin</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/Iduka.jpg" alt="Kegiatan 5">
            <p>Koneksikan Iduka dengan Pencari Kerja</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/pd.webp" alt="Kegiatan 6">
            <p>Perisai Diri Ikuti UKT Periode 72</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/peresmian-SRL.jpg" alt="Kegiatan 7">
            <p>Astra Honda Resmikan Safety Riding</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/pramuka.jpg" alt="Kegiatan 8">
            <p>Kegiatan Ekstrakulikuler Pramuka</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/simoring-bsi.jpeg" alt="Kegiatan 9">
            <p>Aplikasi SIMORING, Solusi Kekinian dari Universitas BSI</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/pelaksanaa-Ukbi.jpeg" alt="Kegiatan 10">
            <p>Guru di SMKN 4 Tasikmalaya melaksanakan UKBI Adaptif Merdeka</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/job fair-2023.jpg" alt="Kegiatan 11">
            <p>Gelar Job Fair 2023, Harapkan Angka Pengangguran di Tasikmalaya Berkurang</p>
        </div>
        <div class="gallery-item">
            <img src="/assets/img/kampanye-keselamatan-berkendara.jpg" alt="Kegiatan 12">
            <p>Gelar pelatihan kampanye keselamatan berkendara bersama (astra honda)</p>
        </div>
    </div>
</template>

    <style scoped>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .gallery-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
            padding: 20px;
        }
        .gallery-item {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .gallery-item img {
            width: 100%;
            height: auto;
            display: block;
        }
        .gallery-item:hover {
            transform: scale(1.05);
        }
        .gallery-item p {
            padding: 15px;
            text-align: center;
            font-size: 16px;
            color: #333;
            background-color: #fff;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>