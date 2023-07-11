<script>
export default {

}
</script>



<template>
    <!-- WE DO SECTION -->
    <section class="container we-do-section">
        <div>PELICULA STUDIO</div>
        <h2>THIS IS WHAT WE DO</h2>
        <div class="row g-5">
            <div class="col-4">
                <img src="../assets/img/image (14).svg" alt="">
                <h5>ARRAY OF EQUIPMENT</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ratione saepe velit veniam ea sed.</p>
            </div>
            <div class="col-4">
                <img src="../assets/img/image (16).svg" alt="">
                <h5>NEW TECHNOLOGIES</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ratione saepe velit veniam ea sed.</p>
            </div>
            <div class="col-4">
                <img src="../assets/img/image (18).svg" alt="">
                <h5>VERSITILE ACTORS</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ratione saepe velit veniam ea sed.</p>
            </div>
            <div class="col-4">
                <img src="../assets/img/image (15).svg" alt="">
                <h5>TOP DIRECTORS</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ratione saepe velit veniam ea sed.</p>
            </div>
            <div class="col-4">
                <img src="../assets/img/image (17).svg" alt="">
                <h5>MINUTE EDITING</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ratione saepe velit veniam ea sed.</p>
            </div>
            <div class="col-4">
                <img src="../assets/img/image (19).svg" alt="">
                <h5>VERSITILE ACTORS</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ratione saepe velit veniam ea sed.</p>
            </div>
        </div>
    </section>

    <!-- ABOUT US SECTION -->
    <section class="about-us-section">
        <div class="container">
            <div class="row">
                <div class="col"></div>
                <div class="col">
                    <div>ABOUT US</div>
                    <h2 class="mt-3">HIGH QUALITY CINEMATICS</h2>
                    <p class="py-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima delectus aspernatur,
                        inventore
                        explicabo vel
                        incidunt quidem illum, consequatur exercitationem beatae iure nulla suscipit architecto aperiam fuga
                        distinctio ipsa nam numquam.
                    </p>
                    <a class="button-style" href="#">READ MORE</a>
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
p {
    font-size: 0.9rem;
}

// WE DO SECTION
.we-do-section {
    text-align: center;
    padding: 80px 0;

    img {
        width: 70px;
        height: 70px;
        margin-bottom: 20px;
    }

    p {
        color: #666666;
    }

    h2 {
        margin-top: 15px;
        margin-bottom: 50px;
    }
}

// ABOUT US SECTION 
.about-us-section {
    height: 500px;
    background-image: url(../assets/img/About-Us.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    color: #fff;
    display: flex;
    align-items: center;
}
</style>