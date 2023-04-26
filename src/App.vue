<script>

import AppHeader from "./components/AppHeader.vue";
import AppBanner from "./components/AppBanner.vue";
import AppCta from "./components/AppCta.vue";
import AppMissions from "./components/AppMissions.vue";



export default {
    components: {
        AppHeader,
        AppBanner,
        AppCta,
        AppMissions
    }
}

</script>

<template>

    <AppHeader />
    <AppBanner />
    <AppCta />
    <AppMissions />

</template>

<style lang="scss">
@use "./styles/general.scss" as *;
</style>
