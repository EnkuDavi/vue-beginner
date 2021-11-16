<template>
    <div class="logos-wrapper">
        <h2>Find Best logo</h2>    
        <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/logo.png">
        </div><div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/logo.png">
        </div>
    </div>    
</template>

<script>
    export default {
        name: 'Logos'
    }
</script>

<style scoped>
    .logos-wrapper{
        width: 70%;
        overflow: hidden;
        margin: auto;
    }

    .item-logos{
        float: left;
        margin-left: 10px;
        margin-bottom: 10px;
        width: 100px;
        height: 100px;
    }

    .item-logos .logo{
        width: 80px;
        height: 80px;
    }
</style>