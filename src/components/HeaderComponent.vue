<template>
    <!-- Header content -->
    <div>
        <h1>FUNNY TECH JOKES!</h1>
    </div>   
</template>

 <!-- Will be using this HeaderComponent in the app.vue file -->
<script>
    export default {
        name : "HeaderComponent"
    }
</script>

 <!-- Will only style the content in this HeaderComponent file -->
<style scoped>
    h1{
        background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuPPD6piLC_9FZtGjViHrNtvN-D8YPOsedc6FQhT_XJ3ZKAur_4d3S37_DZ4MonATNTsI&usqp=CAU);
        color: white;
        font-size: 4em;
    }
</style>