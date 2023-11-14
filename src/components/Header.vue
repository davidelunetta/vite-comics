<template>
    <header>
        <nav>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/DC_Comics_logo.svg/2048px-DC_Comics_logo.svg.png" alt="">
            <ul>
                <li v-for="(item, index) in nav" :key="index">{{item.label}}
                    <a :href="nav.url"></a>
                </li> 
            </ul>
        </nav>
        <div class="jumbotron">
            <button class="series">CURRENT SERIES</button>
        </div>
    </header>
</template>

<script>
export default {
  props:{
      nav:Array,
  }
}
</script>

<style lang="scss" scoped>
@import "@/assets/style/header.scss"
</style>