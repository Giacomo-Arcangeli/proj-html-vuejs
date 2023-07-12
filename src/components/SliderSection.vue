<script>
export default {

}
</script>



<template>
    <section class="container-fluid">
        <div class="box">
            <a href=""><img src="../assets/img/left-arrow.svg" alt=""></a>
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
</style>