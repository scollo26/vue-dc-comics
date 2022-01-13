
<template>
  <main>
    <div class="black">
        <div class="container ">
            <h1>Content goes here</h1>
        </div>
    </div>
    <div class="">
        <ul>
            <li>
                
                 <img src="https://www.dccomics.com/sites/all/themes/dc_comics_bp/images/buy-bar-DCUI.svg" alt="">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
               <img src="https://www.dccomics.com/sites/all/themes/dc_comics_bp/images/buy-bar-DCshop.svg" alt="">
                <p>DC MERCHANDISE</p>
            </li>
            <li>
                <img src="https://www.dccomics.com/sites/all/themes/dc_comics_bp/images/buy-bar-subscription.svg" alt="">
                <p>SUBSCRIPTION</p>
            </li>
            <li>
                <img src="https://www.dccomics.com/sites/all/themes/dc_comics_bp/images/buy-bar-locator.svg" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </li>
        </ul>
        
        
        
        
        
        
        
        
    </div>
  </main>
</template>

<script>
export default {
    name: 'Main',
//   data() {
//     return {
//       title: 'Lista Prodotti'
//     }
//   }
}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
     main {
    // height: 500px;
    color: white;
    
    div{
        background-color: black;
         
        
    }
    h1 {
      font-size: 2em;
      padding: 30px;
      
    }
    div{
        
        ul {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color:#0082F9;
    
        li {
            padding: 3em;
            img{
                vertical-align: middle;
            }
            a {
         display: block;
         text-decoration: none;
         padding: 5em ;
         
         
         
            }
            p{
                display: inline;
            }
        }
    }
        
    }
     
  }
</style>