<template>
<!-- Body content -->
    <div>
        <h2>Why did the PowerPoint Presentation cross the road?</h2>
        <p>To get to the other slide.</p>

        <h2>How does a computer get drunk?</h2>
        <p>It takes screenshots.</p>

        <h2>Why did the computer show up at work late?</h2>
        <p>It had a hard drive.</p>

        <h2>What do cats and programmers have in common?</h2>
        <p>When either one is unusually happy and excited, 
            it's because they found a bug.</p>

        <h2>Knock, knock. Who's There?</h2>
        <p>Very long pause….“Java.”</p>

        <h2>What is the most used language in programming?</h2>
        <p>Profanity.</p>
    </div>
</template>

 <!-- Will be using this BodyComponent in the app.vue file -->
<script>
    export default {
        name : "BodyComponent"
    }
</script>

 <!-- Will only style the content in this BodyComponent file-->
<style scoped>
    div{
        background-image: url(https://i.pinimg.com/736x/f5/94/15/f59415b9c0ad251ab6e7ec6ab7ea1ee3.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        color: white;
    }

    h2{
        border: rgba(255, 255, 255, 0.615) solid 2px;
        background-color: rgba(16, 16, 32, 0.384);
        font-size: 2.5em;
    }

    p{
        background-color: rgba(255, 255, 255, 0.263);
        font-size: 1.8em;
        
    }

    
</style>