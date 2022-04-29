<template>
    <main>
        <!-- first part of the main -->
        <div class="container-fluid m-auto mt-5 mb-5 position-relative">
            <div class="row w-50 m-auto pt-5 pb-5 justify-content-between">
                <div class="col-4 pe-4">
                    <h4> What we do?</h4>
                    <p class="fs-10-rf color-sc-txt-rf pt-2 pb-4">Lorem ipsum dolor sit amet aenean consectetuer socils adipiscing elit. Aenean commodo ligula eget dolor pretium quis sem.</p>
                    <button class="btn-rf rounded-pill pad-button"> Read more <i class="fa-solid fa-caret-right align-middle"></i></button>
                </div>
                <div class="col-8">
                    <div class="row pb-4">
                        <div class="col-4 d-flex align-items-center me-5">
                            <img src="../../src/assets/img/h2-icon-01.png" alt="image icon" class="w-50 me-4">
                            <div class="fs-11-rf fw-bold">
                                <div>Beatifull</div>
                                <div>illustrations</div>
                            </div>
                        </div>
                        <div class="col-4 d-flex align-items-center ms-5">
                            <img src="../../src/assets/img/h2-icon-02.png" alt="image icon" class="w-50 me-4">
                            <div class="fs-11-rf fw-bold">
                                <div>Brand</div>
                                <div>Strategies</div>
                            </div>
                        </div>
                   </div>
                    <div class="row pt-4">
                        <div class="col-4 d-flex align-items-center me-5">
                            <img src="../../src/assets/img/h2-icon-03.png" alt="image icon" class="w-50 me-4">
                            <div class="fs-11-rf fw-bold">
                                <div>Qualified</div>
                                <div>support</div>
                            </div>
                        </div>
                        <div class="col-4 d-flex align-items-center ms-5">
                            <img src="../../src/assets/img/h2-icon-04.png" alt="image icon" class="w-50 me-4">
                            <div class="fs-11-rf fw-bold">
                                <div>Books &</div>
                                <div>magazines</div>
                            </div>
                        </div>
                   </div>
                </div>
            </div>
        <div class="icons text-center">
              <i class="fa-brands fa-instagram-square rounded-circle back-color-inst"></i>
              <i class="fa-brands fa-facebook-f rounded-circle back-color-face"></i>
              <i class="fa-brands fa-twitter rounded-circle back-color-twitt"></i>
              <i class="fa-brands fa-pinterest-p rounded-circle back-color-pint"></i>
            </div>
        <a href="#" class="arrow-up-rf pos-arrow-2-rf"> </a>

        </div>
         <!-- second part of the main -->
        <div class="container-fluid position-relative">
            <div class="row ">
                <div class="col-1 back-img-l h-150px">
                </div>
                <div class="col-10 back-img-c h-150px"></div>
                <div class="col-1 back-img-r h-150px"></div>
            </div>
            <div class="row">
                <div class="col-1 back-img-l2 h-300px"></div>
                <div class="col-10 back-img-c2 h-300px"></div>
                <div class="col-1 back-img-r2 h-300px"></div>
            </div>
            <img src="../../src/assets/img/main-home-video-button-img-01.png" alt="" class="position-absolute top-50 start-50 translate-middle w-50px ">
        <a href="#" class="arrow-up-rf pos-arrow-rf"> </a>
        
        </div>

        <!-- Third part of the main -->
        <div class="container-fluid back-img-3-rf pb-5 pt-5 position-relative">
                <div class="row w-75 justify-content-evenly m-auto pt-5 mb-5 pb-5">
                        <div class="col-3 pt-5 pb-5 text-center card opacity-rf card-rf borders-colors-button1-rf">
                            <h6>Basic</h6> 
                            <div class="position-relative">
                                <h3 class="d-inline-block">99</h3>
                                <span class="dollar-pos">$</span>
                            </div>
                            <p class="fs-10-rf lh-lg color-sc-txt-rf mb-4">
                                5 design concepts <br>
                                Full copyright ownership <br>
                                Art direction <br>
                                Top level creatives <br>
                                No money back 
                            </p>
                            <button class="btn-rf fs-10-rf rounded-pill mb-5"> Learn more <i class="fa-solid fa-caret-right align-middle"></i>  </button>
                        </div><div class="col-3 pt-5 pb-5 text-center card opacity-rf card-rf back-color-img-rf">
                            <h6>Standard</h6>           
                            <div class="position-relative">
                                <h3 class="d-inline-block">119</h3>
                                <span class="dollar-pos">$</span>
                            </div>
                            <p class="fs-10-rf lh-lg color-sc-txt-rf mb-4">
                                10 design concepts <br>
                                Full copyright ownership <br>
                                Art direction <br>
                                Top level creatives <br>
                                No money back 
                            </p>
                            <button class="btn-rf rounded-pill back-color-img-rf mb-5 fs-10-rf"> Learn more <i class="fa-solid fa-caret-right align-middle"></i> </button>
                        </div>
                        <div class="col-3 pt-5 pb-5 text-center card opacity-rf card-rf borders-colors-button2-rf">
                            <h6>Basic</h6>           
                            <div class="position-relative">
                                <h3 class="d-inline-block">139</h3>
                                <span class="dollar-pos">$</span>
                            </div>
                            <p class="fs-10-rf  lh-lg color-sc-txt-rf mb-4">
                                15 design concepts <br>
                                Full copyright ownership <br>
                                Art direction <br>
                                Top level creatives <br>
                                No money back 
                            </p>
                            <button class="btn-rf rounded-pill mb-5 fs-10-rf"> Learn more <i class="fa-solid fa-caret-right align-middle"></i> </button>
                        </div>
                </div>
        <a href="#" class="arrow-up-rf pos-arrow-rf"> </a>
        <div class="pos-icons-rf">
            <img src="../../src/assets/svg/svg-2.svg" alt="icon" class="icon1-rf">
            <img src="../../src/assets/svg/svg-4.svg" alt="icon" class="icon2-rf d-block" >
        </div>
        </div>
    </main>
