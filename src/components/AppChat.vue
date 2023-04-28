<script>

export default {
    name: "AppChat",
}
</script>

<template>
    <!-- Chat Section -->
    <div class="chat">

        <div class="container d-flex">
            <!-- Chat Text -->
            <div class="chat-text me-5">
                <div class="chat-title">
                    <p>With <span>Live Chat 24/7</span> support</p>  
                </div>    
                <div class="lines d-flex my-4">
                    <hr class="small-line me-1">
                    <hr class="big-line">
                </div>
                <div class="chat-paragraph">
                    <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics.</p>
                </div>
            </div>
            <!-- /Chat Text -->
            <!-- Service Cards -->
            <div class="prices-cards d-flex justify-content-between">
                <div class="price-card d-flex flex-column align-items-center">
                    <div class="card-title mt-3 pt-3">
                        <p><b>DESIGNING</b></p>                     
                        <p class="card-subtitle pb-2">All Designs</p> 
                    </div>
                    <div class="card-rate py-3">
                        <p>$ <span class="rate">13</span> / Design</p>
                    </div>
                    <div class="card-option pt-4 text-center">
                        <p><span class="check me-2">✓</span>Creative Design Enabled</p>
                        <p><span class="check me-2">✓</span>Vibrant Color Usage</p>
                        <p><span class="check me-2">✓</span>Eye Catching Design</p>
                        <p><span class="check me-2">✓</span>Extreme Typography</p>
                        <p><span class="check me-2">✓</span>Exceptional Design</p>
                    </div>
                </div>
                <div class="price-card green d-flex flex-column align-items-center">
                    <div class="card-title mt-3 pt-3">
                        <p><b>DEVELOPMENT</b></p>                     
                        <p class="card-subtitle pb-2">WordPress Projects</p> 
                    </div>
                    <div class="card-rate py-3">
                        <p>$ <span class="rate">15</span> / Design</p>
                    </div>
                    <div class="card-option pt-4 text-center">
                        <p><span class="check me-2">✓</span>Creative Design Enabled</p>
                        <p><span class="check me-2">✓</span>Vibrant Color Usage</p>
                        <p><span class="check me-2">✓</span>Eye Catching Design</p>
                        <p><span class="check me-2">✓</span>Extreme Typography</p>
                        <p><span class="check me-2">✓</span>Exceptional Design</p>
                    </div>
                </div>
                <div class="price-card d-flex flex-column align-items-center">
                    <div class="card-title mt-3 pt-3">
                        <p><b>SEO</b></p>                     
                        <p class="card-subtitle pb-2">Web Products</p> 
                    </div>
                    <div class="card-rate py-3">
                        <p>$ <span class="rate">10</span> / Design</p>
                    </div>
                    <div class="card-option pt-4 text-center">
                        <p><span class="check me-2">✓</span>Creative Design Enabled</p>
                        <p><span class="check me-2">✓</span>Vibrant Color Usage</p>
                        <p><span class="check me-2">✓</span>Eye Catching Design</p>
                        <p><span class="check me-2">✓</span>Extreme Typography</p>
                        <p><span class="check me-2">✓</span>Exceptional Design</p>
                    </div>
                </div>
            </div>
            <!-- /Service Cards -->
        </div>
    </div>
    <!-- /Banner section -->
</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;


.chat {
    padding-top: 10rem;
    padding-bottom: 6rem;
    background-color: #F9F9F9;
    .chat-title {
        font-size: 3rem;
    }
    .chat-text {
        width: 35%;
    }
    .chat-paragraph {
        font-size: 0.7rem;
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
span {
    color: $secondary-text-color;
}

// Service Cards
.prices-cards {
    width: 100%;
}
.price-card {
    width: 25%;
    height: 100%;
    border-radius: 15px;
    background-color: black;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;

    .card-title {
        background-color: white;
        color: black;
        width: 100%;
        text-align: center;
        font-size: 1.3rem;
        line-height: 0.8rem;
    }
    .card-subtitle {
        color: grey;
        font-size: 0.8rem;
    }
    .card-rate {
        color: white;
        .rate {
            font-size: 2.2rem;
            color: white;
        }
    }
    .card-option {
        background-color: white;
        color: black;
        width: 100%;
        height: 100%;
        border-radius: 0px 0px 15px 15px;
        p {
            font-size: 0.8rem;
        }
        span {
            color: black;
        }
    }
}
.green {
    background: $green-gradient;
}

</style>