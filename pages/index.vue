<template>
<main>
<section class="first-section">
  <nav class="navbar navbar-expand-lg navbar-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img src="../assets/drive/logo.svg"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
         <NuxtLink to="/#" class="nav-link" id="home">Home</NuxtLink>
        </li>
        <li class="nav-item">
        <NuxtLink to="/contact" class="nav-link" id="contact">Contact Us</NuxtLink>
        </li>
      </ul>
    </div>
  </div>
</nav>

<div class="carousel-inner">
    <div class="carousel-item">
    <img src="../assets/drive/hero-home.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-md-block">
      <p>Goosebumps</p>
        <p>Come Standard</p>
        <p>Discover the benefits of DRIVECLUB Trade-in and get a free vehicle evaluation</p>
        <div class="btn btn-primary">
        <NuxtLink to="/contact">Contact Us</NuxtLink>
        </div>
      </div>
    </div>
  </div>

</section>

<section class="second_sec">
<div class="container-fluid">
  <div class="row">
    <div class="col-md-4 text-center text">
        <p class="new">
  New Range
  </p>
  <p class="la">
 LA FERRARI
  </p>
  <NuxtLink to="/about" class="learn">Learn More</NuxtLink>
    </div>

    <div class="col-md-8 ferrari">
    <img src="../assets/drive/car-1.jpg" alt="...">

    </div>
    
  </div>
</div>

<div class="container-fluid">
  <div class="row">
    <div class="col-md-8 model">
        <img src="../assets/drive/car-2.jpg" alt="...">
    </div>

    <div class="col-md-4 text-center text">
          <p class="new">
  New Range
  </p>
  <p class="la">
MODEL S
  </p>
  <NuxtLink to="/about" class="learn">Learn More</NuxtLink>
    </div>
  </div>
</div>

</section>

<section class="third_sec">
  <!-- footer -->
<footer class="p-5 text-light position-relative" id="contact">
<div class="container">
  <div class="row">
    <div class="col-md-6">

    <img src="../assets/drive/logo.svg">
      <p class="lead">&copy; Driveclub. All rights reserved.</p>

 <div class="social-links px-3">
        <a href="..."> <img src="../assets/drive/facebook.svg"></a>
        <a href="..."> <img src="../assets/drive/instagram.svg" alt=""></a>
        <a href="..."> <img src="../assets/drive/twitter.svg"></a>
          <a href="..."> <img src="../assets/drive/linkedin.svg"></a>
            <a href="..."> <img src="../assets/drive/youtube.svg"></a>
</div>
    </div>

     <div class="col-md-6">
      <div class="container">
  <div class="row">

    <div class="col-md-6">
    MODELS
    <p>LA FERRARI</p>
     <p>MODEL S</p>
    </div>

      <div class="col-md-6">
    MORE
     <p>HOME</p>
      <p>CONTACT US</p>
    </div>

  </div>
</div>
    </div>

  </div>
</div>

    </footer>

    </section>
</main>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang='scss' scoped>
@import '~./sass/main';

.navbar {
    cursor: pointer;
    position: absolute;
    width: 100%;
    top:0;
    z-index: 9999;
}
.lead {
  opacity: 0.48;
  letter-spacing: 0.56px;
}

.navbar-nav {
    display: flex;
    text-align: right;
    justify-content: flex-end;
}
#home {
color: var(--unnamed-color-ff0050);
font: normal normal medium 16px/22px Poppins;
letter-spacing: 0.64px;
}
#contact {
color: #FFFFFF;
}
.nav-item {
  letter-spacing: 1.6px;
}
#goose {
  top: 172px;
}
.learn {
color: var(--unnamed-color-ff0050);
text-align: left;
font: normal normal normal 16px/25px Poppins;
letter-spacing: 0.64px;
opacity: 1;
text-decoration: none;
}
.new{
text-align: left;
font: normal normal normal 18px/75px Proxima Nova;
letter-spacing: 0.72px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.6;
}
.la {
font-family: Proxima Nova;
text-align: left;
font: normal normal 800 56px/75px Proxima Nova;
letter-spacing: 1.12px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.87;
}
.ferrari img {
  width: 100%;
}
.model img {
  width: 100%;
}
.text{
padding-top: 15%;
}
.btn {
border: 2px solid var(--unnamed-color-ff0050);
background: #FF00504D 0% 0% no-repeat padding-box;
border: 2px solid #FF0050;
opacity: 1;
font: normal normal medium 18px/21px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
text-decoration: none;
}
.carousel-caption {
  position: absolute;
  top: 200px;
  color: white;
}
.second_sec{
  background: var(--black-high-) 0% 0% no-repeat padding-box;
}
.second_sec .nav-link {
  letter-spacing: 0.64px;
  color: var(--unnamed-color-ff0050);
}
.second_sec p{
  text-transform: uppercase;
opacity: 0.6;
color: #FFFFFF;
}
.social-links a{
  padding-left: 2%;
  padding-right: 2%;
}
.third_sec{
  background: var(--grey-1000-elevation-) 0% 0% no-repeat padding-box;
}
</style>
