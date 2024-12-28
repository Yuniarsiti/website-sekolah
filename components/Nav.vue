</template>
  <header>
    <nav class="navbar">
      <ul class="navbar-menu">
        <li>
          <a href="#home" class="navbar-link">Beranda</a>
        </li>
        <li>
          <a href="#profil" class="navbar-link">Profil</a>
        </li>
        <li>
          <a href="#kontak" class="navbar-link">Kontak</a>
        </li>
        <li>
          <a href="#ekstrakurikuler" class="navbar-link">Ekstrakuikuler</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.navbar {
  background-color: #eaeaf2;
  padding: 10px;
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
  font-size: 18px;
  font-family: 'Open Sans', sans-serif;
}

.navbar-link:hover {
  color: #FFCC00; /* Ubah warna saat hover */
}
</style>
