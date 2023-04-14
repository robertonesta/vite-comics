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
    <div class="container">
        <div class="top-left">
            <div>
                <h4>DC COMICS</h4>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <h4>SHOP</h4>
                <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div>
                <h4>DC</h4>
                <ul>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <h4>SITES</h4>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
        <div class="top-right">
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>

    </div>
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
@use "node_modules/bootstrap/scss/bootstrap.scss";

.footer-top{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    
    .container{
        width: 70%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        
        .top-left{
            display: flex;
            color: white;
            ul{
                padding: 0;
                list-style-type: none;

                a{    
                    color: white;
                    text-decoration: none;
                }
            }
        }

    }
}
.footer-bottom{
    background-color: #303030;
    .container{
        padding: 1rem 0;
        width: 70%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        z-index: 3;
        
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