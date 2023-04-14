<template>
    <div>
        <img class="img-fluid" :src="img" alt="img">
        <h5>{{ title }}</h5>
    </div>
</template>

<script>
export default {
   name: "SlideEl",
   props: {
    img: String,
    title: String,
   }
}
</script>

<style lang="scss" scoped>

div{
    
    h5{
        text-transform: uppercase;
        font-size: smaller;
    }
}

</style>