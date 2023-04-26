<script>

export default {
 name: "AppHeader",
 data() {
  return {
    links: [
      {
        text: "HOME",
        url: "#",
        current: false
      },
      {
        text: "ABOUT",
        url: "#",
        current: true
      },
      {
        text: "SERVICES",
        url: "#",
        current: false
      },
      {
        text: "SHOWCASE",
        url: "#",
        current: false
      },
      {
        text: "BLOG",
        url: "#",
        current: false
      },
      {
        text: "CONTACT",
        url: "#",
        current: false
      },
    ]
  }
 }
}

</script>

<template>
    
    <header>
        <!-- Header top -->
        <div class="header-top py-1">
            <div class="container">
                <div class="d-flex justify-content-between">
                    <div class="telephone-section d-flex">
                        <span class="me-3"><i class="fa-solid fa-phone"></i></span>
                        <div>(001)88451234 88455438 </div>
                    </div>
                    <div class="social-logos d-flex">
                        <span><i class="fa-brands fa-facebook-f"></i></span>
                        <span class="ms-3 me-3"><i class="fa-brands fa-twitter"></i></span>
                        <span><i class="fa-brands fa-pinterest-p"></i></span>
                    </div>
                </div>
            </div>
        </div>
        <!-- /Header top -->

        <!-- Header bottom -->
        <div class="header-bottom py-3">
            <div class="container d-flex justify-content-between">
                
                <div class="header-logo">
                    <img src="../assets/img/cropped-Group-39-2x.png" alt="logo">
                </div>
               
                
                <nav class="navigation">
                    <ul class="header-nav d-flex">
                        <li v-for="link in links">
                            <a :href="link.url">{{ link.text }}</a>
                        </li>
                    </ul>
                </nav>

                <div class="header-actions d-flex align-items-center">
                    <button class="green-button me-4">PURCHASE</button>
                    <div class="search">
                        <span><i class="fa-solid fa-magnifying-glass"></i></span>
                    </div>
                </div>

            </div>
        </div>
        <!-- /Header bottom -->

    </header>


</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.header-top {
    background-color: #3C3C3C;
    color: white;
    font-size: 0.9rem;
}

.header-nav {
    list-style-type: none;
    li {
        margin: 0.5rem;
        a {
            text-decoration: none;
            color: #433D3D;
        }
    }
}

.green-button {
    background: $green-gradient;
    color: white;
    border-radius: 30px;
    border: none;
    padding: 0.8rem 2rem;
}
.search i {
    color: #04DAA4
}


</style>