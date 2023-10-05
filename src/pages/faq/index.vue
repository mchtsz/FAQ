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
        <RouterLink to="/faq/kodd">
            Køddespørsmål
        </RouterLink>
    </nav>
</template>

<style scoped lang=scss>
nav {
    padding: 2rem;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: 80vh;

    a {
        font-size: 24px;
        color: #000;
        text-decoration: none;

        &:hover {
            text-decoration: underline;
        }
    }
}
</style>