
<template>
    <main>
        <div class="jumbo">
        </div>
        <div class="current-button">
            <button class="button ">CURRENT SERIES</button>
        </div>
        <div class="content-section">
            <div class=" container">
                <div class="product" v-for="(product, index) in products" :key="index">
                    <img id="small" :src="product.thumb" alt="">
                    <div>
                        <h2>{{product.series}}</h2>
                    </div>

                </div>
                
                
            </div>
            <div class="load">
                    <button class="button ">LOAD MORE</button>
                </div>
            </div>
        <div class="">
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                DIGITAL COMICS
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    DC MERCHANDISE
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                SUBSCRIPTIONS
            </li>
            <li>
                <img id="small" src="../assets/img/buy-comics-shop-locator.png" alt="">
                COMIC SHOP LOCATOR
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                DC POWER VISA
            </li>
        </ul>
        
        
        
        
        
        
        
        
        </div>
    </main>
</template>

<script>
export default {
    name: 'Main',
    data() {
    return {
        products: [
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
    price: "$19.99",
    series: "Action Comics",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
    price: "$3.99",
    series: "American Vampire 1976",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
    price: "$16.99",
    series: "Aquaman",
    type: "graphic novel"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
    price: "$2.99",
    series: "Batgirl",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    price: "$3.99",
    series: "Batman",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    price: "$2.99",
    series: "Batman Beyond",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
    price: "$3.99",
    series: "Batman/Superman",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
    price: "$4.99",
    series: "Batman/Superman Annual",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
    price: "$5.99",
    series: "Batman: The Joker War Zone",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
    price: "$6.99",
    series: "Batman: Three Jokers",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
    price: "$4.99",
    series: "Batman: White Knight Presents: Harley Quinn",
    type: "comic book"
  },
  {
    thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
    price: "$16.99",
    series: "Catwoman",
    type: "graphic novel"
  }
] 
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
main {
    // height: 500px;
    color: white;
    .jumbo{
        background-image: url("../assets/img/jumbotron.jpg");
        height: 500px;
        background-size:cover ;
        img{
            
            height: 100%;
            width: 100%;
        }
    }
      .current-button{
            text-align: center;
            
            position: relative;
            
            
            .button {
                position: absolute;
                top: -20px;
                left: 120px;
                width: 180px;
                background-color: #0082F9; 
                color: white; 
                border: 2px solid #0082F9;
                padding: 10px;
                &:hover {
                background-color: #303030;
                color: white;
                }
            
            }  
        }
    
    .content-section{
        // display: flex;
        // flex-wrap: wrap;
        flex-direction: column;
        background-color: black;
        
       
        
        .container{
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            // gap: 1em;
            
            
            
            .product{
                 
                flex-basis: ((100% / 6) );
                height: 100%;
                #small{
                width: 80%;
                }
                
                img{
                
                width: 80%;
                padding-top: 40px;
                
                }
                
            } 
            
            
           
        }
        .load{
            text-align: center;
            padding-bottom: 30px;
            
            
            .button {
                width: 180px;
                background-color: #0082F9; 
                color: white; 
                border: 2px solid #0082F9;
                padding: 10px;
                &:hover {
                background-color: #303030;
                color: white;
                }
            
            }  
        }
        
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
                img {
                    margin-right: 10px;
                    width: 45px;
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
                #small{
                    width: 35px;
                }
        }
    }
        
    } 
}
</style>