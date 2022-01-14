
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
        title: ''
        }
    }
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