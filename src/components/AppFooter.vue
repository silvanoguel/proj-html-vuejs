<script>

export default {
    name: "AppFooter",
}
</script>


<template>

    <footer>

        <div class="container">

            <!-- Footer Top -->
            <div class="footer-top">
                <div class="row g-4">

                    <div class="col-3 footer-logo-section">
                        <div class="footer-logo">
                            <img src="../assets/img/cropped-Group-39-2x.png" alt="logo">
                        </div>
                        <div class="footer-logo-text pt-3">
                            <p>While the lovely valleyteems with vapour around me, and the meridian sun strikes the upper surface of the impenetrable foliage of my trees. While the lovely valller teems with vapour around me.</p>
                        </div>

                    </div>

                    <div class="col-3 footer-links">
                        <div class="footer-links-title">
                            <span>QUICK LINKS</span>
                        </div>
                        <div class="lines d-flex my-2">
                            <hr class="small-line me-1">
                            <hr class="big-line">
                        </div>
                        <div class="links">
                          <ul class="d-flex flex-column align-items-center">
                            <li>Careers</li>
                            <li>News</li>
                            <li>Terms of use</li>
                            <li>Privacy Projects</li>
                            <li>About</li>
                            <li>contact</li>
                          </ul>
                        </div>
                    </div>


                    <div class="col-3 contact">
                        <div class="contact-title">
                            <span>CONTACT</span>
                        </div>
                        <div class="lines d-flex my-2">
                            <hr class="small-line me-1">
                            <hr class="big-line">
                        </div>
                        <div class="contact-info">
                            <p class="contact-name">Patricia Amedee 4401 Waldeck Street</p>
                            <p class="contact-adress">Grapevine Nashville, TX 76051</p>
                            <p class="contact-email pt-3">info@yourdomain.com</p>
                            <p class="contact-telephone pt-3">+99 (0) 1010 0000 888</p>
                        </div>
                    </div>


                    <div class="col-3 map">
                        <div class="map-title">
                            <span>LOCATION ON MAP</span>
                        </div>
                        <div class="lines d-flex my-2">
                            <hr class="small-line me-1">
                            <hr class="big-line">
                        </div>
                        <div class="map-image">
                            <img src="../assets/img/map.png" alt="map-image">
                        </div>
                    </div>
                </div>

            </div>
            <!-- /Footer Top -->

        </div>


        <!-- Footer Bottom -->
        <div class="footer-bottom py-3">
            <div class="container">
                <div class="d-flex justify-content-between">
                    <div class="telephone-section d-flex">
                        <span class="me-3"><i class="fa-regular fa-copyright"></i></span>
                        <div>PHLOX BUSINESS THEME. </div>
                    </div>
                    <div class="social-logos d-flex">
                        <span><i class="fa-brands fa-facebook-f"></i></span>
                        <span class="ms-3 me-3"><i class="fa-brands fa-twitter"></i></span>
                        <span><i class="fa-brands fa-pinterest-p"></i></span>
                    </div>
                </div>
            </div>
        </div>
        <!-- /Footer Bottom -->

    </footer>


</template>


<style scoped lang="scss">
@use '../styles/partials/variables' as *;

img {
    max-width: 100%;
}

footer {
    padding-top: 6rem;
}
.footer-top {
    padding-bottom: 6rem;
}

.footer-logo-text {
    font-size: 0.8rem;
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

.links li {
    list-style-type: none;
    font-size: 0.8rem;
}
.contact-info {
    font-size: 0.8rem;
}

.contact-adress,
.contact-email,
.contact-telephone {
   line-height: 0.08rem;
}

.footer-bottom {
    background-color: #3C3C3C;
    color:#888888;
    font-size: 0.8rem;
}

</style>