
<template>
  <footer>
    <div class="container">
     
      <ul class="col">
          <p>DC COMICS</p>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <p>DC COMICS</p>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
      </ul>
      <ul class="col">
          <p>DC COMICS</p>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
      </ul>
      <ul class="col">
          <p>DC COMICS</p>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
        <li><a href="">link</a></li>
      </ul>
      <div class=" logo">
          <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>

     
       
    </div>
    <div class="contatti ">
        <div class="container" >
            <button>SIGN-UP NOW!</button>
            
            <ul>
                <li><p>foolow us</p></li>
                <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                <li><img src="../assets/img/footer-youtube.png" alt=""></li>
            </ul>
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
    background-repeat: repeat-x;
    background-position: bottom left;
    background-image: url(../assets/img/footer-bg.jpg);
    .container {
      display: flex;
    //   padding-top: 40px;
      justify-content: flex-start;
      
      
      
      
      .col {
        flex-basis: calc(100% / 8); 
        position: relative;
        }
     
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
    .logo { 
             height: 30vh;
             position: absolute;
             left: 50%;
             bottom: 40%
            
            
        }
        img{
            width: auto;
            height:auto;
            
   
        }
        
        

        
    }
    .contatti{
            background-color: #303030;
            height: 150px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            
            // flex-basis: calc(100% / 2); 
            .container{
                ul{
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    
                    
                }

            }
        }
        p{
            color: white;
        }
        
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
</style>
