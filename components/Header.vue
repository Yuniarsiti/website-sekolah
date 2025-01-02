<template>
  <header class="header-school">
    <div class="container-fluid">
      <div class="row align-items-center">
        <!-- Logo -->
        <div class="col-lg-2 col-md-3 col-4 text-center">
          <img src="~/assets/LOGO-SMKN4.png" alt="Logo SMKN 4" class="logo" />
        </div>

        <!-- Informasi Kontak -->
        <div class="col-lg-10 col-md-9 col-8 text-end">
          <div class="contact-info">
            <p>
              <i class="fas fa-map-marker-alt"></i> Jl. Depok, Sukamenak, Purbaratu, Tasikmalaya
            </p>
            <p>
              <i class="fas fa-phone-alt"></i> (0265) 123456
            </p>
            <p>
              <i class="fas fa-envelope"></i> info@smkn4tasik.sch.id
            </p>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap');

/* Header Styling */
.header-school {
  background-color: #0E0E55;
  color: white;
  padding: 15px 0;
}

.logo {
  max-width: 100px;
}

/* Kontak Styling */
.contact-info {
  font-family: "Open Sans", sans-serif;
  font-size: 0.9rem;
  display: flex;  /* Flexbox untuk tata letak horizontal */
  justify-content: flex-end; /* Menempatkan semua item ke kanan */
  align-items: center;
  gap: 30px; /* Jarak antar item */
}

.contact-info p {
  margin: 0;
  display: flex;
  align-items: center;
  gap: 10px;
}

.contact-info i {
  color: #f0eee5; /* Warna ikon */
  font-size: 1.2rem;
}
</style>
