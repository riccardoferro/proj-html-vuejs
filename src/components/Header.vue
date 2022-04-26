<template>
    <header>
        <div class="container-fluid">
            <div class="row">
                <img src="../../src/assets/img/logo-img-01.png" alt="image logo">
            </div>
        </div>
    </header>
</template>

<script>
export default {
  name: "HeaderComponent"
}
</script>

<style lang="scss" scoped>
    header {
      .row {
          padding: 20px 40px;
           img {
                max-width: 75px;
            }
      }

     
    }
</style>