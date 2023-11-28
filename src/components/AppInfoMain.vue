<script>

export default{
    name: "AppInfoMain",
    data(){
        return{
            informazioni:[
                {
                    img: "src/assets/img/buy-comics-digital-comics.png",
                    text: "DIGITAL COMICS",
                },
                {
                    img: "src/assets/img/buy-comics-merchandise.png",
                    text: "DC MERCHANDISE",
                },
                {
                    img: "src/assets/img/buy-comics-subscriptions.png",
                    text: "SUSCRIPTION",
                },
                {
                    img: "src/assets/img/buy-comics-shop-locator.png",
                    text: "COMIC SHOP LOCATOR",
                },
                {
                    img: "src/assets/img/buy-dc-power-visa.svg",
                    text: "DC POWER VISA",
                }
            ]

        }
    },
    methods(){

    },
    mounted(){
        console.log("Componente AppInfoMain caricato")

    },

}

</script>

<template>
    <section class="styleInfoMain">
        <div class="card" v-for="info in informazioni">
            <img :src="info.img" alt="#">
            <p>{{ info.text }}</p>
        </div>
    </section>
</template>

<style scoped>

.styleInfoMain{
    background-color: #0082F9;
    color: white;
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-around;
    padding: 3rem;
}

.card{
    display: flex;
    gap: 0.5rem;
    align-items: center;
}

img{
    width: 60px;
    height: 60px;
}

</style>