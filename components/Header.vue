<template>
    <div class="head">
        <div class="title">
            <img src="/assets/logo-smkn4.png" alt="logo">
            <h2>SMKN Tasikmalaya</h2>
        </div>
        <div class="info">
            <span>Lokasi</span>Purbaratu, Tasikmalaya
        </div>
    </div>
    <ul class="nav justify-content-center">
        <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Beranda</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Profil
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Sejarah</a></li>
            <li><a class="dropdown-item" href="#">Visi Misi</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Estrakurikuler
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Olahraga</a></li>
            <li><a class="dropdown-item" href="#">Non Olahraga</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Kurikulum
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Kompetensi Keahlian</a></li>
            <li><a class="dropdown-item" href="#">Visi Misi</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Siswa
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Sejarah</a></li>
            <li><a class="dropdown-item" href="#">Visi Misi</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
      </ul>
      

    </div>
  </div>
</nav>
    </ul>
    
<div class="garis"></div>
</template>
<style>
.garis{
    border-bottom: 1px solid #ccc;
}
.head{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: nowrap;
    padding: 20px 20px;
    border-bottom: 1px solid #ccc;
}
.title{
    display: flex;
    align-items: center;

}
.title h2{
    font-size: 29px;
}
.title img{
    height: 60px;
}
.info{
    font-size: 24px;
    color: #8d8585;
}
.info span{
    font-size: 20px;
    display: block;
    color: black;
}
</style>