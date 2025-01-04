<template>
    <div>
        <header>
            <h1>Daftar Ekstrakurikuler SMKN 4 Tasikmalaya</h1>
        </header>
        
        <nav>
            <a href="#olahraga">Olahraga</a>
            <a href="#seni">Seni</a>
            <a href="#akademik">Akademik</a>
            <a href="#lainnya">Lainnya</a>
        </nav>

        <div class="container">
            <h2 id="olahraga">Ekstrakurikuler Olahraga</h2>
            <ul class="ekstrakurikuler-list">
                <li>Sepak Bola</li>
                <li>Basket</li>
                <li>Volleyball</li>
                <li>Badminton</li>
                <li>Renang</li>
            </ul>

            <h2 id="seni">Ekstrakurikuler Seni</h2>
            <ul class="ekstrakurikuler-list">
                <li>Pramuka</li>
                <li>Paduan Suara</li>
                <li>Tari</li>
            </ul>

            <h2 id="akademik">Ekstrakurikuler Akademik</h2>
            <ul class="ekstrakurikuler-list">
                <li>Komputer dan IT</li>
            </ul>

            <h2 id="lainnya">Ekstrakurikuler Lainnya</h2>
            <ul class="ekstrakurikuler-list">
                <li>Pramuka</li>
                <li>PLH</li>
                <li>Paskibra</li>
                <li>PKS</li>
                <li>Organisasi Siswa Intra Sekolah (OSIS)</li>
                <li>Palang Merah Remaja (PMR)</li>
                <li>Ikatan Remaja Masjid (IRMA)</li>
            </ul>
        </div>
        
    </div>
</template>

<style scoped>
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f9;
        margin: 0;
        padding: 0;
        
        /* Menggunakan Flexbox untuk pusatkan konten */
        display: flex;
        justify-content: center; /* Menyusun konten secara horizontal di tengah */
        align-items: center; /* Menyusun konten secara vertikal di tengah */
        height: 100vh; /* Menggunakan seluruh tinggi layar */
        flex-direction: column;
    }

    header {
        background-color: #ffffff;
        color: white;
        padding: 20px 0;
        text-align: center;
        width: 100%; /* Pastikan header memenuhi lebar layar */
    }

    header h1 {
        margin: 0;
        font-size: 32px;
    }

    nav {
        background-color: #333;
        overflow: hidden;
        width: 100%;
        text-align: center;
    }

    nav a {
        color: white;
        padding: 14px 20px;
        text-decoration: none;
        display: inline-block;
    }

    nav a:hover {
        background-color: #ddd;
        color: black;
    }

    .container {
        margin: 20px;
        padding: 20px;
        background-color: white;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        width: 80%; /* Lebar konten bisa diatur sesuai kebutuhan */
        max-width: 1000px; /* Maksimal lebar konten */
    }

    h2 {
        font-size: 24px;
        color: #333;
        margin-bottom: 10px;
        padding-bottom: 5px;
    }

    .ekstrakurikuler-list {
        list-style-type: none;
        padding: 0;
    }

    .ekstrakurikuler-list li {
        background-color: #fff;
        margin: 10px 0;
        padding: 15px;
        border: 1px solid #ddd;
        border-radius: 5px;
        transition: background-color 0.3s ease, transform 0.3s ease;
    }

    .ekstrakurikuler-list li:hover {
        background-color: #f0f0f0;
        transform: scale(1.02);
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

    /* Responsif untuk layar kecil */
    @media (max-width: 768px) {
        header h1 {
            font-size: 24px;
        }

        nav a {
            padding: 10px;
            font-size: 14px;
        }

        .container {
            margin: 10px;
        }

        h2 {
            font-size: 20px;
        }

        .ekstrakurikuler-list li {
            font-size: 14px;
        }
    }
</style>

