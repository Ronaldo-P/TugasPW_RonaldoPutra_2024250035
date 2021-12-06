<template>
  <div class="hello">
    <body data-bs-spy="scroll" data-bs-target=".navbar" data-bs-offset="50">

<nav class="navbar navbar-expand-sm bg-primary navbar-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="mdp.png" alt="MDP" width="60px">
      Multi Data Palembang
    </a>
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="#login">Masuk</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#register">Daftar</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#about">About Me</a>
      </li>
    </ul>
  </div>
</nav>

<div id="section1" class="container-fluid bg-danger text-white" style="padding:100px 30px;">
  <h1>Ronaldo Putra</h1>
  <hr>
  <div class="row">
    <p></p>
  <div class="col" ><center>
    <img src="ronaldo.jfif" class="rounded-circle" alt="Cinque Terre" width="190" height="170"> 
    </center></div>
    
  <div class="col">
    <li>Perkenalkan Ronaldo Putra dengan NPM 2024250035</li>
    <li>Seorang Mahasiswa MDP </li>
    <li>Merupakan anak ke-3 dari 4 bersaudara</li>
    <li>Bertempat tinggal di Palembang</li>
  </div>
  <p></p>
  <p></p>
  <p></p>
  <p>    *Hai, nama saya Ronaldo Putra biasa dipanggil Aldo atau Dodo. Saya merupakan seorang mahasiswa MDP yang mengambil jurusan TI/IF dengan NPM 2024250035, alasan saya sendiri memilih jurusan TI dikarenakan saya tertarik dengan ilmu komputer dan berharap untuk kedepannya bisa menggunakan ilmu komputer dengan baik sehingga mendapat pekerjaan yang diinginkan.
  </p>
</div>
</div>

<div id="section2" class="container-fluid bg-warning" style="padding:100px 30px;">
  <h1>Data Diri</h1>
  <hr>
  <div class="row">
    
    <div class="col">
      <h5><u>Biodata</u></h5>
      <li>Lahir di Palembang, 2 Juli 2002</li>
      <li>Anak ke-3 dari 4 bersaudara</li>
      <li>Tinggal di Jl. Slamet Riady No 255</li>
      <li>Beragama Buddha</li>
      <li>Jenis Kelamin Laki-laki</li>
      <li>Merupakan Mahasiswa MDP</li>
      <li>Bekerja di Kedai B217an</li>
    </div>

    <div class="col">
        <h5><u>Pendidikan</u></h5>
        <li>SD SUMSEL JAYA</li>
        <li>SMP METHODIST 2</li>
        <li>SMK METHODIST 2</li>
        <li>UNIVERSITAS MDP</li>
    </div>

    <div class="col">
      <h5><u>Sosial Media</u></h5>
      <li><img src="ig.png" width="20px"> @ronal2pz</li>
      <li><img src="fb.png" width="20px"> Ronaldo Putra</li>
    </div>
  </div>
  </div>

<div id="section3" class="container-fluid bg-secondary text-white" style="padding:70px 30px;">
  <h1>Kesimpulan</h1>
  <hr>
  <p></p>
  <p></p>
  <p>
      *Hai,Salam kenal!
    Saya adalah Ronaldo Putra dengan NPM 2024250035, anak ke-3 dari 4 bersaudara yang tinggal di Lorong Kemas 1 (Kuto),Hobi saya sendiri adalah menonton film movie/series dan bermain game. Saya bekerja di Kedai B217an yang berada di Bangau sebagai Waitress pada shift pagi dan pulang siang sehingga bisa langsung melanjutkan kuliah pada malamnya. jadi, , kegiatan saya bukan hanya seorang pelajar namun juga seorang pekerja.
    Terima kasih.
  </p>
  </div>

</body>
  </div>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
