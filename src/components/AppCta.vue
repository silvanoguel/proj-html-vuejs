<script>

export default {
    name: "AppCta",
}
</script>

<template>

    <div class="cta">

        <div class="container">
            <div class="row">
                <div class="col-5">
                    <div class="cta-title pt-4">
                       <p>We are Here To Make your <span>Website</span> Look more <span>Elegant</span> And Stylish!</p> 
                    </div>
                    <div class="lines d-flex my-4">
                        <hr class="small-line me-1">
                        <hr class="big-line">
                    </div>
                    <button class="green-button me-4">VIEW ALL</button>

                </div>
                <div class="col-7">
                    <div class="container">
                        <div class="row g-3">
                            <div class="col">
                                <div class="ms_card">
                                    <div class="card-icon">
                                        <span><i class="fa-solid fa-gauge-high"></i></span>
                                    </div>
                                    <div class="card-title">
                                        <p>Speed Optimization</p>
                                    </div>
                                    <div class="card-text">
                                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                                    </div>
                                </div>
                            </div>

                            <div class="col">
                                <div class="ms_card">
                                    <div class="card-icon">
                                        <span><i class="fa-solid fa-cloud"></i></span>
                                    </div>
                                    <div class="card-title">
                                        <p>Cloud Solutions</p>
                                    </div>
                                    <div class="card-text">
                                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                                    </div>
                                </div>
                            </div>
                            <div class="w-100"></div>
                            <div class="col">
                                <div class="ms_card">
                                    <div class="card-icon">
                                        <span><i class="fa-solid fa-tablet"></i></span>
                                    </div>
                                    <div class="card-title">
                                        <p>Website Design</p>
                                    </div>
                                    <div class="card-text">
                                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="ms_card">
                                    <div class="card-icon">
                                        <span><i class="fa-solid fa-stopwatch"></i></span>
                                    </div>
                                    <div class="card-title">
                                        <p>Online Marketing</p>
                                    </div>
                                    <div class="card-text">
                                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>

    </div>

</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.cta {
    padding-top: 8rem;
    padding-bottom: 8rem;
}

.cta-title {
    font-size: 3rem;
}

.card-text {
    font-size: 0.7rem;
}

span {
    color: $secondary-text-color;
}

.ms_card {
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    padding: 2rem;
    border-radius: 5px;
}

.card-icon i {
    padding-bottom: 2rem;
    color: $secondary-text-color;
    font-size: 30px;
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

</style>