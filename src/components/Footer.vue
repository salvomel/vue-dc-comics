<template>
    <footer>
        <div class="background-container">

            <div class="container">

                <div class="footer-wrapper">

                    <div class="left-side">

                        <div class="footer-col">
                            <h3>dc comics</h3>
                            <ul class="footer-menu">
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>
                        
                            <h3>shop</h3>
                            <ul class="footer-menu">
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>
                        </div>
                    
                        <div class="footer-col">
                            <h3>dc</h3>
                            <ul class="footer-menu">
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>
                        </div>
                    
                        <div class="footer-col">
                            <h3>sites</h3>
                            <ul class="footer-menu">
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>
                        </div>

                    </div>
                    
                    <div class="footer-img">
                        <img src="../assets/img/dc-logo-bg.png" alt="Logo DC">
                    </div>

                </div>
            </div>
        </div>

        <div class="footer-bottom">
            <div class="container">
                <div class="bottom-wrapper">
                    <div class="button">
                        <a href="#">SIGN-UP NOW!</a>
                    </div>

                    <div class="social">
                        <span>FOLLOW US</span>
                        <img src="../assets/img/footer-facebook.png" alt="FB">
                        <img src="../assets/img/footer-twitter.png" alt="TW">
                        <img src="../assets/img/footer-youtube.png" alt="YT">
                        <img src="../assets/img/footer-pinterest.png" alt="PI">
                        <img src="../assets/img/footer-periscope.png" alt="PS">
                    </div>

                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
    
    .background-container {
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;

        .footer-wrapper {
            padding: 25px 0 35px;
            position: relative;
            overflow: hidden;

            .footer-img {
                position: absolute;
                top: -25%;
                right: 0;

                img {
                    width: 450px;
                }
            }

            .left-side {
                display: flex;

                .footer-col {
                    margin-right: 20px;

                    h3 {
                        text-transform: uppercase;
                        font-size: 15px;
                        color: white;
                        margin-top: 10px;
                    }

                    .footer-menu {
                        list-style-type: none;
                        margin-top: 10px;

                        a {
                            text-decoration: none;
                            color: #666f66;
                            font-size: 12px;
                        }
                    }
                }
            }
        }
    }

    .footer-bottom {
        background-color: #303030;
        padding: 25px 0;

        .bottom-wrapper {
            display: flex;
            align-items: center;
            justify-content: space-between;

            .button {
                padding: 10px;
                border: 2px solid #0282f9;

                a {
                    text-decoration: none;
                    color: white;
                }
            }

            .social {
                display: flex;
                align-items: center;

                span {
                    color: #0282f9
                }

                img {
                    margin-left: 15px;
                    height: 30px;
                }
            }
        }
    }
</style>