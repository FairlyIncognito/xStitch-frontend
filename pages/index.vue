<template>
    <div class="container mx-auto bg-gray-300 py-8">
        <Title>Home | {{ title }}</Title>
        <h1 class="font-bold text-gray-600 text-lg">Hello Index!</h1>
    </div>
</template>

<script setup>
const title = useState("title");
</script>
