<template>
  <main>
    <h3 class="sec-titles">Available services</h3>

    <div style="display: flex; border: 1px solid #F0F1F5; border-bottom: white;">
      <div style="flex: 1; border-right: 1px solid #F0F1F5;">
        <h1>Answering phone calls</h1>
        <p>Elementum posuere mauris,ac ultricies eu orci massa at id tincidunt</p>
      </div>
      <div style="flex: 1; border-right: 1px solid #F0F1F5;">
        <h1>Basic Data Entry</h1>
        <p>Accumsan odio id nec mauris, eu, tortorr at. Vitae tincidunt enim quis</p>
      </div>
      <div style="flex: 1; border-right: 1px solid #F0F1F5;">
        <h1>Organizing calendar</h1>
        <p>Elementum blandit erat odio quam pellentesque aliquam faucibus.</p>
      </div>
      <div style="flex: 1;">
        <h1>Booking Travels</h1>
        <p>Est dignissim ipsum tellus,henderit ac aliquam eu vel blandit ac amet ut ut </p>
      </div>
    </div>
    <section>
      <div class="container">
        <div class="image">
          <img src="../assets/img/images/info-bg.png" alt="">
        </div>
        <div class="text">
          <h1 style="color: #0D1168;">Find the ultimate virtual assistant for your business</h1>
          <p>Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula.</p>
          <button style="background-color: #F86636 ; width:200px;"><a
              href="https://avada.website/virtual-assistant/about-me/">What is
              a VA exactly?</a></button>
        </div>
      </div>

    </section>
  </main>
</template>

<script>

</script>

<style>
.sec-titles {
  color: #F86636;
  margin: 40px;
}

section {
  padding: 30px 0;
  min-height: 400px;
}

section .container {
  display: flex;
}

section .container .image {
  width: 60%;
  margin-top: 200px;
}

section .container .text {
  width: 40%;
  display: flex;
  align-items: center;


}

section .container .text h1 {
  font-size: 30px;
}
</style>