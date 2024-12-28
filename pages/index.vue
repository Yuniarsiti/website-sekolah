<template>
  <section class="hero">
    <div class="content">
      <h1>Selamat Datang di Website Sekolah</h1>
      <p>SMKN 4 Tasikmalaya</p>
    </div>
  </section>

  <!-- Seksi Visi, Misi, dan Sejarah -->
  <section class="info">
    <div class="container">
      <h2>Visi dan Misi</h2>
      <p>Visi: Terwujudnya lulusan yang cerdas, aktif, kompetitif, adaptif, dan produktif berlandaskan iman dan takwa.</p>
      <p>Misi: Mempersiapkan Sumber Daya Manusia yang Berkualitas di Bidang Teknologi dan Kejuruan.</p>

      <h3>Sejarah Singkat</h3>
      <p>SMKN 4 Tasikmalaya berdiri sejak tahun 2010 </p>
    </div>
  </section>

  <!-- Seksi Jurusan -->
  <section class="departments">
    <div class="container">
      <h2>Konsentrasi Keahlian</h2>
      <div class="department-list">
        <!-- Jurusan 1 -->
        <div class="department">
          <img src="~/assets/tkjt.png" alt="Teknik jaringan komputer" class="department-logo"/>
          <h3>Teknik Komputer dan Jaringan</h3>
        </div>
        <!-- Jurusan 2 -->
        <div class="department">
          <img src="~/assets/pplg.png" alt="Pengembangan Perangkat Lunak Gim" class="department-logo"/>
          <h3>Pengembangan Perangkat Lunak Gim</h3>
        </div>
        <!-- Jurusan 3 -->
        <div class="department">
          <img src="~/assets/tbsm.png" alt="Teknik Sepeda Motor" class="department-logo"/>
          <h3>Teknik Sepeda motor</h3>
        </div>
        <!-- Jurusan 4 -->
        <div class="department">
          <img src="~/assets/toi.png" alt="Teknik Otomasi Industri" class="department-logo"/>
          <h3>Teknik Otomasi Industri</h3>
        </div>
        <!-- Jurusan 5 -->
        <div class="department">
          <img src="~/assets/dkv.png" alt="Desain Komunikasi Visual" class="department-logo"/>
          <h3>Desain Komunikasi Visual</h3>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  background-image: url('~/assets/smkn44.jpg');
  background-size: cover;
  background-position: center;
  height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #ebebf4;
  text-align: center;
}

.info {
  background-color: #f8f8f8;
  padding: 30px;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

h2, h3 {
  color: #0E0E55;
}

p {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #150e0e;
}

/* Styling untuk bagian jurusan */
.departments {
  background-color: #f0f0f0;
  padding: 50px 0;
}

.department-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 kolom untuk bagian atas */
  gap: 20px;
  margin-bottom: 20px;
}

.department-list > .department:nth-child(4),
.department-list > .department:nth-child(5) {
  grid-column: span 1; /* Membuat jurusan ke-4 dan ke-5 berdampingan */
}

.department {
  text-align: center;
  background-color: #fff7f7;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.department-logo {
  width: 100px;
  height: 100px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 15px;
}

.department h3 {
  color: #0E0E55;
  font-size: 1.2rem;
}

.department p {
  font-size: 1rem;
  color: #777;
}
</style>
