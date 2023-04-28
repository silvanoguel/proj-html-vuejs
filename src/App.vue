<script>

import AppHeader from "./components/AppHeader.vue";
import AppBanner from "./components/AppBanner.vue";
import AppCta from "./components/AppCta.vue";
import AppMissions from "./components/AppMissions.vue";
import AppProjects from "./components/AppProjects.vue";
import AppPrices from "./components/AppPrices.vue";
import AppChat from "./components/AppChat.vue";
import AppTestimony from "./components/AppTestimony.vue";
import AppBlog from "./components/AppBlog.vue";
import AppClients from "./components/AppClients.vue";
import AppFooter from "./components/AppFooter.vue";




export default {
    components: {
    AppHeader,
    AppBanner,
    AppCta,
    AppMissions,
    AppProjects,
    AppPrices,
    AppChat,
    AppTestimony,
    AppBlog,
    AppClients,
    AppFooter, 
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
    <AppChat />
    <AppTestimony />
    <AppBlog />
    <AppClients />
    <AppFooter />
    
</template>

<style lang="scss">
@use "./styles/general.scss" as *;
</style>
