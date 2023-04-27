<script>

import AppHeader from "./components/AppHeader.vue";
import AppBanner from "./components/AppBanner.vue";
import AppCta from "./components/AppCta.vue";
import AppMissions from "./components/AppMissions.vue";
import AppProjects from "./components/AppProjects.vue";
import AppPrices from "./components/AppPrices.vue";



export default {
    components: {
        AppHeader,
        AppBanner,
        AppCta,
        AppMissions,
        AppProjects,
        AppPrices,
    }
}

</script>

<template>

    <AppHeader />
    <AppBanner />
    <AppCta />
    <AppMissions />
    <AppProjects />
    <AppPrices />

</template>

<style lang="scss">
@use "./styles/general.scss" as *;
</style>
