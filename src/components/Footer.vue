
<template>
<footer>
    <div class=" logo">  
        <div class="container">
            <ul class="col">
                <p>DC COMICS</p>
                <li><a href="">Characters</a></li>
                <li><a href="">Comics</a></li>
                <li><a href="">Movies</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">Games</a></li>
                <li><a href="">Videos</a></li>
                <li><a href="">News</a></li>
                <p>DC SHOP</p>
                <li><a href="">Shop DC</a></li>
                <li><a href="">Shop DC Collectibles</a></li>
            </ul>
            <ul class="col">
                <p>DC </p>
                <li><a href="">Terms Of Use</a></li>
                <li><a href="">Privacy Policy (New)</a></li>
                <li><a href="">Advertising</a></li>
                <li><a href="">Jobs</a></li>
                <li><a href="">Subscriptions</a></li>
                <li><a href="">CPSC Certificates</a></li>
                <li><a href="">Ratings</a></li>
                <li><a href="">Shop Help</a></li>
                <li><a href="">Contact Us</a></li>
            </ul>
            <ul class="col">
                <p>SITES</p>
                <li><a href="">DC</a></li>
                <li><a href="">DC UNIVERSE INFINITE</a></li>
                <li><a href="">DC Kids</a></li>
                <li><a href="">DC Shop</a></li>
                <li><a href="">MAD Magazine</a></li>
            </ul>  
        </div>
    </div>
    
    <div class="footer-bot ">
        <div class="container" >
            <div class="sign-up">
                <button>SIGN-UP NOW!</button>

            </div>
                <div class="social">
                    <ul>
                    <li><p>FOLLOW US</p></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                    <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                    </ul>
                </div>
            
        </div>
        
    </div>  
</footer>
</template>

<script>
export default {
    name: "Footer",
    data() {
        return {
            
        }
    },
}
</script>

<style lang="scss" scoped>
footer {
    background-repeat: repeat;
    background-position: bottom left;
    background-image: url(../assets/img/footer-bg.jpg);
    
    .logo { 
        background-image: url("../assets/img/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-position-x: 85%;
        background-position-y: 50%;
        .container {
        display: flex;
        position: relative;
        justify-content: flex-start;
    
    ul {
        list-style: none; 
        P{
            padding-top: 30px;
            color: white;
        }
        li{
            padding: 0.4em;
            a{
                text-decoration: none;
                color: gray;
            }
        }
    }     
            
        }

            
        
        
    }   
    .footer-bot {
        background-color: #303030;
        padding: 2em 0;
        z-index: 100;
        
        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            
            .sign-up {
                width: 100%;
                button {
                background-color: #303030; 
                color: white; 
                border: 2px solid #008CBA;
                padding: 10px;
                &:hover {
                background-color: #008CBA;
                color: white;
                    }
                }
            }
            .social {
                ul {
                    list-style: none;
                    display: flex;
                    justify-content: flex-end;
                    align-items: center;
                    gap: 1em;
                    p {
                        text-transform: uppercase;
                        font-size: 1.5em;
                        color: #0282F9;
                        
                    }
                }
            }
        }
    }
        
}
</style>
