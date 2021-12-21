<template>
    <div class="banner">
        <div class="container">
            <a href="#" class="button-top">CURRENT SERIES</a>
        </div> 
    </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../style/variables';

    .banner {
        height: 350px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        
        .container {
            position: relative;
        }

        .button-top{
            position: absolute;
            bottom: -370px;
            left: 0;
            font-size: 20px;
            padding: 10px 20px;
            text-decoration: none;
            background-color: $brand_primary_color;
            color: white
        }
    }
</style>