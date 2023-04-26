<script>

export default {
    name: "AppMissions",
}
</script>

<template>

    <div class="missions">

    <img class="faded-image"  alt="">

    </div>


</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.missions {
    background-color: grey;
    padding-top: 6rem;
    padding-bottom: 10rem;
}
.faded-image {
    background-image:
    linear-gradient(to right, rgba(#99E15E, 0.52), rgba(#04DAA4, 0.73)),
    url('../assets/img/busy-architect-PYVKWM4-1024x872.jpg');
    width: 40%;
    height: 400px;
    background-repeat: no-repeat;
    background-size: cover;
}


</style>