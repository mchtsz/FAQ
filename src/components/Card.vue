<script setup lang=ts>
import { RouterLink } from "vue-router"
const { title, img, link } = defineProps<{
    title: string,
    img: string,
    link: string
}>()
</script>

<template>
    <section>
        <RouterLink :to="link">
            <img :src="img" alt="image">
            <h1>{{ title }}</h1>
        </RouterLink>
    </section>
</template>

<style scoped lang=scss>
section {
    display: flex;
    text-align: center;
    width: 300px;
    height: 300px;
    background: #fff;
    border: 1px solid #000;
    border-radius: 20px;
    transition: .2s ease-in-out;

    &:hover {
        transform: scale(1.1);
    }

    a {
        width: 100%;
        margin: auto 0;
        transition: .2s ease-in-out;
        font-size: 24px;
        color: #000;
        text-decoration: none;

        &:hover {
            transform: scale(1.1);
        }

        img {
            margin: 0 5rem;
            object-fit: cover;
        }

        h1 {
            text-align: center;
            width: 100%;
        }
    }

}
</style>