</template>

<script>
export default {
    name: "MainComponent"
}
</script>

<style lang="scss" scoped>

@import "./src/assets/toolsStyle.scss";

        .pad-button {
                font-size: 8px;
                padding: 5px 25px;
        }

        h6 {
            margin-bottom: 0;
        }

        .back-img-c{
            background-image: url('../../src/assets/img/h2-img-2.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: bottom;
        }

        .back-img-l{
            background-image: url('../../src/assets/img/h2-img-2.jpg');
            background-attachment: fixed;
            background-position: left;
        }
        .back-img-r{
            background-image: url('../../src/assets/img/h2-img-2.jpg');
            background-attachment: fixed;
            background-position: center;
        }

        .back-img-c2{
            background-image: url('../../src/assets/img/h2-img-2.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: top;
        }

        .back-img-l2{
            background-image: url('../../src/assets/img/h2-img-2.jpg');
            background-position-y: center;
        }
        .back-img-r2{
            background-image: url('../../src/assets/img/h2-img-2.jpg');
            background-position-y: right;
        }

        .back-img-3-rf {
            background-image: url('../../src/assets/img/h2-background-img-03.png');
            background-size: cover;
        }

        .borders-colors-button2-rf {
            border: 1px solid hsl(14deg 71% 71%);
        }
        
        .borders-colors-button1-rf {
            border: 1px solid hsl(33deg 72% 78%);
        }

        .dollar-pos {
            position: absolute;
            top: 0;
        }

    .pos-arrow-rf {
        position: absolute;
        top: 250px;
        right: 10px;
        }

        .pos-arrow-2-rf {
        position: absolute;
        top: 250px;
        right: 10px;
        }

        .icon1-rf {
            background-color: hsl(347deg 86% 55%);
            width: 20px;
            padding: 3px;
        }

        .icon2-rf {
            background-color: white;
            width: 20px;
            padding: 6px;
        }
        
        .pos-icons-rf {
            position: absolute;
            right: 0;
            top: 300px;
        }

        .icons {
            font-size: 10px;
            
            display: flex;
            flex-direction: column;
            position: absolute;
            right: 20px;
            top: 100px;
            i {
                margin: 10px 0;
            }
        }
</style>