<template>
    <nav class="navbar navbar-expand-lg bg-black">
        <div class="container">
            <img src="/assets/img/LOGO-SMK.png" alt="logo smk" width="100px" height="100px">
            <a class="navbar-brand" href="#">SMKN 4 TASIKMALAYA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'index' }" to="/">Beranda</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Ekstrakulikuler' }" to="/Ekstrakulikuler">Ekstrakulikuler</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Fasilitas' }" to="/Fasilitas">Fasilitas</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Galeri' }" to="/Galeri">Galeri</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Jurusan' }" to="/Jurusan">Jurusan</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Profil' }" to="/Profil">Profil</NuxtLink>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    </template>
    
    <script setup>

    
    const route = useRoute()

    
    console.log(route.name)
    </script>