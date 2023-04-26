<script>

export default {
    name: "AppBanner",
}
</script>

<template>
    <div class="banner">

        <div class="container">
            <div class="banner-text py-5">
              <p class="fw-lighter"><span class="subtitle">17 YEARS OF EXPERIENCE</span></p>
              <p class="banner-title fw-bold">Focus on Your <span class="secondary">Business</span></p>
              <div class="lines d-flex my-4">
                <hr class="small-line me-1">
                <hr class="big-line">
              </div>
              <p class="banner-paragraph">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large languace ocean. Separated they live in Bookmarksgrove.</p>
              <button class="black-button my-5">READ MORE</button>
              <p>FACEBOOK - INSTAGRAM - YOUTUBE - TWITTER</p>
            </div>

        </div>
      

        <!-- <img src="../assets/img/Group-35-2x.png" alt=""> -->
    </div>
</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.banner {
    // position: relative;
    // width: 100%;
    background-color: #FAFAFA;
}

img {
    // position: absolute;
    // left: 70%;
    // width: 70%;
    // height: 70%;
    // object-fit: cover;
    // object-position: center;
}

.banner-text {
    // position: absolute;
    width: 30%;
    .black-button {
        background: $black-gradient;
        color: white;
        border-radius: 30px;
        border: none;
        padding: 0.8rem 2rem;
    }
    .subtitle {
        color: $secondary-text-color;
    }
    .banner-title {
        font-size: 3rem;
        .secondary {
            color: $secondary-text-color;
        }
    }
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
.banner-paragraph {
    font-size: 0.8rem;
}
</style>