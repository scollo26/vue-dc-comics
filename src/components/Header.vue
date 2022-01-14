<template>
  <header>
    <div class="container ">
        <img src="../assets/img/dc-logo.png" alt="">
        
        <ul>
            <li><a href="#">Characters</a></li>
            <li ><a class="active" href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
        </ul>
    </div>
  </header>
</template>
<script>
export default {
    name: 'Header',
    data(){
        return{
            title: "lorem"
        }
    }

}
</script>
<style lang="scss" scoped>
.container {
    height: 10vh;
    font-size: 1em;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
        & > ul {
        list-style: none;
        display: flex;
        justify-content: center;
        align-items: center;
      li a {
        display: block;
        text-decoration: none;
        padding: 0.7em 1em ;
        transition: all 0.4s;
        color: black;
        height: 6em;
        &:hover,
        &:active,
        &.active {
        color: #0082F9;
        border-bottom: 3px solid #0082F9;
    
        }
      }
  }
}
</style>
