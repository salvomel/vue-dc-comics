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

</style>