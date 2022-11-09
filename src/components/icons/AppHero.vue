<template>
        <div class="jumbotron">
            <div class="container">
                <h1 class="display-3"><AppTitle/></h1>
                <div class="position">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f1/Vitejs-logo.svg/2078px-Vitejs-logo.svg.png" alt="">
                </div>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi vero recusandae quidem architecto tenetur quia, culpa ut voluptatem dolorum minima eos iste incidunt eum iure, ratione facilis porro! Laborum adipisci necessitatibus totam at vitae consequuntur, doloremque obcaecati incidunt vel alias numquam commodi eveniet. Ipsa alias numquam nulla totam, excepturi ducimus..</p>
            </div>
        </div>
</template>

<script>
import AppTitle from './AppTitle.vue';

export default {
    name: "AppHero",
    components: { AppTitle },
    data() {
        return {

        };
    },
}
</script>

<style lang="css">

</style>