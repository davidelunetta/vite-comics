<template>
    <div>
        <main class="black">
            <div class="container">
                <div id="card" v-for="(items, index) in cards" :key="index">
                    <div class="image">
                        <img :src="cards.thumb" alt="">
                    </div>
                    <span id="price">{{items.price}}</span>
                    <span>{{items.series}}</span>
                </div>
            </div>
            <div class="load-more">
                <button>LOAD MORE</button>
            </div>
        </main>
    </div>
</template>

<script>
export default {
    props:{
        cards: Array
    }
}
</script>

<style lang="scss" scoped>
@import "@/assets/style/main.scss"
</style>