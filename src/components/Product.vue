<template>
<div>
    <img id="small" :src="img" :alt="alt">
    <div>
        <h2>{{alt}}</h2>
    </div>
</div>
        
</template>

<script>
export default {
    name: "Product",
    props: ["img", "alt"],
}
</script>

<style lang="scss" scoped>
img{
                
    width: 80%;
    padding-top: 40px;
                
}


</style>