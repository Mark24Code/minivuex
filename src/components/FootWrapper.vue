<template>
    <footer>
        <div>© 2016 Mark24, Inc</div>
        <div>Powerd By Vue.js</div>
    </footer>
</template>
<style>
footer{
    position: absolute;
    bottom: 0;
    width:100%;
    height: 50px;
    background:#776666;
    text-align: center;
    color:#ffffff;
}
</style>
<script>
    export default{
        data(){
            return{
                foot_msg:"msg底部信息"
            }
        }
    }
</script>
