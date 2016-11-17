<template>
    <header class="header">
        <p class="title">Welcome to my homepage</h1>
        <p class="subtitle">My name is Donald Duck</p>
    </header>
</template>
<style lang="sass">
header{
    width:100%;
    height:50px;
    background:#303030;
    color:#ffffff;
    .title{
        font-size:15px;
    }
    .subtitle{
        font-size:10px;
        color:red;
    }
}
</style>
<script>
    export default{
        data(){
            return{
                header_text:'头部导航信息'
            }
        }
    }
</script>
