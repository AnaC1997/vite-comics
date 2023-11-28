<script>

export default {
    name: "AppMenuFooter",
    data() {
        return {

        }
    },
    methods() {

    },
    mounted() {

    },

}

</script>

<template>
    <footer>
        <!--Section info-->
        <section class="contenitore">
            <div class="contenuto">
                <span class="lista">
                    <h2>DC COMICS</h2>
                    <ul >
                        <li><a href="#">Charaters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li class="pB1"><a href="#">News</a></li>

                    </ul>

                    <h2>SHOP</h2>
                    <ul >
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop D Collectibles</a></li>
                    </ul>
                </span>

                <span class="lista">
                    <h2>DC</h2>
                    <ul >
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Add Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Suscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </span>

                <span class="lista">
                    <h2>SITES</h2>
                    <ul >
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </span>

                <span>
                    <img class="imgDc" src="../assets/img/dc-logo-bg.png" alt="#">
                </span>

            </div>

        </section>

        <!--Section icone social-->
        <section class="contenitoreIcone">
            <span>
                <button>SIGN-UP NOW!</button>
            </span>
            <span class="icone">
                <h4>FLOW US</h4>
                 <img src="src/assets/img/footer-facebook.png" alt="#">
                 <img src="src/assets/img/footer-periscope.png" alt="#">
                 <img src="src/assets/img/footer-pinterest.png" alt="#">
                 <img src="src/assets/img/footer-twitter.png" alt="#">
                 <img src="src/assets/img/footer-youtube.png" alt="#">

            </span>
          
         
        </section>

    </footer>
</template>

<style scoped>

/*****Style Section1 *******/
.contenitore {
    background-image: url("../assets/img/footer-bg.jpg");
    color: white;
    width: 100%;
    min-height: 300px;
    /*
    filter: grayscale(100%);
    color: white;*/
}


.contenuto {
    display: flex;
    justify-content: space-around;
    gap: 2rem;
}

h2{
    padding-bottom: 1rem;
}

a {
    text-decoration: none;
    color: inherit; /*Utilizza il colore ereditato dal contenitore */
}

a:hover {
    color: #585ded;
}

ul li {
    text-decoration: none;
    list-style: none;
   padding-bottom: 0.3rem;
}

.lista{
    padding-top: 2rem;
}

.imgDc{
    width: 350px;
    height: 350px;
   
 
}

.pB1{
    padding-bottom: 1rem;
}


/*****Style Section2 *******/
.contenitoreIcone{
    background-color: #303030;
    padding: 2rem;
    display: flex;
    justify-content: space-between;
   
}

button{
    padding: 1rem;
    border-color: #063d91;
    cursor: pointer;
    color: white;
    background-color: #303030;
    margin-left: 2rem;
}

button:hover{
    background-color: #0082F9;
}

h4{
    color: #1D64CC;
}
.icone{
    display: flex;
    gap: 0.5rem;
    align-items: center;
    margin-right: 2rem;
    cursor: pointer;
}

</style>