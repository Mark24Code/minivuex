<template>
    <div class="app">
        <head_wrapper></head_wrapper>
        <foot_wrapper></foot_wrapper>
    </div>

</template>
<script>
    import store from './vuex/store.js';
    import head_wrapper from './components/HeadWrapper.vue';
    import foot_wrapper from './components/FootWrapper.vue';
    export default{
        data(){
            return {
                msg:"App总组件msg"
            }
        },
        components:{
            head_wrapper,
            foot_wrapper
        },
        store
    }
</script>
<style>
body{
    margin:0;
    padding:0;
    min-height: 500px;
    position: relative;
}
.app{
    width: 100%;
    text-align: center;
    height:200px;
    color:red;
    font-weight: bold;
}
</style>