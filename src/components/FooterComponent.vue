<template>
  <footer>
    <div class="container">
      <div class="footer-content">
        <div class="left-section">
          <img src="../assets/img/images/logo.png" alt="Logo">
          <nav>

            <ul class="nav">
              <li><a href="https://avada.website/virtual-assistant/"><span>Home</span></a></li>
              <li><a href="https://avada.website/virtual-assistant/about-me/"><span>About</span></a></li>
              <li><a
                  href="https://avada.website/virtual-assistant/my-services/"><span>Services</span></a><button></button>
              <li><a href="https://avada.website/virtual-assistant/journal/"><span>Journal</span></a></li>
              <li><a href="https://avada.website/virtual-assistant/contact-me/"><span>Contact</span></a></li>
              </li>
            </ul>

          </nav>
        </div>
        <div class="right-section">
          <a href="tel:1-800-123-4567"><i class=""></i>1.800.123.4567</a>
          <button class="btns-style-dark"><strong>Buy Avada now</strong> </button>

        </div>
      </div>
    </div>
    <div class="footer-content2">
      <h1>Independent professional who works remotely to help with your business.</h1>
      <button class="btns-white" style=""><a style="color: #0D1168; text-decoration: none;
              font-size: 1.1em;" href="https://avada.website/virtual-assistant/about-me/">
          <strong>What
            is
            a VA exactly?</strong></a></button>
      <p> &copy; Copyright 2012 - 2023 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
    </div>

  </footer>
</template>

<script>

</script>

<style>
footer {
  background-color: #0D1168;
  padding: 20px 0;
  text-align: center;
  min-height: 600px;
}

.footer-content2 {
  color: white;
  width: 50%;
  margin-top: 80px;
  margin-left: 100px;

}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100% - 300px);
  margin-top: 100px;

}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 80%;
}

.left-section {
  display: flex;
  align-items: center;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin-right: 10px;
}

nav ul li:last-child {
  margin-right: 0;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

.right-section {
  text-align: right;
}

.right-section a {
  text-decoration: none;
  color: white;
}

.btns-style-dark {
  background-color: #030545;
  padding-left: 20px;
  border-radius: 5px;
  width: 200px;
  height: 55px;
  border: none;
  color: white;
}

.btns-white {
  margin-top: 30px;
  background-color: white;
  width: 200px;
  height: 50px;
  border-radius: 2px;
  border: none;
}
</style>