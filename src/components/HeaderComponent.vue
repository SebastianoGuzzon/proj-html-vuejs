<template>
	<body>
		<nav class="navbar">
			<div class="logo">
				<img src="../assets/img/images/logo.png" alt="">
			</div>
			<ul class="nav">
				<li><a href="https://avada.website/virtual-assistant/"><span>Home</span></a></li>
				<li><a href="https://avada.website/virtual-assistant/about-me/"><span>About</span></a></li>
				<li><a href="https://avada.website/virtual-assistant/my-services/"><span>Services</span></a><button></button>
				<li><a href="https://avada.website/virtual-assistant/journal/"><span>Journal</span></a></li>
				<li><a href="https://avada.website/virtual-assistant/contact-me/"><span>Contact</span></a></li>
				</li>
			</ul>
			<div class="nav-right">
				<a href="tel:1-800-123-4567"><i></i><span>1.800.123.4567</span></a>
				<button style="background-color: #FFFFFF; border-radius: 6px; height: 50px"><a
						href="https://avada.website/virtual-assistant/contact-me/" style="color: #030545;"><span>Get
							a free
							consultation</span></a></button>
			</div>
		</nav>
		<header class="header">

			<div class="header-content">
				<h1>Independent professional who works remotely to help with your business.</h1>
				<p>Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.</p>
				<button style="background-color: white; border-radius: 2px; width: 150px;
				height: 40px;">Buy Avada now</button>
			</div>


		</header>
	</body>
</template>

<script>

</script>

<style>
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

body {
	margin: 0;
	padding: 0;
	font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.navbar {
	margin-top: 20px;
	display: flex;
	align-items: center;
	justify-content: space-between;
	background-color: #0D1168;
	color: #fff;
	height: 60px;
	padding: 0 20px;
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	z-index: 2;
}

.logo {
	font-size: 24px;
	font-weight: bold;
}

.nav {
	display: flex;
	list-style: none;
	margin: 0;
	padding: 0;
}

.nav li {
	margin: 0 10px;
}

.nav a {
	color: #fff;
	text-decoration: none;
	font-size: 18px;
}

.nav-right {
	display: flex;
	align-items: center;
}

.nav-right a {
	margin: 0 10px;
	font-size: 16px;
	text-decoration: none;
	color: white;
}

.header {
	background-color: #0D1168;
	height: 500px;
	position: relative;
}

.overlay {
	background-color: rgba(0, 0, 0, 0.5);
	height: 100%;
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	z-index: 1;
}

.header-content {
	margin: 0;
	position: absolute;
	top: 50%;
	left: 38%;
	transform: translate(-50%, -50%);
	text-align: center;
	z-index: 2;
	width: 35%;
}

.header-content h1 {
	color: #fff;
	font-size: 45px;
	margin: 0;

}

.header-content p {
	color: #fff;
	font-size: 19px;
	padding: 0 3vw;
}
</style>