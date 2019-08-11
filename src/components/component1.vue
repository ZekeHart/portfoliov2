<style scoped>
.demo {  background-color: rgb(96, 230, 230);
font-size: 3rem;}
</style>


<script>
export default {  name: 'component1',  
props: {    msg: String  }}
</script>


<template>  
    <div class="demo">    
        <h1>{{ msg }}</h1>  
    </div>
</template>