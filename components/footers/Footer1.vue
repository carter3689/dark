<template>
  <footer
    class="main-footer rel z-1"
    style="background-image: url(assets/images/footer/footer-bg-shape.png)"
  >
    <div class="container container-1290">
      <div class="footer-top pt-80 pb-60">
        <div class="row align-items-center">
          <div class="col-lg-4">
            <div class="footer-logo mb-20 wow fadeInRight delay-0-2s">
              <NuxtLink href="/"
                >Nexus Acumen</NuxtLink>
            </div>
          </div>
          <div class="col-lg-8 text-lg-end">
            <div class="social-style-four mb-20 wow fadeInLeft delay-0-2s">
              <a href="#"
                ><i class="fab fa-facebook-f"></i> <span>Facebook</span></a
              >
              <a href="#"
                ><i class="fab fa-linkedin"></i> <span>LinkedIn</span></a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-8">
          <div class="footer-left-content pt-80">
            <div class="lets-work mb-50 wow fadeInUp delay-0-2s">
              <img
                src="/assets/images/footer/lets-work.png"
                alt="Let's Work Man"
              />
              <span>Let’s Grow Your Business</span>
            </div>
            <div class="footer-contact-info wow fadeInUp delay-0-3s">
              <a class="theme-btn style-three" href="mailto:support@gmail.com"
                >support@gmail.com <i class="far fa-arrow-right"></i
              ></a>
              <a
                class="theme-btn style-three phone-number"
                href="callto:+000(123)45688"
                >+000 (123) 456 88 <i class="far fa-arrow-right"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="footer-right-content">
            <h4 class="footer-title wow fadeInUp delay-0-2s">Quick Links</h4>
            <div class="footer-widget widget_nav_menu">
              <ul class="list-style-two wow fadeInUp delay-0-3s">
                <li><NuxtLink href="about">Hear Our Story</NuxtLink></li>
                <li><NuxtLink href="pricing">Get Started with Pricing</NuxtLink></li>
                <li><NuxtLink href="contact">Contact Us?</NuxtLink></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <div class="row align-items-center">
          <div class="col-xl-8 col-lg-6">
            <div
              class="footer-bottom-menu pt-40 pb-35 rpb-0 wow fadeInRight delay-0-2s"
            >
              <ul>
                <li><NuxtLink href="about">About</NuxtLink></li>
                <li><NuxtLink href="pricing">Pricing</NuxtLink></li>
                <li><NuxtLink href="contact">Contact</NuxtLink></li>
              </ul>
            </div>
          </div>
          <div class="col-xl-4 col-lg-6">
            <div
              class="copyright-text text-lg-end pt-40 pb-35 rpt-10 wow fadeInLeft delay-0-2s"
            >
              <p>
                Copyright @{{ new Date().getFullYear() }},
                <NuxtLink href="/">Nexus Acumen</NuxtLink> All Rights Reserved
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer1",
};
</script>
