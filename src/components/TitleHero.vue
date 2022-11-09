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
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    color: #dedede;
    text-shadow: 10px 5px 10px #0f0559;
} 
</style>