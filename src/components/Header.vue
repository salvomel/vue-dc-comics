<template>
    <header class="container">
        <div class="header-wrapper">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>

            <nav>
                <ul class="menu">
                    <li v-for="(link, index) in links" :key="index" :class="{current: link.current}">
                        <a :href="link.url">{{link.text}}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header",
    data: function() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false
                },
                {
                    text: 'Tv',
                    url: '#',
                    current: false
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false
                },
                {
                    text: 'News',
                    url: '#',
                    current: false
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false
                }
            ],
        };
    }
}
</script>

<style scoped lang="scss">
.header-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100px;

    .logo {
        img {
            width: 65px;
        }
    }
    
    .menu {
        display: flex;
        list-style-type: none;
        text-transform: uppercase;
        font-size: 12px;

        li {
            margin: 0 10px;

            &.current {
                color: #0282f9;
                border-bottom: 4px solid #0282f9;
            }

            a {
                line-height: 96px;
                text-decoration: none;
                color: black;
            }
        }
    }
}
</style>