<template>
  <nav class="navbar">
    <div class="navbar-container">
      <div class="logo">MeuSite</div>
      <ul class="nav-links">
        <li><a href="#">Início</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Serviços</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "AppNavbar",
};
</script>

<style scoped>
.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  height: 60px;
  background-color: #2c3e50;
  color: white;
  display: flex;
  align-items:flex-end;
  margin-left: 1px;
  z-index: 1000;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.navbar-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
  display: flex;
  justify-content: space-between;
  width: 100%;
  align-items: center;
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
  margin: 0;
}

.nav-links li a {
  text-decoration: none;
  color: white;
  font-weight: 500;
  transition: color 0.3s;
}

.nav-links li a:hover {
  color: #42b983;
}
</style>
