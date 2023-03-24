

<template>
    <div class="container">
        <AppTitle/>
        <Jumbotron/>

    </div>
    

</template>

<script>
    import AppTitle from './components/AppTitle.vue';
    import Jumbotron from './components/Jumbotron.vue';

    export default {

        components : {
            AppTitle,
            Jumbotron,
        }
    }


</script>

<style>

.container {
    background-color: rgb(209, 209, 250);
    width: 1170px;
    margin: auto;
    text-align: center;
}

</style>