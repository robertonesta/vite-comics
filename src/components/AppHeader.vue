<script>
export default {
    name: "AppHeader",
    data() {
        return {
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="logo">
            <img class="img-fluid" src="../assets/img/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li><strong>CHARACTERS</strong></li>
                <li><strong>COMICS</strong></li>
                <li><strong>MOVIES</strong></li>
                <li><strong>TV</strong></li>
                <li><strong>GAMES</strong></li>
                <li><strong>COLLECTIBLES</strong></li>
                <li><strong>VIDEOS</strong></li>
                <li><strong>FANS</strong></li>
                <li><strong>NEWS</strong></li>
                <li><strong>SHOP</strong></li>
            </ul>
        </nav>
    </div>
 
</template>

<style scoped lang="scss">
.container{
    width: 70%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;

    ul{
        display: flex;
        list-style-type: none;
        padding: 0.5rem 1rem;

        li{
            padding: 0.25rem 0.5rem;
        };
    }
}

</style>