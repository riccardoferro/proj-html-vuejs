<template>
    <div class="jumbotron container-fluid position-relative ">
        <div class="container w-75 m-auto pt-5">

            <!-- First part of the jumbotron whre is the Title and Paragraph -->

            <div class="row pt-5 pb-5 justify-content-between">
                <div class="col-6">
                    <h2> We are Bryson, New York-based art & design studio</h2>
                </div>
                <div class="col-6 color-sc-txt-rf fs-10-rf">
                    <p>
                        Here at Bryson it only takes a smidgen of imagination and we're already prepared ourselves for
                        future challenges. Take a peek and see if you recognize the trademark ingredients of our work.
                    </p>
                </div>

            </div>

            <!-- Second part of the jumbotron where are the images -->
            <div class="row pt-5 w-75 m-auto position-relative">
                <div class="col-6">
                    <img src="../../src/assets/img/port-img-07.jpg"  alt="port-img" class="img-fluid">
                </div>
                <div class="col-6 folded-corner">
                    <img src="../../src/assets/img/port-img-08.jpg"  alt="port-img" class="img-fluid">
                </div>
                <div class="col-6">
                    <img src="../../src/assets/img/port-img-09.jpg"  alt="port-img" class="img-fluid">
                </div>
                <div class="col-6">
                    <img src="../../src/assets/img/port-img-10.jpg"  alt="port-img" class="img-fluid">
                </div>
                <div class="col-6">
                    <img src="../../src/assets/img/port-img-11.jpg"  alt="port-img" class="img-fluid">
                </div>
                <div class="col-6">
                    <img src="../../src/assets/img/port-img-12.jpg"  alt="port-img" class="img-fluid">
                </div>

            </div>

        </div>

    </div>
</template>

<script>
export default {
    name: "JumboComponent",
    methods: {
        // linkImgJumbo() {
        //     return "../../src/assets/img/port-img-07.jpg"
        // }
        
    }
}
</script>

<style lang="scss" scoped>



.row:first-child {
    background-image: url('../../src/assets/img/h2-background-img-02.png');
    background-size: cover;
    background-repeat: no-repeat;
    div:last-child {
        padding-top: 50px;
        padding-left: 100px;
        padding-right: 40px;
    }
}

.row:last-child {
    div {
        padding: 0;
    }
}

.jumbotron {
    background-image: url('../../src/assets/img/h2-background-img-01.png');
    background-size: cover;
    background-position: right;
}

// UTILITIES

@import "./src/assets/toolsStyle.scss";

.folded-corner {
              position: relative;
              width: 50%;
              padding: 1em 1.5em;
              margin: 0 auto;
              color: #fff;
              background: #47a79a;
              overflow: hidden;
            }

.folded-corner:before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    border-width: 60px 60px 60px 60px;
    border-style: solid;
    border-color: white hsl(19deg 90% 92%) hsl(19deg 90% 92%) white;
    // -webkit-box-shadow: 0 1px 1px rgba(0,0,0,0.3), -1px 1px 1px rgba(0,0,0,0.2);
    // -moz-box-shadow: 0 1px 1px rgba(0,0,0,0.3), -1px 1px 1px rgba(0,0,0,0.2);
    // box-shadow: 0 1px 1px rgba(0,0,0,0.3), -1px 1px 1px rgba(0,0,0,0.2);
    display: block;
    width: 0;
 }

</style>