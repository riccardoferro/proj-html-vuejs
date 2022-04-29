<template>
    <div class="callinAction">
        <div class="container-fluid m-auto mt-5 mb-5 fs-10-rf position-relative">
            <div class="row w-75 m-auto pt-3 pb-3 justify-content-between ">
                <!-- left side -->
                <div class="col-4">
                    <h2>
                        Get in touch and say hello
                    </h2>
                    <span class="color-sc-txt-rf">
                        Lorem ipsum dolor sit amet, consectetuer socils quis adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa cum.
                    </span>
                </div>
                <!-- right side -->
                <div class="col-6">
                    <!-- text area -->
                    <div class="row pb-5">
                        <textarea type="text" placeholder="Comment" class="w-100 color-sc-txt-rf border-input pe-0 ps-0 ">
                        </textarea>
                    </div>
                    <!-- input text -->
                    <div class="row justify-content-between pb-5">
                        <div class="col-5 pe-0 ps-0">
                            <input type="text" placeholder="Name" class="w-100 color-sc-txt-rf border-input ">

                        </div>
                        <div class="col-5 pe-0 ps-0">
                            <input type="text" placeholder="Email" class="w-100 color-sc-txt-rf border-input ">
                        </div>
                    </div>
                    <!-- button -->
                    <button class="btn-rf rounded-pill"> Submit <i class="fa-solid fa-caret-right align-middle"></i></button>
                </div>

            </div>
                <a href="#" class="arrow-up pos-arrow"> </a>

        </div>
    </div>
</template>

<script>
export default {
    name: "CallInActionComponent"
}
</script>

<style lang="scss" scoped>

@import "./src/assets/toolsStyle.scss";

        .btn-rf {
            background-color: white;
            padding: 5px 30px;
            font-size: 8px; 
            font-weight: bolder;
            border: 2px solid hsl(184deg 22% 59%);
        }

        .border-input {
            border: none;
            border-bottom: 2px solid grey;
        }

        .pos-arrow {
            position: absolute;
            top: 20px;
            right: 10px;
        }
</style>