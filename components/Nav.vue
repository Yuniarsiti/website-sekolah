<template>
  <div class="container-fluid p-0">
    <nav class="navbar justify-content-center">
      <ul class="navbar-menu m-1">
        <li>
          <nuxt-link to="/" class="navbar-link active">Beranda</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/profil" class="navbar-link">Profil</nuxt-link>
        </li>
        <li>
          <nuxt-link to="" class="navbar-link">Kontak</nuxt-link>
        </li>
        <li>
          <nuxt-link to="" class="navbar-link">Ekstrakurikuler</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style scoped>
.navbar {
  background-color: #eaeaf2;
}

.navbar-menu {
  display: flex;
  justify-content: center;
  list-style: none;
}

.navbar-menu li {
  margin: 0 15px;
}

.navbar-link {
  color: rgb#0E0E55;
  text-decoration: none;
  font-size: 15px;
  font-family: 'Open Sans', sans-serif;
}

.navbar-link:hover {
  color: #FFCC00; /* Ubah warna saat hover */
}
</style>
