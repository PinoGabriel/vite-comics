<script>
export default {
    name: "AppHeader",
    data() {
        return {
            navbar: [
                "CHARACTER", "COMICS", "MOVIES", "TV", "GAMES", "COLLECTIBLES", "VIDEOS", "FANS", "NEWS", "SHOP"
            ]
        }
    }
}
</script>

<template>
    <section>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <div>
                <a href="#" v-for="element in navbar">{{ element }}</a>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    background-color: white;
    margin-top: 50px;
}

img {
    display: block;
}

.container {
    width: 1100px;
    margin: 0 auto;
    min-height: 130px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

a {
    margin-left: 1rem;
    font-weight: 600;
    text-decoration: none;
    color: black;
}

a:hover{
    color: #0282F9;
}
</style>
