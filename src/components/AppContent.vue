<script>
export default {
    name: "AppContent"
}
</script>

<template>
    <section>
        <div class="container">
            <p> -- Content goes here -- </p>
        </div>
    </section>
</template>

<style scoped>

section {
    background-color: #1C1C1C;
    color: white;
}
.container {
    width: 1100px;
    margin: 0 auto;
    min-height: 130px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

p {
    font-weight: 600;
    font-size: 25px;
}
</style>