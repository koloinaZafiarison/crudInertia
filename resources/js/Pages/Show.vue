<template>
   <div class="post__content ">
        <h1>{{post.title}}</h1>
        <p>{{post.author }}</p>
        <div>{{ post.content }}</div>

   </div>
</template>

<script setup>
    defineProps({
        post :Object
    })
</script>

