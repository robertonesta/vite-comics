<script>
import CardsContainer from './CardsContainer.vue';
export default {
    name: "AppMain",
    data() {
        return {
            
           
        }
    },
    components: {
        CardsContainer
    }
}
</script>

<template>
    <CardsContainer></CardsContainer>
    <section class="icons">
        <div class="container">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </li>
                <li>
                    <img height="40" src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </li>
                
            </ul>
        </div>
    </section>
 
</template>

<style scoped lang="scss">

.icons{
    background-color: #0282f9;
    .container{
        padding: 1rem;
        width: 70%;
        display: flex;
        align-items: center;
        justify-content: space-around;
        
        ul{ 
            padding: 0;
            color: white;
            display: flex;
            list-style-type: none;

            li{
                align-items: center;
                display: flex;
               padding: 1rem 0.25rem;
                
                img{
                    max-width: 50px;
                }
                span{
                    padding: 0 0.25rem;
                }
        };
        }
    }
}

</style>