<script>
export default {

}
</script>



<template>
    <!-- HITS SECTION -->
    <section class="hits container">
        <div class="small"><b>YOUR WATCHLIST</b></div>
        <h2>BEST HITS MOVIES</h2>
        <div class="row gy-5">
            <div class="col-4">
                <div class="card-box">
                    <img src="../assets/img/Gallery-01.jpg" alt="" class="img-fluid">
                    <h6>SEVENTEENTH SUMMER</h6>
                    <div class="small grey">Commercial, Music Video.</div>
                </div>
            </div>
            <div class="col-4">
                <div class="card-box">
                    <img src="../assets/img/Gallery-02.jpg" alt="" class="img-fluid">
                    <h6>A MESSAGE TO SPACE</h6>
                    <div class="small grey">Short Film</div>
                </div>
            </div>
            <div class="col-4">
                <div class="card-box">
                    <img src="../assets/img/Gallery-03.jpg" alt="" class="img-fluid">
                    <h6>THE MOST BEAUTIFUL THING</h6>
                    <div class="small grey">Music Video</div>
                </div>
            </div>
            <div class="col-4">
                <div class="card-box">
                    <img src="../assets/img/Gallery-04.jpg" alt="" class="img-fluid">
                    <h6>PERMISSION TO SPEAK</h6>
                    <div class="small grey">Documentary</div>
                </div>
            </div>
            <div class="col-4">
                <div class="card-box">
                    <img src="../assets/img/Gallery-05.jpg" alt="" class="img-fluid">
                    <h6>EXPLORE OUR SPACE</h6>
                    <div class="small grey">Film noir</div>
                </div>
            </div>
            <div class="col-4">
                <div class="card-box">
                    <img src="../assets/img/Gallery-06.jpg" alt="" class="img-fluid">
                    <h6>FILM PRODUCTION</h6>
                    <div class="small grey">Blaxploitation</div>
                </div>
            </div>
        </div>
    </section>

    <!-- STATS SECTION -->
    <section class="stats white">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h1>780</h1>
                    <h5>SATISFIED CLIENTS</h5>
                </div>
                <div class="col">
                    <h1>20+</h1>
                    <h5>OUR PROJECTS</h5>
                </div>
                <div class="col">
                    <h1>10.000</h1>
                    <h5>CUP OF COFFEE</h5>
                </div>
                <div class="col">
                    <h1>12</h1>
                    <h5>OUR AWARDS</h5>
                </div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
// HITS SECTION
.hits {
    text-align: center;
    padding: 100px 0;
}

// STATS SECTION
.stats {
    height: 300px;
    background-image: url(../assets/img/Parallax-01.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    display: flex;
    align-items: center;
    text-align: center;
}
</style>