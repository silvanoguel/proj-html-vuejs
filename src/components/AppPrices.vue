<script>

export default {
    name: "AppPrices",
}
</script>

<template>

    <div class="prices">
        <div class="container">

            <img class="faded-image" alt="">

            <div class="projects text-center">
                <div class="projects">
                    <div class="projects-number fw-lighter">280</div>
                    <div class="projects-text fw-lighter">PROJECTS</div>
                </div>

            </div>

            <div class="users-comments text-center">
                <div class="users-comments-number fw-lighter">+3,500</div>
                <div class="users-comments-text fw-lighter">USERS COMMENTS</div>
            </div>

            <div class="clients text-center">
                <div class="clients-number fw-lighter">100%</div>
                <div class="clients-text fw-lighter">HAPPY CLIENTS</div>
            </div>

            <div class="prices-text">
                <div class="prices-title">
                    <p>We <span>Love</span> What We Do</p>  
                </div>
                <div class="lines d-flex my-4">
                    <hr class="small-line me-1">
                    <hr class="big-line">
                </div>
                <div class="prices-paragraph">
                    <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large languace ocean. Separated they live in Bookmarksgrove. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large languace ocean. Separated they live in Bookmarksgrove.</p>
                </div>
                <div class="options">
                    <div class="word-option">
                        <span class="check">✓</span>
                        <span class="option-text"> far far away, behind the word mountains</span>
                    </div>
                    <div class="language-option">
                        <span class="check">✓</span>
                        <span class="option-text"> large language ocean</span>
                    </div>
                    <div class="countries-option">
                        <span class="check">✓</span>
                        <span class="option-text"> far from the countries Vokalia and Consonantia</span>
                    </div>

                </div>
            </div>

        </div>


    </div>


</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;


.prices {
    padding-top: 6rem;
    padding-bottom: 6rem;
    background-color: #F9F9F9; 
    position: relative;
}
.prices-text {
    position: absolute;
    top: 30%;
    left: 45%;
    width: 40%;
    padding: 60px 40px;
    background-color:white;
    border-radius: 10px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}

.faded-image {
    background-image:
    linear-gradient(to right, rgba(#04DA90, 0.9), rgba(#99E15E, 0.90)),
    url('../assets/img/person-with-long-curly-hair-PZ99QM2-2x.jpg');
    width: 50%;
    height: 500px;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 10px;
    border: none;
}
.projects {
    position: absolute;
    top: 30%;
    left: 25%;
    color: white;
}
.projects-number {
    font-size: 6rem;
}

.users-comments {
    position: absolute;
    top: 60%;
    left: 18%;
    color: white;
}

.users-comments-number {
    font-size: 2rem;
}

.clients {
    position: absolute;
    top: 60%;
    left: 33%;
    color: white;
}
.clients-number {
    font-size: 2rem;
}


.prices-title {
    font-size: 3rem;
}
.prices-paragraph {
    font-size: 0.7rem;
}

.small-line {
    background-image: $green-gradient; 
    height: 5px; 
    border: 0;
    border-radius: 5px;
    width: 3%;
    opacity: 1;
}

.big-line {
    background-image: $green-gradient; 
    height: 5px; 
    border: 0;
    border-radius: 5px;
    width: 10%;
    opacity: 1;
}
span {
    color: $secondary-text-color;
}

.word-option,
.language-option,
.countries-option {
    font-size: 0.7rem;
}
.option-text {
    color: black;
}

</style>