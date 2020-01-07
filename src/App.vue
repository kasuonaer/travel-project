<template>
    <div id="app">
        <home-components></home-components>
    </div>
</template>

<script>
    import homeComponents from '@/components/home/home'
    export default {
        name: 'app',
        data(){
            return{

            }
        },
        components:{
            homeComponents
        }
    }
</script>

<style lang="less">

</style>
