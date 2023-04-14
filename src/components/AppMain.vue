<script>
import jumbotronComponent from "./jumbotronComponent.vue"
import CardsContainer from './CardsContainer.vue';

export default {
    name: "AppMain",
    data() {
        return {
            
           
        }
    },
    components: {
        CardsContainer,
        jumbotronComponent
    }
}
</script>

<template>
    <jumbotronComponent></jumbotronComponent>
    <div class="content">
        <button>
            <a href="">Current Series</a>
        </button>
        <div class="container py-5">
            <CardsContainer>
            </CardsContainer>
        </div >
        <div class="load">
            <button><a href="">Load more</a></button>
        </div>
        
    </div>
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
.content{
    background-color: black;
    color: white;
    padding: 1rem 0;
    button{
        margin-left: 15%;
        transform: translate(0, -100%);
        background-color: #0282f9;
        border: 0;
        a{
            padding: 0.5rem 1rem;
            text-transform: uppercase;
            text-decoration: none;
            color: white;
            font-weight: 600;
        }
    }
    .container{
        display: flex;
        width: 70%;
    }
}
.load{
    padding: 2rem 0;
    display: flex;
    justify-content: center;
    button{
        margin: 0;
        padding: 0.5rem 4rem;
        background-color: #0282f9;
        border: none;
        a{
            text-decoration: none;
            color: white;
            text-transform: uppercase;
            font-weight: 600;
        }
    }
}

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