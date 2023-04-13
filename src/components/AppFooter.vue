<script>
export default {
    name: "AppFooter",
    data() {
        return {
            
        }
    }
}
</script>

<template>
  <div class="footer-top">
  </div>
  <div class="footer-bottom">
    <div class="container">
        <div class="bottom-left">
            <button><strong>SIGN UP NOW!</strong></button>
        </div>
        <div class="bottom-right">
            <div class="socials">
                <span><strong>FOLLOW US</strong></span>            
                    <ul>
                        <li><i class="fa-brands fa-facebook fa-lg"></i></li>
                        <li><i class="fa-brands fa-twitter fa-lg"></i></li>
                        <li><i class="fa-brands fa-youtube fa-lg"></i></li>
                        <li><i class="fa-brands fa-pinterest fa-lg"></i></li>
                        <li><i class="fa-solid fa-location-dot fa-lg"></i></li>
                    </ul>                
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.footer-bottom{
    background-color: #303030;
    .container{
        padding: 1rem 0;
        width: 70%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        button{
            color: white;
            background: #30303000;
            padding: 0.5rem 0.75rem;
            border: 2px solid #0282f9;
        }
        .bottom-right{
            span{
                color: #0282f9;
                font-size: 1.3rem;
            }
            .socials{
                display: flex;
                align-items: center;

                ul{ 
                    display: flex;   
                    align-items: center;           
                    list-style-type: none;
                    justify-content: space-between;

                    li{
                        padding: 0 0.25rem;
                        i{
                            font-size: 2rem;
                        }
                    }
                }
            }
            
        } 
    }
}

</style>