<template>
<main>
  <section class="first_sec">
  <i class="far fa-window-close"></i>
    <div class ="container-fluid">
    <div class="row">

      <div class="col-md-6">
    <img src="../assets/drive/car-large.jpg" style="width: 100%; height: 100%;">
      </div>

      <div class="col-md-6 text">
      <p class="new">NEW Range</p>

      <p class="la">LA Ferrari</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>

        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      </div>

    </div>
    </div>
  </section>
</main>
</template>


<style lang="scss" scoped>

@import '~./sass/main';
main {
background: var(--black-high-) 0% 0% no-repeat padding-box;
}
.text {
top: 245px;
left: 890px;
height: 820px;
text-align: left;
font: normal normal 300 18px/27px Poppins;
letter-spacing: 0.36px;
color: #FFFFFF;
opacity: 0.87;
padding-top: 12%;
}
.la {
  text-align: left;
font: normal normal 800 56px/75px Proxima Nova;
letter-spacing: 1.12px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.87;
}
.new {
  text-align: left;
font: normal normal normal 18px/75px Proxima Nova;
letter-spacing: 0.72px;
color: #FFFFFF;
text-transform: uppercase;
opacity: 0.6;
}
.fa-window-close{
  top:0;
  right:0;
  position:absolute;
  color:red;
}

</style>
