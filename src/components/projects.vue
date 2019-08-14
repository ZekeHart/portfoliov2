<style scoped>
.demo {  background-color: rgb(96, 230, 230);
font-size: 3rem;}
</style>


<script>
export default {  name: 'component1'}

var something = new Vue({
    el: '#something',
    data: {
        projects: [
        { name: 'AHABot' },
        { name: 'Calculator' }
        ]
    }
})
</script>


<template>  
    <div id="something">    
        <div v-for="project in projects">
            <h2>{{ project.name }}</h2>  
        </div>
    </div>
</template>

