<script setup lang=ts>
import { RouterLink } from "vue-router"
</script>

<template>
    <nav>
        <RouterLink to="/">
            FAQ FOR 1 IM ELEVER
        </RouterLink>
    </nav>
</template>

<style scoped lang=scss>
nav {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 100%;
    height: 80px;
    box-shadow: #000 0 0 .05rem;

    a {
        transition: 0.2s ease-in-out;
        font-size: 20px;
        font-weight: 600;
        color: #000;
        text-decoration: none;

        &:hover {
            text-decoration: underline;
            transform: scale(1.1)
        }
    }


}
</style>