<template>
        <div>
            <h1>{{title}}</h1>
            <p>{{paragraf}}</p>
        </div>
</template>
  
<script>
    export default {
        name: 'TitleHero',
        data(){
            return{
                title: 'I am Angelo',
                paragraf: 'And I\'m a Full Stack Web Developer'
            }
        }
    }
</script>
  
<style lang="css" scoped>
div {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: black;
} 
</style>