<template>
    <section class="content">
        <div class="container">
            
        </div>
    </section>
</template>

<script>
import dccomics from "../assets/data/dc-comics.json";
export default {
   name: "CardsContainer",
   data(){
    return{
        dccomics
    }
   }
}
</script>

<style lang="scss" scoped>
.content{
    background-color: black;
    color: white;
    padding: 1rem 0;
    .container{
        width: 70%;
        display: flex;
        align-items: center;
        h2{
            font-size: 2rem;
        }
    }
}

</style>