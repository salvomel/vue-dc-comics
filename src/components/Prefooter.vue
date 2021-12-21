<template>
    <div class="prefooter">
        <ul>
            <li v-for="(link, index) in links" :key="index">
                <img :src="require(`../assets/img/${link.img}`)" :alt="link.text">
                <a :href="link.url">{{link.text}}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "Shop",
    data: function () {
        return {
            links: [
                {
                    img: 'buy-comics-digital-comics.png',
                    text: 'DIGITAL COMICS',
                    url: '#',
                },
                {
                    img: 'buy-comics-merchandise.png',
                    text: 'DC MERCHANDISE',
                    url: '#',
                },
                {
                    img: 'buy-comics-subscriptions.png',
                    text: 'SUBSCRIPTION',
                    url: '#',
                },
                {
                    img: 'buy-comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR',
                    url: '#',
                },
                {
                    img: 'buy-dc-power-visa.svg',
                    text: 'DC POWER VISA',
                    url: '#',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
.prefooter {
    background-color: #0282f9;
    padding: 40px 0;
    
    ul { 
        display: flex;
        list-style-type: none;
        width: 65%;
        margin: auto;

        li {
            display: flex;
            align-items: center;
            margin: 0 10px;
        }

        a {
            color: white;
            text-decoration: none;
            margin-left: 10px;
            font-size: 13px;
        }

        img {
                height: 40px;
            }
    }
}
</style>
