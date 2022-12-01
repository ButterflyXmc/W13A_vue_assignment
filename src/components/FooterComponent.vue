<template>
<!-- Footer content -->
    <div>
        <a href="mailto:abcdef@gmail.com">Send us your jokes to get featured on our website!</a>
    </div>
</template>

 <!-- Will be using this FooterComponent in the app.vue file -->
<script>
    export default {
        name : "FooterComponent",
    }
</script>

 <!-- Will only style the content in this FooterComponent file -->
<style scoped>
    a{
        color: white;
        font-size: 1.4em;
        background-color: rgba(0, 0, 0, 0.581);
        border: 2px solid blue;
        padding: 10px;
    }
</style>