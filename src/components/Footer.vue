<template>
    <div>
        <footer>
            <div class="container">

                <div class="col">

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
                </div>

                <div class="col">
                    <img src="../assets/img/dc-logo-bg.png" alt="Logo DC">
                </div>
            </div>

        </footer>

        <div class="footer-bottom">
        
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
    
    footer {
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        height: 300px;

        .col {
            width: 50%;

            img {
                width: 300px;
            }

            .left-side {
                display: flex;
                width: 50%;

                .footer-col {
                    width: calc(100% / 3);

                    h3 {
                        text-transform: uppercase;
                        font-size: 15px;
                        color: white;
                    }

                    .footer-menu {
                        list-style-type: none;

                        a {
                            text-decoration: none;
                            color: white;
                            font-size: 12px;
                        }
                    }
                }

            }
        }

    }
</style>