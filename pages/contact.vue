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
    <img src="../assets/drive/car-2.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-md-block px-5">
      <p id="cont">CONTACT US</p>
      <p id="support">24/7 support</p>
      </div>
    </div>
  </div>

</section>

<section class="second_sec">
  <div class="container">
    <div class="row">

      <div class="col-md-6 py-5 ">

      <div class="phone d-flex justify-content-center">
      <div class="btn me-3">
        <i class="fas fa-phone-alt"></i>
      </div>

      <p>Phone <br>
        082 000 0000</p>

      </div>

      <div class="email d-flex justify-content-center p-5">
      <div class="btn">
        <i class="fas fa-paper-plane"></i>
        </div>
        <p class="">Email <br>
        email@example.com</p>
      </div>

        <div class="location d-flex justify-content-center">
        <div class="btn me-3">
        <i class="fas fa-map-marker-alt"></i>
        </div>
        <p>Location <br>
        42 Business Rd</p>
        </div>

      </div>

       <div class="col-md-6 py-5 form">
        <p>How Can we help?</p>

        <form>

    <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Name</label>
    <input type="text" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Contact number</label>
    <input type="number" class="form-control" id="exampleInputEmail1">
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1">
  </div>

  <div class="mb-3">
  <label for="text" class="form-label">How can we help?</label>
  <textarea class="form-control" aria-label="With textarea"></textarea>
</div>
  <button type="submit" class="btn">Submit</button>
</form>
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

    <div class="col-md-6 foot">
    <p>MODELS</p>
    <div class="footer-text">LA FERRARI<br>
     MODEL S</div>
    </div>

      <div class="col-md-6 foot">
    <p>MORE</p>
     <div class="footer-text">HOME <br>
      CONTACT US</div>
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

<style lang="scss" scoped>

@import '~./sass/main';
@import 'https://pro.fontawesome.com/releases/v5.10.0/css/all.css';

.first-section{
  text-align: left;
letter-spacing: 1.6px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.87;
}
.second_sec {
  background: var(--black-high-) 0% 0% no-repeat padding-box;
opacity: 1;
}
.fa {
  text-align: left;
font: normal normal medium 18px/21px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
opacity: 0.87;
}
.form p{
  text-align: left;
font: normal normal bold 32px/38px Proxima Nova;
letter-spacing: 1.28px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.87;
}
.navbar {
    cursor: pointer;
    position: absolute;
    width: 100%;
    top:0;
    z-index: 9999;
}
.navbar-nav {
    display: flex;
    text-align: right;
    justify-content: flex-end;
}
#contact {
color: var(--unnamed-color-ff0050);
font: normal normal medium 16px/22px Poppins;
letter-spacing: 0.64px;
}
#home {
color: #FFFFFF;
}
.nav-item {
  letter-spacing: 1.6px;
}
.carousel-caption {
  position: absolute;
  top: 200px;
  color: white;
}
.lead {
  opacity: 0.48;
  letter-spacing: 0.56px;
}
.footer-text{
  opacity: 0.48;
  letter-spacing: 0.56px;
}
#cont {
  text-align: left;
font: normal normal 800 80px/75px Proxima Nova;
letter-spacing: 1.6px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.87;
}
#support {
  text-align: left;
font: normal normal 800 40px/38px Proxima Nova;
letter-spacing: 1.6px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.87;
}
.form-control{
  border: 1px solid #FFFFFFDE;
opacity: 0.87;
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
.phone p{
  text-align: left;
  left: 208px;
font: normal normal medium 18px/21px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
opacity: 0.87;
}
.email p{
text-align: left;
left: 208px;
font: normal normal medium 18px/21px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
opacity: 0.87;
}
.location p {
text-align: left;
left: 208px;
font: normal normal medium 18px/21px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
opacity: 0.87;
}
.footer-text:hover{
  color: var(--unnamed-color-ff0050);
}
.social-links a{
  padding-left: 2%;
  padding-right: 2%;
}
.social-links:hover{
  color: var(--unnamed-color-ff0050);
}
.third_sec{
  background: var(--grey-1000-elevation-) 0% 0% no-repeat padding-box;
}
 @media(max-width:1105px){
#cont {
  font: normal normal 800 48px/75px Proxima Nova;
letter-spacing: 0.96px;
}
.carousel-caption{
   position: absolute;
  top: 130px;
}
 }

  @media(max-width: 414px){
   .carousel-caption{
   position: absolute;
  top: 30px;
}
#cont {
  font: normal normal 800 20px/65px Proxima Nova;
}
#support{
   font: normal normal 800 16px/65px Proxima Nova;
}
  }
</style>
