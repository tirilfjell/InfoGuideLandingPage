<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height p-4">
      <div class="container pt-3">
        <div class="row pb-5">
          <div class="col-lg-6 pt-4 my-auto">
            <div class="text-center mb-3 d-block d-lg-none">
              <h1 class="display-3">{{ title }}</h1>
              <h3>Alt du trenger å vite om oppstarten av skoleåret ditt</h3>
            </div>
            <img id="iphone-img" src="../assets/iPhoneInfo.png" class="img-fluig">
          </div>

          <div class="col-lg-6 my-auto pt-4">
            <div class="text-center mb-3 d-none d-lg-block">
              <h1 class="display-3">{{ title }}</h1>
              <h3>Alt du trenger å vite om oppstarten av skoleåret ditt</h3>
            </div>

            <div id="available" class="p-2">
              <h4 class="text-center mb-2 mt-3 text-light">Available On</h4>
              <div class="row">
                <div class="col my-auto">
                  <img
                    src="../assets/download_apple.png"
                    class="float-right img-fluid app_store_img"
                  >
                </div>
                <div class="col my-auto">
                  <img
                    src="../assets/download_google.png"
                    class="float-left img-fluid app_store_img"
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="about" class="bg-dark p-3 p-md-5">
      <div class="row">
        <div class="col-lg">
          <!-- Icon made by Freepik perfect from www.flaticon.com -->
          <img src="../assets/oppstartsfestivalen.png" height="120" class="m-4">
          <h5 class="ml-md-4 mr-md-4">
            Plan your next adventure by setting a daily spending budget.
            We make it easy to break your expenses down by category,
            giving you more time to plan the important tings!
          </h5>
        </div>
        <div class="col-lg">
          <!-- Icon made by Freepik perfect from www.flaticon.com -->
          <img src="../assets/LogoK.png" height="120" class="m-4">
          <h5 class="ml-md-4 mr-md-4">
            Use the app to track how much money you’ve saved towards your trips
            total budgeted goal. Know exactly how much more you need to save,
            and how much time you have left to save.
          </h5>
        </div>
        <div class="col-lg">
          <!-- Icon made by Freepik perfect from www.flaticon.com -->
          <img src="../assets/icons/passport.svg" height="120" class="m-4">
          <h5 class="ml-md-4 mr-md-4">
            When the day of your trip comes, have the peace of mind that you
            planned out your expenses. Never worry about money on a trip again!
          </h5>
        </div>
      </div>
    </div>

    <div id="footer" class="p-4">
      <footer class="text-light p-4">
        <a
          href="https://www.youtube.com/1manstartup"
          target="_blank"
          class="text-warning"
        >Build This App</a> |
        <a href="#" class="text-warning">Privacy Policy</a>
        <br>
        <small>&copy; 2021, Kvadtratuen Videregående Skole</small>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "KVADRATUREN VGS APP",
      email: "",
      message: "",
      show_contact: true,
      contact_email: "",
      contact_message: "",
      contact_notice: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#home-page {
  background-color: #92d2f2;
  background: url("../assets/kva.jpg") no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

#about {
  min-height: 40vh;
}

#iphone-img {
  max-height: 80vh;
}

#footer {
  background-color: #24ae80;
}

.app_store_img {
  max-height: 80px;
}
</style>
