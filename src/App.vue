<template>
    <div class="container min-h-screen flex flex-col centered mx-auto">
		<main class="flex-grow p-4">
			<headerComponent/>
            <contentComponent/>
			<footerComponent/>
        </main>
    </div>
</template>

<script setup>
import headerComponent from './components/headerComponent.vue';
import contentComponent from './components/contentComponent.vue';
import footerComponent from './components/footerComponent.vue';
</script>

<style scoped>

</style>
