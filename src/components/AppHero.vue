<script>
    import AppTitle from '../components/AppTitle.vue'
    
    export default{
        name: 'AppHero',
        components:{
        AppTitle,
        }
    }
</script>

<template>
    <div id="hero">
        <AppTitle/>
    </div>
</template>

<style scoped lang="css">

#hero {
    width: 100%;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: center;
    background-image: url(../../public/img/bg-hero.jpg);
}

</style>


