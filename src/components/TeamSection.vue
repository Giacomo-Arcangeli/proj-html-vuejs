<script>
export default {

}
</script>



<template>
    <!-- TEAM SECTION -->
    <section class="team container">
        <div class="small"><b>THE PERICUROS</b></div>
        <h2>MEET THE TEAM</h2>
        <div class="row">
            <div class="col">
                <img src="../assets/img/Team-01.jpg" alt="" class="img-fluid">
                <h6>FABRICIO GUERRA</h6>
                <div class="small grey">Main Director</div>
            </div>
            <div class="col">
                <img src="../assets/img/Team-02.jpg" alt="" class="img-fluid">
                <h6>UMBERTO PAGODA</h6>
                <div class="small grey">Main Writer</div>
            </div>
            <div class="col">
                <img src="../assets/img/Team-03.jpg" alt="" class="img-fluid">
                <h6>GLORIA RICCASSO</h6>
                <div class="small grey">Main Producer</div>
            </div>
            <div class="col">
                <img src="../assets/img/Team-04.jpg" alt="" class="img-fluid">
                <h6>LIO NAPOIN</h6>
                <div class="small grey">Cameraman</div>
            </div>
        </div>
    </section>

    <!-- COMMENT SECTION -->
    <section class="comment white">
        <div class="container">
            <div class="row">
                <div class="col"></div>
                <div class="col-6">
                    <img src="../assets/img/image (20).svg" alt="" class="icon">
                    <p class="small my-4">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero ullam debitis dolorum odio in,
                        quaerat sequi laboriosam enim non quam praesentium aliquam esse perferendis ad inventore! Quia
                        tempore iure
                        repudiandae.
                    </p>
                    <div class="user">
                        <img src="../assets/img/01.jpg" alt="">
                        <div class="mx-3">
                            <div class="small"><b>JOHN DOE</b></div>
                            <div class="small">Designer</div>
                        </div>
                    </div>
                </div>
                <div class="col"></div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
// TEAM SECTION
.team {
    text-align: center;
    padding: 100px 0;
}

// COMMENT SECTION
.comment {
    height: 570px;
    background-image: url(../assets/img/Parallax-02.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    display: flex;
    align-items: center;
    text-align: center;

    .icon {
        width: 50px;
        filter: invert(100%) sepia(0%) saturate(1%) hue-rotate(328deg) brightness(106%) contrast(101%);
    }

    .user {
        display: flex;
        justify-content: center;
        align-items: center;

        img {
            width: 60px;
            border-radius: 50%;
            margin-top: 10px;
        }

        div {
            text-align: start;
            line-height: 1;
        }
    }
}
</style>