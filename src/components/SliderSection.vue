<script>
export default {

}
</script>



<template>
    <section class="container-fluid white">
        <div class="box">
            <a href=""><img src="../assets/img/left-arrow.svg" alt=""></a>
        </div>
        <div class="title container">
            <h5>CINEMATO STUDIO</h5>
            <h1>ACTION AND INSPIRE PEOPLE</h1>
            <a class="button-style" href="#">READ MORE</a>
        </div>
        <div class="box">
            <a href=""><img src="../assets/img/right-arrow.svg" alt=""></a>
        </div>
    </section>
</template>



<style lang="scss" scoped>
section {
    height: 700px;
    background-image: url(../assets/img/blog05.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 90px;
}

img {
    width: 10px;
    filter: invert(100%) sepia(0%) saturate(1%) hue-rotate(328deg) brightness(106%) contrast(101%);
}

.box {
    padding: 3px 12px;
    background-color: black;
    filter: opacity(50%);
}

h1 {
    font-size: 60px;
    width: 40%;
    margin-bottom: 30px;
}
</style>