<template>
    <div class="app">
        <h1>Vuex试验</h1>
        <div>来自App的msg:{{msg}}</div>

        <display></display>
        <increment></increment>
    </div>

</template>
<script>
    import store from './vuex/store.js';
    import display from './components/Display.vue';
    import increment from './components/Increment.vue';
    export default{
        data(){
            return {
                msg:"App总组件msg"
            }
        },
        components:{
            display,
            increment
        },
        store
    }
</script>
<style>
.app{
    width: 100%;
    text-align: center;
    height:200px;
    color:red;
    font-weight: bold;
}
</style>