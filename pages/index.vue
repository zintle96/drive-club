<template>
<main>
<section>
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
          <NuxtLink to="/contact" class="nav-link">Contact Us</NuxtLink>
        </li>
      </ul>
    </div>
  </div>
</nav>

<div class="content">
  <img src="../assets/drive/hero-home.jpg" class="d-block w-100"/>

   <div class="content-caption d-md-block">
      <p class="goose">Goosebumps</p>
      <p class="come">Come standard</p>
      <p class="para">Discover the benefits of DRIVECLUB Trade-in and get a free vehicle evaluation</p>

<button type="button" class="btn">Contact Us</button>
  </div>

</div>
</section>

<section>
 <div class="container">
   <div class="row">
     <div class="col-md-6 new">

      </div>

     <div class="col-md-6">
<img src="../assets/drive/car-1.jpg" class="w-100">

  </div>
    </div>

 </div>

</section>
</main>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang='scss'>

.navbar {
  position: absolute;
  top: 0;
  width: 100%;
  z-index: 9999
}
#home {
  color: #FF0050;
}
.new {
  background: #171B1E 0% 0% no-repeat padding-box;
opacity: 1;
}
.btn {
top: 419px;
left: 140px;
width: 156px;
height: 48px;
border: 2px solid var(--unnamed-color-ff0050);
background: #FF00504D 0% 0% no-repeat padding-box;
border: 2px solid #FF0050;
opacity: 1;
font: normal normal medium 18px/21px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
}
.navbar-brand {
top: 36px;
left: 120px;
width: 148px;
height: 16px;
background: 0% 0% no-repeat padding-box;
opacity: 1;
}

.nav-link {
  text-align: center;
font: normal normal 300 16px/22px Poppins;
letter-spacing: 0.64px;
color: #FFFFFF;
opacity: 0.87;
text-transform: uppercase;
top: 32px;
left: 1223px;
width: 106px;
height: 23px;
}
.content {
   height: 500px !important;
}
.content-caption {
     padding-bottom: 150px;
   top: 172px;
left: 140px;
width: 714px;
height: 91px;
text-align: left;
color: #FFFFFF;
}

.content-caption .goose{
font: normal normal 800 80px/75px Proxima Nova;
letter-spacing: 1.6px;
opacity: 0.87;
text-transform: uppercase;
}

.content-caption .come {

font: normal normal 800 40px/38px Proxima Nova;
letter-spacing: 1.6px;
opacity: 0.87;
text-transform: uppercase;
}
.content-caption .para {

font: normal normal 300 16px/22px Poppins;
letter-spacing: 0.32px;
opacity: 0.6;
}
</style>
