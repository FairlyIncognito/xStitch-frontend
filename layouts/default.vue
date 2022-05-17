<template>
    <div class="bg-gray-100 min-h-screen text-gray-900">
        <Title>{{ title }}</Title>
        <header class="bg-white shadow text-lg px-6 py-6">
            <div
                class="container mx-auto flex items-center justify-between px-6"
            >
                <div>
                    <NuxtLink to="">Logo</NuxtLink>
                </div>

                <Nav />
            </div>
        </header>

        <slot />
    </div>
</template>

<script setup>
const title = useState("title", () => "Nuxt3 Demo");
</script>
