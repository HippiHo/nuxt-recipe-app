<script setup lang="ts">

const params = useRoute().params

</script>

<template>
    <div>
        <h1 class="text-3xl">{{ params.id }}</h1>
    </div>
</template>
