<script>
export default {
    name: "AppMain",
    data() {
        return {
           
        }
    }
}
</script>

<template>
    <section class="content">
        <div class="container">
            <h2><i class="fa-solid fa-arrow-right"></i>Content Goes Here<i class="fa-solid fa-arrow-left"></i></h2>
        </div>
    </section>
    <section class="icons"></section>
 
</template>

<style scoped lang="scss">
.content{
    background-color: black;
    color: white;
    padding: 1rem;
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