<template>
    <div>
       <!-- {{image}} -->
        <TitleHero/>
    </div>
</template>
  
<script>
import TitleHero from './TitleHero.vue';
    export default {
        componets:{
        TitleHero
        },
        name: 'AppHero',
        data(){
            return{
                image : '../assets/img/fswd.png'
            }
        }
    }
</script>
  
<style lang="css" scoped>
div{
    width: 100%;
    height: 200px;
    position: relative;
    background-color: red
};
</style>