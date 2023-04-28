<script>

export default {
    name: "AppTestimony",
}
</script>

<template>
    <!-- Testimony section  -->
    <div class="testimony">
        <div class="container d-flex flex-column justify-content-center align-items-center">
            <div class="icon">
                <i class="fa-solid fa-quote-left"></i>
            </div>
            <div class="testimony-paragraph py-4 text-center">
                <p>When it comes to barbequing, there are two main schools of thought for the techniques that you can use. Freshly scrambled eggs with applewood smoked bacon - are amazing!</p>
            </div>
            <div class="testimony-photo pb-2">
                <img src="../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
            </div>
            <div class="testimony-name pt-2">
                <span>LISSA DURBIN</span>
            </div>
            <div class="testimoy-role">
                <p>Client</p>
            </div>
        </div>
    </div>
    <!-- Testimony section  -->
</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.testimony {
    background-image: 
    linear-gradient(to right, rgba(#2E2E2E, 0.9), rgba(#2E2E2E, 0.9)), 
    url("../assets/img/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg");
    height: 500px;
    width: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.icon {
    padding-top: 6rem;
    font-size: 3rem;
    color: #00D8A6;
}

.testimony-photo img {
    width: 50px;
    height: 50px;
    object-fit: cover;
    border-radius: 50%;
}

.testimony-paragraph {
    color: white;
    width: 60%;
}

.testimony-name {
    color: #00D9A6;
}
.testimoy-role {
    color: white;
    font-size: 0.8rem;
}

</style>