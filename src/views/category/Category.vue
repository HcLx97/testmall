<template>
    <div class="wrapper" ref="aaa">
        <ul class="content">
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
             <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>
            <li>9999</li>

            
        </ul>
    </div>
</template>

<script>
import BScroll from 'better-scroll'

export default {
    name: "Category",
    data() {
        return {
            scroll: null
        }
    },
    mounted() {
        this.scroll = new BScroll(document.querySelector('.wrapper'), {
            
        })
    },
}
</script>

<style scoped>
    .wrapper {
        height: 150px;
        background-color: red;

        /* overflow: hidden; */
        /* overflow: scroll; */
    }
</style>