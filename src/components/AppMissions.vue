<script>

export default {
    name: "AppMissions",
}
</script>

<template>
    <!-- Missions Section -->
    <div class="missions">
        <img class="faded-image"  alt="">
        <img class="woman-image" src="../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
        <div class="mission-text">
            <div class="mission-title">
                <p>learn more about our <span>missions</span></p>
            </div>
            <div class="lines d-flex my-4">
                <hr class="small-line me-1">
                <hr class="big-line">
            </div>
            <div class="mission-paragraph">
                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large languace ocean. Separated they live in Bookmarksgrove.</p>
            </div>
            <button class="green-button me-4">VIEW ALL</button>
        </div>
    </div>
    <!-- /Missions Section -->

</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.missions {
    background-color:#F9F9F9;
    padding-top: 6rem;
    padding-bottom: 10rem;
    position: relative;
}
.faded-image {
    background-image:
    linear-gradient(to right, rgba(#99E15E, 0.52), rgba(#04DAA4, 0.73)),
    url('../assets/img/busy-architect-PYVKWM4-1024x872.jpg');
    width: 40%;
    height: 400px;
    background-repeat: no-repeat;
    background-size: cover;
    border-top-right-radius: 20px;
    border: none;
}

.woman-image {
    width: 30%;
    position: absolute;
    top: 25%;
    left: 13%;
    border-radius: 20px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}

.mission-text {
    position:absolute;
    top: 25%;
    right: 20%;
    width: 20%
}

span {
    color: $secondary-text-color;
}
.mission-title {
    font-size: 3rem;
    line-height: 3.2rem;
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
.green-button {
    background: $green-gradient;
    color: white;
    border-radius: 30px;
    border: none;
    padding: 0.8rem 2rem;
}
.mission-paragraph {
    font-size: 0.7rem;
}
</style>