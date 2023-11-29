<script setup>
import AppHeader from './components/AppHeader.vue'
import AppJumbo from './components/AppJumbo.vue'
import AppContent from './components/AppContent.vue'
import AppLinks from './components/AppLinks.vue'
import AppIndex from './components/AppIndex.vue'
import AppSignFollow from './components/AppSignFollow.vue'
</script>

<template>
    <div>
        <AppHeader />
        <AppJumbo />

        <main>
            <AppContent />
            <AppLinks />
        </main>

        <footer>
            <AppIndex />
            <AppSignFollow />
        </footer>

    </div>
</template>

<style scoped></style>
