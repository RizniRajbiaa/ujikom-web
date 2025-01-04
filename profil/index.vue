<template>
  <div class="container-fluid p-0">
    <section class="hero">
      <div class="content">
        <h4>Selamat Datang di Website Resmi</h4>
        <h1 class="fw-semibold">SMKN 4 Tasikmalaya</h1>
      </div>
    </section>
    <!-- Seksi Visi -->
    <section class="info">
      <div class="container">
        <h3 class="text-center">Visi Sekolah</h3>
        <p class="mt-3 text-center">Terwujudnya lulusan yang Cerdas, Aktif, Kompetitif, Adaptif dan Produktif
          berlandaskan Iman dan Takwa (CAKAP BERIMTAK)</p>
        <!-- <h3>Sejarah Singkat</h3> -->
        <!-- <p>SMKN 4 Tasikmalaya berdiri sejak tahun 2010 </p> -->
      </div>
    </section>
    <!--Seksi Sambutan-->
    <div class="sambutan">
      <h3 class="text-center">Sambutan Kepala Sekolah</h3>
      <div class="row justify-content-center">
        <div class="col-md-4">
          <img src="../assets/Kepala Sekolah.png" alt="Kepala Sekolah">
        </div>
        <div class="col-md-8">
          <h4 class="mt-4">Kurniawan S.Pd, M.Pd</h4>
          <h6 class="mt-4">Assalamualaikum Warahmatullahi Wabarakatuh</h6>
          <h6 class="mt-4">Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam
            lindungan-Nya. Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4 Tasikmalaya ini. Kami
            berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh
            tentang sekolah kami sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi
            kemajuan kita bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih
            banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk
            pengembangan ke depan.</h6>
          <h6 class="mt-4">Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak
            dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang
            kita lakukan bermanfaat bagi masyarakat.</h6>
          <h6 class="mt-4">Wassalamu'alaikum Warahmatullahi Wabarakatuh.</h6>
        </div>
      </div>
    </div>
  </div>

  <!-- Seksi Jurusan -->
  <template>
    <div>
      <h2 class="title">Konsentrasi Keahlian</h2>
      <div class="container">
        <!-- Kartu pertama -->
        <div class="card">
          <img src="/assets/img/TKJ.jpeg" alt="Gambar TKJ">
          <div class="card-body">
            <h3>TKJ</h3>
          </div>
        </div>

        <!-- Kartu kedua -->
        <div class="card">
          <img src="/assets/img/PPLG.jpeg" alt="Gambar PPLG">
          <div class="card-body">
            <h3>PPLG</h3>
          </div>
        </div>

        <!-- Kartu ketiga -->
        <div class="card">
          <img src="/assets/img/TSM.jpeg" alt="Gambar TSM">
          <div class="card-body">
            <h3>TSM</h3>
          </div>
        </div>


        <!-- Kartu keempat -->
        <div class="card">
          <img src="/assets/img/TOI.jpeg" alt="Gambar TOI">
          <div class="card-body">
            <h3>TOI</h3>
          </div>
        </div>
      </div>
    </div>
  </template>

  <style scoped>
    /* Gaya dasar untuk kartu jurusan */
    .container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }

    .card {
      background-color: #fff;
      width: 250px;
      border: 1px solid #ddd;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .card-body {
      padding: 15px;
    }

    .card h3 {
      font-size: 20px;
      color: #333;
      margin-bottom: 10px;
    }

    .title {
      text-align: center;
      margin-bottom: 20px;
    }
  </style>
