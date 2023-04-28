<script>

export default {
    name: "AppProjects",
}
</script>

<template>

    <div class="projects">
        <div class="container">
            <!-- Project text -->
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
            <!-- Project text -->
            <!-- Project images -->
            <div class="projects-images">
                <div class="row g-1">
                    <div class="col-3">
                        <img src="../assets/img/ina-soulis-227104-unsplash-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/355H-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/business-competition-PB366D8-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="">
                    </div>
                    <div class="col-3">
                        <img src="../assets/img/cody-davis-253928-unsplash-1024x1024.jpg" alt="">
                    </div>
                </div>
            </div>
            <!-- /Project images -->
            <!-- Button -->
            <div class="projects-button text-center pt-5">
                <button class="green-button">READ MORE</button>
            </div>
            <!-- /Button -->
        </div>
    </div>

</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

img {
    max-width: 100%;
}
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
.green-button {
    background: $green-gradient;
    color: white;
    border-radius: 30px;
    border: none;
    padding: 0.8rem 2rem;
}

</style>