<script setup lang="ts">
useHead({
    title: "Jira software",
});
</script>

<template>
    <!-- HERO SECTION  -->
    <section class="flex items-center justify-between h-[100vh] pt-[10vh] gap-4 bg-gradient-to-tr from-white dark:from-black 
    to-blue-500 dark:to-blue-800">
        <div class="pl-20 flex flex-col space-y-3">
            <h1 class="text-5xl">Move fast, stay aligened and build better - together</h1>
            <p>The #1 software development tool used by agile teems</p>
            <NuxtLink to="/auth">
                <UButton color="blue" >Try it free</UButton>
            </NuxtLink>
        </div>
        <NuxtImg src="/hero.webp"/>
    </section>
</template>
