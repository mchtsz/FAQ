<script setup lang=ts>
import Faq from "@/components/Faq.vue"
import questions from "@/assets/json/questions.json"
</script>

<template>
    <Faq v-for="i of questions" :title="i.title" :start="i.start" :mid="i.mid" :end="i.end" />
</template>

<style scoped lang=scss></style>