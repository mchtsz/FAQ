<script setup lang=ts>
import { RouterLink } from "vue-router"
import Card from "@/components/Card.vue"
</script>

<template>
    <nav>
        <Card img="/Code.svg" title="IT spørsmål (koding, html, js)" link="/faq/programmering/" />
        <Card img="/Academic.svg" title="Eksamen spørsmål" link="/faq/eksamen/" />
        <Card img="/Question.svg" title="Køddespørsmål" link="/faq/kodd/" />
    </nav>
</template>

<style scoped lang=scss>
nav {
    padding: 2rem;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: 80vh;
}
</style>