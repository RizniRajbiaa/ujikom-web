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
          <nuxt-link to="/galeri" class="navbar-link">Galeri</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/ekstrakulikuler/" class="navbar-link">Ekstrakulikuler</nuxt-link>
        </li>
        <li>
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
  font-family: "sans-serif";
}

.navbar-link:hover {
  color: #003cff;
  /* Ubah warna saat hover */
}
</style>