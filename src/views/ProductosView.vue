<script setup>
    import { useRoute } from "vue-router";
    import Productos from "@/components/Productos.vue";

    const route = useRoute()
    const categoria = route.params.categoria
</script>

<template>
    <Productos :categoria="categoria" />
</template>