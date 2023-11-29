<script>

export default {
    name: "AppCard",
    props: ["cardsProps"],
    data() {
        return {};
    },
    methods() {
    },
    mounted() {
        console.log("Componente AppCard caricato");
    },

}

</script>

<template>
    <section class="container">
        <div v-for="card in cardsProps" class="card">
            <img :src="card.thumb" alt="">
            <p>{{ card.price }}</p>
            <p>{{ card.series }}</p>
            <p>{{ card.type }}</p>
        </div>
    </section>
</template>

<style scoped>

.container{
    background-color: black;
    width: 80%;
    min-height: 600px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
   
}
.card {
    background-color: black;
    color: white;
    width: 15%;
    padding: 1rem;

    
}

img {
    width: 100%;
    height: 40%;
}
</style>