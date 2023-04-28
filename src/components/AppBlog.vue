<script>

export default {
    name: "AppBlog",
}
</script>


<template>

    <div class="blog">

        <div class="container">

            <div class="blog-title d-flex justify-content-center">

                <p>Latest News & Our <span>Blog</span></p>

                <div class="lines d-flex my-4">
                    <hr class="small-line me-1">
                    <hr class="big-line">
                </div>

            </div>

            <div class="lines d-flex my-4">
                <hr class="small-line me-1">
                <hr class="big-line">
            </div>
            
            
            <div class="posts row g-4">

                <div class="post col-4">
                    <img src="../assets/img/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg" alt="">
                    <div class="post-text p-3">
                        <div class="post-date">
                            <span class="ps-4">May 24, 2018 -by Alex</span> 
                        </div>
                        <div class="post-title ps-1">
                            <span class="big-dot pe-2"><i class="fa-solid fa-circle"></i></span> 
                            <span class="post-title-text">Marketing Ideas</span>
                        </div>
                    </div>
                </div>

                <div class="post col-4">
                    <img src="../assets/img/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg" alt="">
                    <div class="post-text p-3">
                        <div class="post-date">
                            <span class="ps-4">May 24, 2018 -by Alex</span> 
                        </div>
                        <div class="post-title ps-1">
                            <span class="big-dot pe-2"><i class="fa-solid fa-circle"></i></span> 
                            <span class="post-title-text">Rest During Working Hours</span>
                        </div>
                    </div>
                </div>

                <div class="post col-4">
                    <img src="../assets/img/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg" alt="">
                    <div class="post-text p-3">
                        <div class="post-date">
                            <span class="ps-4">May 24, 2018 -by Alex</span> 
                        </div>
                        <div class="post-title ps-1">
                            <span class="big-dot pe-2"><i class="fa-solid fa-circle"></i></span> 
                            <span class="post-title-text">Develop Your Startup Idea</span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="posts-button text-center">
                <button class="black-button">VIEW ALL POST</button>
            </div>
           

        </div>
    </div>


</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;


.blog {
    padding-top: 7rem;
    padding-bottom: 5rem;
}
.lines {
    justify-content: center;
}
.blog-title {
    font-size: 3rem;
}

.small-line {
    background-image: $green-gradient; 
    height: 5px; 
    border: 0;
    border-radius: 5px;
    width: 1%;
    opacity: 1;
}
.big-line {
    background-image: $green-gradient; 
    height: 5px; 
    border: 0;
    border-radius: 5px;
    width: 5%;
    opacity: 1;
}
span {
    color: $secondary-text-color;
}
.post {
    position: relative;
}
.post-text {
    width: 80%;
    position: absolute;
    top: 85%;
    left: 11%;
    background-color: white;
    border-radius: 5px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    .post-date span{
        font-size: 0.7rem;
        color: #BDB2AA;
    }
}

.post-title-text {
    color: black;
}

.big-dot {
    font-size: 0.6rem;
}

img {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    position: relative;
}
.posts-button {
    padding-top: 8rem;
}
.black-button {
    background: $black-gradient;
    color: white;
    border-radius: 30px;
    border: none;
    padding: 0.8rem 2rem;
}


</style>