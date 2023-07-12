<script>
export default {

}
</script>



<template>
    <!-- COLLABORATE SECTION -->
    <section class="container">
        <div class="row gx-5">
            <div class="col">
                <div class="small"><b>COLLABORATE</b></div>
                <h2>WANT TO WORK WITH US? LEAVE US A MESSAGE!</h2>
                <p class="small grey">Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus quam debitis
                    autem consequuntur cumque
                    quod dicta. Aspernatur, dolorem? Inventore minus suscipit deserunt. Nulla quaerat voluptatibus nisi.
                    Adipisci deserunt voluptatibus rerum.
                    Tempora, ipsam excepturi dolorem, sequi corrupti perferendis at illum illo nam placeat atque quis? Ullam
                    illo ad minima dolores, quis quisquam nulla expedita tempora ducimus iure molestias cupiditate. Aliquam,
                    blanditiis.</p>
            </div>
            <div class="col mt-5">
                <form action="">
                    <div class="row">
                        <div class="col-6">
                            <input class="small" type="text" placeholder="Your Name">
                        </div>
                        <div class="col-6">
                            <input class="small" type="email" placeholder="Your email">
                        </div>
                        <div class="col-6">
                            <input class="small" type="number" placeholder="Mobile Number">
                        </div>
                        <div class="col-6">
                            <input class="small" type="password" placeholder="Your Pincode">
                        </div>
                        <div class="col">
                            <textarea class="small" name="" id="" cols="80" rows="8"
                                placeholder="Enter Your Message"></textarea>
                        </div>
                        <div class="col">
                            <a href="#" class="white">SUBMIT NOW</a>
                        </div>
                    </div>
                </form>


            </div>

        </div>
    </section>
</template>



<style lang="scss" scoped>
section {
    padding: 100px 0;

    p {
        text-align: justify;
    }

    input {
        width: 330px;
        margin-bottom: 30px;
        background-color: #f2f2f2;
        padding: 3px 15px;
        border: 0;
    }

    textarea {
        background-color: #f2f2f2;
        padding: 6px 15px;
        border: 0;
    }

    a {
        background-color: black;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 4px 0;
        margin-top: 20px;
        font-size: 0.9rem;
        font-weight: bold;
    }
}
</style>