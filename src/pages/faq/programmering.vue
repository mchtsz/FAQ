<script setup lang=ts>
import Faq from "@/components/Faq.vue"
import pro from "@/assets/json/pro.json"
</script>

<template>
    <section>
    <Faq v-for="i of pro" :title="i.title" :description="i.description" />
    </section>
</template>

<style scoped lang=scss>
    section {
        height: 100%;
        padding: 2rem 0;
    }
</style>