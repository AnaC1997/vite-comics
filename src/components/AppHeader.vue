<script>

export default{
    name: "AppHeader",
    data(){
        return{
            menuLinks: [
                {
                    text: "CHATACTERS",
                    url: "#CHATACTERS",
                },
                {
                    text: "COMICS",
                    url: "#COMICS",
                },
                {
                    text: "MOVIES",
                    url: "#MOVIES",
                },
                {
                    text: "TV",
                    url: "#TV",
                },
                {
                    text: "GAMES",
                    url: "#GAMES",
                },
                {
                    text: "COLLECTIBLES",
                    url: "#COLLECTIBLES",
                },
                {
                    text: "VIDEOS",
                    url: "#VIDEOS",
                },
                {
                    text: "FANS",
                    url: "#FANS",
                },
                {
                    text: "NEWS",
                    url: "#NEWS",
                },
                {
                    text: "SHOP",
                    url: "#SHOP",
                }
                
            ]

        }
    },
    methods(){

    },
    mounted(){
        console.log("Componente AppHeader caricato")

    },

}

</script>

<template>
    <header>
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <div class="styleMenuLinks">
                <a v-for="link in menuLinks" :href="link.url">{{ link.text }}</a>
            </div>
            
        </nav>
    </header>
</template>

<style scoped>
nav{
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 1rem;
}

img{
    width: 80px;
    height: 80px;
}

.styleMenuLinks{
    display: flex;
    gap: 1rem;
}

a{
    text-decoration: none;
    color: black;
}



</style>