<template>
    <header>
        <div class="container-fluid">
            <div class="row justify-content-between">
                <img class="col-2" src="../../src/assets/img/logo-img-01.png" alt="image logo">
                <div class="buttons-rf col-auto">
                    <button v-for="(text,index) in data" :key="index" class="btn">
                        {{text}} 
                    </button>
                    <img class="ps-2" src="../../src/assets/svg/svg-1.svg" alt="image logo">
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
              margin: 0 15px;
              font-size: 12px;
              font-weight: 400;
            }
         
      }
    }
</style>