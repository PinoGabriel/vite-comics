<script>
export default {
    name: "AppLinks",
    data () {
        return {
            links: [
                {
                    img: "../assets/img/buy-comics-digital-comics.png",
                    nome: "DIGITAL COMICS"
                },
                {
                    img: "../assets/img/buy-comics-merchandise.png",
                    nome: "DC MERCHANDISE"
                },
                {
                    img: "../assets/img/buy-comics-subscriptions.png",
                    nome: "SUBSCRIPTION"
                },
                {
                    img: "../assets/img/buy-comics-shop-locator.png",
                    nome: "COMIC SHOP LOCATOR"
                },
                {
                    img: "../assets/img/buy-dc-power-visa.svg",
                    nome: "DC POWER VISA"
                },
            ]
        }
    }
}
</script>

<template>
    <section>
        <div class="container">
            <div v-for="element in links">
                <img :src="element.img" :alt="element.nome">
                <p>{{ element.nome }}</p>
            </div>
        </div>
    </section>
</template>

<style scoped>

section {
    background-color: #0282F9;
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
</style>










