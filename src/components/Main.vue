<template>
    <main>
        <div class="container w-75 m-auto mt-5 mb-5">
            <!-- first part of the main -->
            <div class="row w-75 m-auto pt-5 pb-5 justify-content-between">
                <div class="col-4 pe-4">
                    <h2> What we do?</h2>
                    <p class="fs-13-rf color-sc-txt-rf pt-2 pb-4">Lorem ipsum dolor sit amet aenean consectetuer socils adipiscing elit. Aenean commodo ligula eget dolor pretium quis sem.</p>
                    <button class="btn-rf rounded-pill"> Read more</button>
                </div>
                <div class="col-8">
                    <div class="row pb-4">
                        <div class="col-4 d-flex align-items-center me-5">
                            <img src="../../src/assets/img/h2-icon-01.png" alt="image icon" class="w-50 me-4">
                            <div>
                                <h6>Beatifull</h6>
                                <h6>illustrations</h6>
                            </div>
                        </div>
                        <div class="col-4 d-flex align-items-center ms-5">
                            <img src="../../src/assets/img/h2-icon-02.png" alt="image icon" class="w-50 me-4">
                            <div>
                                <h6>Brand</h6>
                                <h6>Strategies</h6>
                            </div>
                        </div>
                   </div>
                    <div class="row pt-4">
                        <div class="col-4 d-flex align-items-center me-5">
                            <img src="../../src/assets/img/h2-icon-03.png" alt="image icon" class="w-50 me-4">
                            <div>
                                <h6>Qualified</h6>
                                <h6>support</h6>
                            </div>
                        </div>
                        <div class="col-4 d-flex align-items-center ms-5">
                            <img src="../../src/assets/img/h2-icon-04.png" alt="image icon" class="w-50 me-4">
                            <div>
                                <h6>Books &</h6>
                                <h6>magazines</h6>
                            </div>
                        </div>
                   </div>
                </div>
            </div>
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
        </div>

        <!-- Third part of the main -->
        <div class="container-fluid back-img-3-rf pb-5 pt-5">
            <div class="row w-75 justify-content-evenly m-auto pt-5 mb-5 pb-5">
                <div class="col-3 pt-5 pb-5 text-center card opacity-rf card-rf borders-colors-button1-rf">
                    <h6>Basic</h6>           
                    <h3>99</h3>
                    <p class="fs-10-rf lh-lg color-sc-txt-rf mb-4">
                        5 design concepts <br>
                        Full copyright ownership <br>
                        Art direction <br>
                        Top level creatives <br>
                        No money back 
                    </p>
                    <button class="btn-rf fs-10-rf rounded-pill mb-5"> Learn more </button>
                </div><div class="col-3 pt-5 pb-5 text-center card opacity-rf card-rf back-color-img-rf">
                    <h6>Standard</h6>           
                    <h3>119</h3>
                    <p class="fs-10-rf lh-lg color-sc-txt-rf mb-4">
                        10 design concepts <br>
                        Full copyright ownership <br>
                        Art direction <br>
                        Top level creatives <br>
                        No money back 
                    </p>
                    <button class="btn-rf rounded-pill back-color-img-rf mb-5 fs-10-rf"> Learn more </button>
                </div>
                <div class="col-3 pt-5 pb-5 text-center card opacity-rf card-rf borders-colors-button2-rf">
                    <h6>Basic</h6>           
                    <h3>139</h3>
                    <p class="fs-10-rf  lh-lg color-sc-txt-rf mb-4">
                        15 design concepts <br>
                        Full copyright ownership <br>
                        Art direction <br>
                        Top level creatives <br>
                        No money back 
                    </p>
                    <button class="btn-rf rounded-pill mb-5 fs-10-rf"> Learn more </button>
                </div>
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


        .btn-rf {
            background-color: white;
            padding: 5px 10px;
            font-size: 11px; 
            border: 1px solid hsl(184deg 22% 59%);
        }

        h6 {
            margin-bottom: 0;
        }

        .opacity-rf {
            background-color: rgba(255, 255, 255, 0.1);
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


        .card-rf {
            border-radius: 20px;
            padding: 10px 40px;
        }


        .back-color-img-rf {
            background-color: hsl(166deg 35% 93%);
        }

        .borders-colors-button2-rf {
            border: 1px solid hsl(14deg 71% 71%);
        }
        
        .borders-colors-button1-rf {
            border: 1px solid hsl(33deg 72% 78%);
        }
</style>