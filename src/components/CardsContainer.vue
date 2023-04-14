<script>
import dccomics from "../assets/data/dc-comics.json";
import SlideEl from "./SlideEl.vue";
export default {
    name: "CardsContainer",
    data(){
        return{
        dccomics
        }
    },
    components: {
        SlideEl
    }
}
</script>

<template>
    <div class="row">
        <SlideEl class="col-2" v-for="slide in dccomics" :img="slide.thumb" :title="slide.series"></SlideEl>
    </div>
</template>


<style lang="scss" scoped>



</style>