<script setup lang=ts>
import { RouterLink } from "vue-router"
</script>

<template>
    <nav>
        <RouterLink to="/faq/programmering">
            IT spørsmål (koding, html, js)
        </RouterLink>
        <RouterLink to="/faq/eksamen">
            Eksamen spørsmål
        </RouterLink>
        <RouterLink to="/faq/livsglede">
            Livsglede spørsmål
        </RouterLink>
        <RouterLink to="/faq/kodd">
            Kødde spørsmål
        </RouterLink>
    </nav>
</template>

<style scoped lang=scss>
nav {
    width: 100%;
    padding: 2rem;
    display: flex;
    justify-content: space-evenly;
    align-items: center;

    a {
        font-size: 24px;
        color: #000;
        text-decoration: none;
    }
}
</style>