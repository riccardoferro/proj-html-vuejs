<template>
    <footer>
      <div class="container-fluid position-relative">
          <div class="row flex-column justify-content-center align-items-center back-img pt-5 pb-3">
              <!-- logo -->
              <div class="col-3 text-center pt-5 pb-2">
                  <h5>Bryson</h5>
              </div>
              <!-- text -->
              <div class="col-4 text-center">
                  <p class="fs-10-rf color-sc-txt-rf"> 
                          Sometimes doing something seemingly demanding turns out to be fun. Here's the proof - Bryson, your brand new portfolio.
                  </p>
              </div>
              <!-- icons -->
              <div class="col-3 text-center pb-5 ">
                  <i class="fa-brands fa-instagram-square rounded-circle back-color-inst"></i>
                  <i class="fa-brands fa-facebook-f rounded-circle back-color-face"></i>
                  <i class="fa-brands fa-twitter rounded-circle back-color-twitt"></i>
                  <i class="fa-brands fa-pinterest-p rounded-circle back-color-pint"></i>
              </div>
            </div>
            <a href="#" class="arrow-up pos-arrow"> </a>
      </div>

    </footer>
</template>

<script>
export default {
  name: "FooterComponent"
}
</script>

<style lang="scss" scoped>

@import "./src/assets/toolsStyle.scss";


    .back-img {
      background-image: url('../../src/assets/img/h2-footer-img-01.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
    }

    .back-color-inst {
      background-color: hsl(181deg 28% 54%);
    }

     .back-color-face {
      background-color: hsl(38deg 86% 77%);
    }
     .back-color-twitt {
      background-color: hsl(15deg 83% 81%);
    }
     .back-color-pint {
      background-color: hsl(57deg 45% 72%);
    }

    i {
        margin-left: 10px;
        color: white;
        padding: 6px;
        font-size: 9px;
    }

    .pos-arrow {
      position: absolute;
      bottom: 20px;
      right: 10px;
    }
</style>