<script setup lang=ts>
import Faq from "@/components/Faq.vue"
import kodd from "@/assets/json/kodd.json"
</script>

<template>
    <section>
        <Faq v-for="i of kodd" :title="i.title" :description="i.description" />
    </section>
</template>

<style scoped lang=scss>
section {
    height: 100vh;
    padding: 2rem 0;
}
</style>