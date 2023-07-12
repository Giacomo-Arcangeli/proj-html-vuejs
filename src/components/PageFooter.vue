<script>
export default {
    props: {
        informationLinks: Array,
        usefulLinks: Array
    }
}
</script>



<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col">
                    <ul>
                        <li class="title">CONTACT INFO</li>
                        <li class="mb-2">
                            <img src="../assets/img/footer-location-dot-solid.svg" alt="">
                            <span>
                                2/45 Tower Street, New York
                                USA
                            </span>
                        </li>
                        <li class="mb-2">
                            <img src="../assets/img/footer-phone-solid.svg" alt="">
                            <span>
                                Call Us On 0800 840 1010
                            </span>
                        </li>
                        <li class="mb-2">
                            <img src="../assets/img/footer-envelope-soli.svg" alt="">
                            <span>
                                Demo@Example.Com
                            </span>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="title">INFORMATION</li>
                        <li class="mb-2" v-for="link in informationLinks" :key="link.text">
                            <a class="link" :href="link.url">{{ link.text }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="title">USEFUL LINKS</li>
                        <li class="mb-2" v-for="link in usefulLinks" :key="link.text">
                            <a class="link" :href="link.url">{{ link.text }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="title">NEWSLETTER</li>
                        <li class="mb-2">
                            Subscribe To Receive Inspiration,
                            Ideas & News In Your Inbox.
                        </li>
                        <li>
                            <input type="email" placeholder="Enter Your Email" class="email">
                        </li>
                        <li>
                            <a class="button-style" href="#">SUBSCRIBE</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="copyright small">© 2023 All Rights Reserved. Developed By Giacomo Arcangeli</div>
        </div>
    </footer>
</template>



<style lang="scss" scoped>
footer {
    padding-top: 100px;
    padding-bottom: 20px;
    background-color: #111111;
    color: rgb(204, 204, 204);
    font-size: 0.9rem;

    .title {
        font-weight: bold;
        color: #ffffff;
        margin-bottom: 20px;
    }

    img {
        width: 15px;
        margin-right: 10px;
    }

    .link {
        color: rgb(204, 204, 204);

        &:hover {
            color: #ffffff;
            transition: 0.3s;
        }
    }
}

.email {
    border: 0;
    margin-bottom: 28px;
    padding: 5px 15px;
    width: 280px;
    background-color: rgb(28, 28, 28);
}

.button-style {
    color: #111111;
}

.copyright {
    margin-top: 100px;
    height: 50px;
    border-top: 1px solid #666666;
    text-align: center;
    padding-top: 20px;
    color: rgb(204, 204, 204);
}
</style>