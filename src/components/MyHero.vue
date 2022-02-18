<template>
   
    <div class="jumbotron">

        <div class="jumbotron-items">

            <img src="../assets/vue-jumbo.png" alt="vue image">
            <h2>Standard Tooling for Vue.js Development </h2>
            <button>Get Started</button> 
            
        </div>
        
    </div>
        
    
</template>

<script>
    export default {
        name: 'MyHero',
    }

</script>

<style scoped>
.jumbotron{
    width: 100%;
    max-height: 600px;
    background-color: #f8f8f8;
    color: #435365;
    display: flex;
    justify-content: center;
    
}
.jumbotron-items{
    max-width: 1280px;
    width: 100%;
    position: relative;
}
img{
    width: 100%;
    object-fit: cover;
    
}
h2{
    position: absolute;
    font-size: 2em;
    left: 20px;
    bottom: 50%;
    transform: translateY(+50%);
    width: 30%;
}

button{
    position: absolute;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    background-color: #4db986;
    color: #fff;
    border: none;
    border-radius: 10px;
    padding: 10px;
    cursor: pointer;
}
    
    
</style>