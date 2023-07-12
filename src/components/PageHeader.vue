
<script>
export default {
    props: {
        navbarLinks: Array
    }
}
</script>


<template>
    <header class="container-fluid">

        <img src="../assets/img/logo.svg" alt="" class="img-fluid logo">

        <!-- NAVBAR LINKS -->
        <ul class="navbar-links">
            <li v-for="link in navbarLinks" :key="link.text">
                <a :href="link.url">{{ link.text }}</a>
            </li>
        </ul>

        <ul class="navbar-icons">
            <li><img src="../assets/img/image (8).svg" alt="" class="search"></li>
            <li><img src="../assets/img/image (9).svg" alt="" class="fb"></li>
            <li><img src="../assets/img/image (10).svg" alt=""></li>
            <li><img src="../assets/img/image (11).svg" alt=""></li>
            <li><img src="../assets/img/image (12).svg" alt=""></li>
        </ul>
    </header>
</template>


<style lang="scss" scoped>
header {
    background-color: #fff;
    height: 90px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 5px silver;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1;
}

.logo {
    width: 200px;
    margin-left: 20px;
}

.navbar-links {
    display: flex;
    margin-top: 15px;

    li {
        padding: 0 23px;
    }
}

.navbar-icons {
    display: flex;
    margin-right: 20px;
    margin-top: 15px;

    li {
        padding-left: 20px;

        img {
            width: 18px;

        }

    }

    .search {
        width: 42px;
        border-right: 1px solid #666666;
        padding-right: 17px;
    }

    .fb {
        width: 10px;
    }
}


a {
    color: black;
}
</style>