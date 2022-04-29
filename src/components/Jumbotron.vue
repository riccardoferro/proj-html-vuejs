<template>
    <div class="jumbotron container-fluid position-relative ">
        <div class="container w-75 m-auto pt-5">

            <!-- First part of the jumbotron whre is the Title and Paragraph -->

            <div class="row pt-5 pb-5 justify-content-between">
                <div class="col-5">
                    <h1> We are Bryson, New York-based art & design studio</h1>
                </div>
                <div class="col-7 color-sc-txt-rf fs-13-rf">
                    <p>
                        Here at Bryson it only takes a smidgen of imagination and we're already prepared ourselves for
                        future challenges. Take a peek and see if you recognize the trademark ingredients of our work.
                    </p>
                </div>

            </div>

            <!-- Second part of the jumbotron where are the images -->
            <div class="row pt-5 w-75 m-auto">
                <div class="col-6">
                    <img src="../../src/assets/img/port-img-07.jpg"  alt="port-img" class="img-fluid">
                </div>
                <div class="col-6">
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

    <a href="#" class="arrow-up-rf pos-arrow-2-rf"> </a>
    <a href="#" class="arrow-up-rf pos-arrow-1-rf"> </a>


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

        .pos-arrow-rf {
            position: absolute;
            top: 250px;
            right: 10px;
        }

        .pos-arrow-2-rf {
            position: absolute;
            bottom: 200px;
            right: 10px;
        }

        .pos-arrow-1-rf {
            position: absolute;
            top: 700px;
            right: 10px;
        }


</style>