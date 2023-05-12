<template>
  <header>
    <div class="menu-sinistra">
      <div class="logo">
        <a href="#">
          <img src="../assets/img/images/logo.png" alt="Logo">
        </a>
      </div>
      <nav>
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Services</li>
          <li>Journal</li>
          <li>Contact</li>
        </ul>
      </nav>
    </div>

    <div class="menu-destra">
      <span>1.800.123.4567</span>
      <img src="../assets/img/hover-button1.png" alt="Free Consultation button">
    </div>


  </header>
</template>

<script>

</script>

<style>
header {
  display: flex;
  justify-content: space-between;
}

.menu-sinistra {
  display: flex;
  align-items: center;

}

.menu-destra {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo img {
  width: 60px;

}

nav ul {
  display: flex;
  list-style: none;
}

nav li {
  margin: 20px;
  list-style-type: none;
  list-style: none;

}

nav a {
  color: #000;

}
</style>