<script>

export default {
    name: "AppClients",
}
</script>

<template>

    <div class="clients">

        <div class="container">
            <!-- Work Actions -->
            <div class="work-actions d-flex">
                <!-- Input Card -->
                <div class="input-section text-center py-5 me-3 d-flex flex-column">
                    <div class="input-text">
                        <span>Are you Ready?</span>
                    </div>
                    <div class="input-title pb-5">
                        <span>Start a New Project</span>
                    </div>
                    <div class="custom-input">
                        <input type="text" class="custom-search-input " placeholder="Enter Your Email Adress">
                        <button class="custom-search-botton" type="submit">SUBMIT</button>  
                    </div>
                </div>
                <!-- /Input Card -->
                <!-- Start now card -->
                <div class="work-section text-center py-5 me-3 d-flex flex-column">
                    <div class="work-text">
                        <span>What Are You Waiting for?</span>
                    </div>
                    <div class="work-title pb-5">
                        <span>Let's Talk About Work</span>
                    </div>
                    <div class="work-button">
                        <button class="black-button">START NOW</button> 
                    </div>
                </div>
                <!-- /Start now card -->
            </div>
            <!-- /Work Actions -->

            <!-- Clients -->
            <div class="row d-flex align-items-center text-center">
                <div class="col-2">
                    <img src="../assets/img/client-1-2x.png" alt="">
                </div>
                <div class="col-2">
                    <img src="../assets/img/client-9-2x.png" alt="">
                </div>
                <div class="col-2">
                    <img src="../assets/img/client-7-2x.png" alt="">
                </div>
                <div class="col-2">
                    <img src="../assets/img/client-3-2x.png" alt="">
                </div>
                <div class="col-2">
                    <img src="../assets/img/client-4-2x.png" alt="">
                </div>
                <div class="col-2">
                    <img src="../assets/img/client-5-2x.png" alt="">
                </div>
            </div>
            <!-- /Clients -->
        </div>
    </div>
</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.clients {
    padding-top: 16rem;
    padding-bottom: 8rem;
    background-color: #F9F9F9;
    position: relative;
}
img {
    width: 90px;
}

.work-actions {
    position: absolute;
    bottom: 80%;
    width: 100%;
}

.input-section {
    width: 40%;
    background: $black-gradient;
    border-radius: 10px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    align-items: center;
}
.work-section {
    width: 40%;
    background: $green-gradient;
    border-radius: 10px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    align-items: center;
}

.input-text {
    font-size: 0.7rem;
    color:#929292
}
.input-title {
    font-size: 1.8rem;
    color: white;
}
.work-text {
    font-size: 0.7rem;
    color: white;
}
.work-title {
    font-size: 1.8rem;
    color: white;
}
.custom-input {
  position: relative;
  width: 300px;
}
.custom-search-input {
  width: 100%;
  border-radius: 100px;
  padding: 10px 100px 10px 20px; 
  line-height: 1;
  outline: none;
  background-color:#3F3F3F;
  color: white;
  font-size: 0.8rem;
}
.custom-search-botton {
  position: absolute;
  right: 3px; 
  top: 3px;
  bottom: 3px;
  border: 0;
  color: #AFAFAF;
  font-size: 0.8rem;
  background-color:#3F3F3F;
  outline: none;
  margin: 0;
  padding: 0 10px;
  border-radius: 100px;
  z-index: 2;
}

.black-button {
    background: $black-gradient;
    color: white;
    border-radius: 30px;
    border: none;
    padding: 0.8rem 2rem;
    font-size: 0.7rem;
}

</style>