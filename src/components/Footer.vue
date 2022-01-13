
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
                <p>DC SHOP</p>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
            </ul>
            <ul class="col">
                <p>DC </p>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
            </ul>
            <ul class="col">
                <p>SITES</p>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
                <li><a href="">link</a></li>
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
  name: 'Footer'
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
