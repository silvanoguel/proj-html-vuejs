<script>

export default {
    name: "AppProjects",
}
</script>

<template>

    <div class="projects">
        <div class="container">
            <div class="row">
                <div class="col-6 pe-5">
                    <div class="lines d-flex my-4">
                        <hr class="small-line me-1">
                        <hr class="big-line">
                    </div>
                    <div class="projects-title">
                        <p>Our recent <span>web design</span> & some examples of past <span>projects</span></p>
                    </div>
                    <div class="lines d-flex my-4">
                        <hr class="small-line me-1">
                        <hr class="big-line">
                    </div>
                </div>
                <div class="projects-paragraph d-flex col-6 pb-5">
                    <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large languace ocean. Separated they live in Bookmarksgrove. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large languace ocean. Separated they live in Bookmarksgrove.</p>
                </div>
            </div>
        </div>



    </div>


</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;


.projects {
    padding-top: 6rem;
    padding-bottom: 6rem;
}
.projects-title {
    font-size: 3rem;
}
.projects-paragraph {
    font-size: 0.7rem;
    align-items: end;
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


</style>