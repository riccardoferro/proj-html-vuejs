<template>
    <header>
        <div class="container-fluid">
            <div class="row justify-content-between">
                <!-- logo -->
                <img class="col-2" src="../../src/assets/img/logo-img-01.png" alt="image logo">

                <!-- nav bar -->
                <div class="buttons-rf col-auto">
                    <!-- buttons -->
                    <button v-for="(text,index) in data" :key="index" class="btn">
                        {{text}} 
                    </button>
                    <!-- menu -->
                     <a href="#">  
                         <img class="ps-2" src="../../src/assets/svg/svg-1.svg" alt="image logo">
                     </a>
                </div>
            </div>
        </div>
    </header>
</template>

<script>

export default {
    name: "HeaderComponent",
    props: {
      data: Array
    }
}

</script>

<style lang="scss" scoped>
    header {
      .row {
            padding: 20px 20px;
           img {
                max-width: 80px;
                max-height: 20px;
                align-self: center;
            }
            button {
              margin: 0 5px;
              font-size: 10px;
              font-weight: 500;

              &:hover {
                  border-bottom: 2px solid hsl(16deg 64% 73%);
              }
            }
         
      }
    }
</style>