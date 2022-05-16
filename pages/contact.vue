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
      <div class="carousel-caption d-md-block">
      CONTACT US
      24/7 support
      </div>
    </div>
  </div>

</section>


</main>
</template>

<style lang="scss" scoped>

@import '~./sass/main';
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
</style>