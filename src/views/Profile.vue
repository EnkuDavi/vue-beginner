<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <div class="media d-flex">
                        <img src="../assets/logo.png" class="mr-3" alt="">
                        <div class="media-body">
                            <h5 class="mt-0">{{ firstName }} {{ lastName }}</h5>
                            <p class="">Will you do the same for me? It's time to face the music I'm no longer your muse.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.min.css'

export default {
    name: 'profile',
    data: function(){
        return {
            firstname: 'Enku',
            lastName: 'Davi'
        }
    },
    components: { }
}
</script>

<style scoped>
    .media{
        text-align: left;
    }
    img{
        border-radius: 20%;
        width: 100px;
        height: 80px;
    }

    .media-body{
        margin-left: 10px;
    }
</style>