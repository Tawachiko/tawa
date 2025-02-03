<script setup lang="ts">
definePageMeta({
    title: 'ENGLISH',
    description: 'I am a 19 year old boy! MBTI is ISFJ-T!On this site, I would like to talk about my favorite anime!'
})
</script>

<template>
   <Intro />
    <Localization>
        <template #en>
            <h2>Hi! This is English</h2>
        </template>
        <template #ja>
            <h2>こんにちは! This is Japanese</h2>
        </template>
    </Localization>
</template>