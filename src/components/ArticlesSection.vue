<script>
export default {

}
</script>



<template>
    <!-- ARTICLES SECTION -->
    <section class="articles container text-center">
        <div class="small text-center"><b>LATEST NEWS</b></div>
        <h2>ARTICLES UPDATED DAILY</h2>
        <div class="row">
            <div class="col">
                <div class="card-box">
                    <img src="../assets/img/blog07.jpg" alt="" class="img-fluid">
                    <div class="grey">November 06, 2021 By Admin</div>
                    <h6>RECAP YOUR LATEST COMPANY EVENT</h6>
                    <div class="small">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolore ducimus quos esse
                        incidunt dolorem.
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card-box">
                    <img src="../assets/img/blog01.jpg" alt="" class="img-fluid">
                    <div class="grey">November 06, 2021 By Admin</div>
                    <h6>RECAP YOUR LATEST COMPANY EVENT</h6>
                    <div class="small">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolore ducimus quos esse
                        incidunt dolorem.
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card-box">
                    <img src="../assets/img/blog02.jpg" alt="" class="img-fluid">
                    <div class="grey">November 06, 2021 By Admin</div>
                    <h6>RECAP YOUR LATEST COMPANY EVENT</h6>
                    <div class="small">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolore ducimus quos esse
                        incidunt dolorem.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- BRANDS SECTION -->
    <section class="brands">
        <div class="container">
            <div class="row">
                <div class="col">
                    <img src="../assets/img/03.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/04.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/05.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/01.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/img/02.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
// ARTICLES SECTION
.articles {
    padding: 100px 0;

    .card-box {
        text-align: start;

        .grey {
            font-size: 0.8rem;
            margin-top: 20px;
        }
    }
}

// BRANDS SECTION
.brands {
    height: 300px;
    background-image: url(../assets/img/Parallax-03.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    display: flex;
    align-items: center;
    text-align: center;
}
</style>