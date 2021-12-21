<template>
    <div class="comic">
        <img :src="comicObject.thumb" :alt="comicObject.series">
        <h3>{{comicObject.series}}</h3>
    </div>
</template>

<script>
export default {
    name: 'Comic',
    props: ['comicObject']
}
</script>

<style scoped lang="scss">
@import '../style/variables';

    .comic {
        width: calc(100% / 6);
        padding-bottom: 20px;

        img {
            width: 150px;
        }

        h3 {
            color: white;
            text-transform: uppercase;
            font-size: 15px;
            margin-top: 10px;
        }
    }
</style>