<template>
  <NuxtLayout name="ygency" :header="1" :footer="1">
    <!-- Hero Section Start -->
    <section class="hero-area pt-185 rpt-150 rel z-1">
      <div class="container">
        <div class="row">
          <div class="col-lg-8">
            <div class="hero-content wow fadeInLeft delay-0-2s">
              <h1>Tell <span>Your Brand</span> <i>Story</i></h1>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="hero-right-image mt-20 wow fadeInUp delay-0-4s">
              <img src="/assets/images/hero/hero-right.png" alt="Hero" />
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="hero-bottom-image">
          <img src="/assets/images/hero/Women-brand-fashion.png" alt="Hero" />
          <div class="hero-social">
            <a href="#"
              ><i class="fab fa-facebook-f"></i> <span>Facebook</span></a
            >
            <a href="#"
              ><i class="fab fa-linkedin"></i> <span>LinkedIn</span></a
            >
          </div>
        </div>
      </div>
      <div class="hero-bg">
        <img src="/assets/images/hero/hero-bg.png" alt="lines" />
      </div>
    </section>
    <!-- Hero Section End -->

    <!-- About Us Area start -->
    <section class="about-area pt-130 rpt-100 rel z-1">
      <div class="container">
        <div class="row justify-content-between">
          <div class="col-xl-5 col-lg-3">
            <div class="about-image rmb-45 wow fadeInUp delay-0-2s">
              <img
                src="/assets/images/about/circle-text.svg"
                alt="Circle Text"
              />
            </div>
          </div>
          <div class="col-xl-7 col-lg-9">
            <div class="about-content wow fadeInUp delay-0-4s">
              <div class="section-title mb-40">
                <span class="sub-title mb-15">Our Mission</span>
                <h2>(Should you choose to accept us...) is to help YOU bring your brand's story to life. Digitally</h2>
              </div>
              <div class="content">
                <p>
                  We marry artistry with analytics to drive tangible growth for your business. 
                  Our data-informed approach ensures your brand's story is brought to life with both captivating visuals and proven marketing strategies. 
                  We track key metrics to measure success, 
                  making sure your digital presence is not only beautiful but drives the leads, engagement, and community growth you desire.
                </p>
                <NuxtLink class="read-more mt-10" href="pricing"
                  >I Accept - Let's Get Started! <i class="far fa-arrow-right"></i
                ></NuxtLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- About Us Area end -->

    <!-- Headline area start -->
    <div class="headline-area pt-90 rpt-85 rel z-1">
      <div class="container-fluid">
        <div class="headline-text marquee">
          <span>Tell<span>Your</span> Story</span>
        </div>
      </div>
    </div>
    <!-- Headline Area end -->

    <!-- What We Do start -->
    <section class="what-we-do-area pt-90 rpt-80 rel z-1">
      <div class="container">
        <div class="row justify-content-between">
          <div class="col-xl-5 col-lg-8">
            <div class="what-we-do-content mb-55">
              <div class="section-title mb-60 wow fadeInUp delay-0-2s">
                <span class="sub-title mb-15">What We Do</span>
                <h2>Data Driven Story-telling. To help you FIND and KEEP your ideal customer.</h2>
              </div>
              <div class="what-we-do-item wow fadeInUp delay-0-3s">
                <div class="number">
                  <span>01</span>
                </div>
                <div class="content">
                  <h5>Mobile-First Solutions</h5>
                  <p>
                    Your Customers are moving as fast as the digital age. To engage them correctly, you 
                    (and your brand) MUST speak their language, with visuals and messaging that resonate.
                  </p>
                  <NuxtLink class="read-more style-two" href="pricing"
                    ><span>Read More</span> <i class="far fa-arrow-right"></i
                  ></NuxtLink>
                </div>
              </div>
              <div class="what-we-do-item wow fadeInUp delay-0-5s">
                <div class="number">
                  <span>02</span>
                </div>
                <div class="content">
                  <h5>Data-Driven Story-telling</h5>
                  <p>
                    Everyone loves a great story! But the best stories aren't about us. They're about the hero – the one who conquers challenges and emerges transformed. That's the power of the "hero's journey" for your brand.  
                    By putting your customers at the heart of your digital narrative, you give them a role to play, an adventure to embark on. <br><br>
                    This isn't about self-promotion; it's about empowering your customers to see themselves as heroes, with your brand as their trusted ally.  
                    Let's make your digital presence their epic adventure!
                  </p>
                  <NuxtLink class="read-more style-two" href="pricing"
                    ><span>Read More</span> <i class="far fa-arrow-right"></i
                  ></NuxtLink>
                </div>
              </div>
              <div class="what-we-do-item wow fadeInUp delay-0-7s">
                <div class="number">
                  <span>03</span>
                </div>
                <div class="content">
                  <h5>Custome Solutions</h5>
                  <p>
                    We denounce with righteous indignation and dislike beguiled
                    demoralized charms
                  </p>
                  <NuxtLink class="read-more style-two" href="service-details"
                    ><span>Read More</span> <i class="far fa-arrow-right"></i
                  ></NuxtLink>
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-6">
            <div class="what-we-do-image mb-55 wow fadeInRight delay-0-2s">
              <img
                src="/assets/images/services/what-we-do.jpg"
                alt="What We Do"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- What We Do end -->

    <!-- Statistics Area start -->
    <div class="statistics-area pt-75 rpt-45 rel z-1">
      <div class="container">
        <CountersCounter />
      </div>
    </div>
    <!-- Statistics Area end -->

    <!-- Headline area start -->
    <div class="headline-area pt-65 rpt-60 rel z-1">
      <div class="container-fluid">
        <div class="headline-text marquee">
          <span><span>Grow</span>Faster.</span>
        </div>
      </div>
    </div>
    <!-- Headline Area end -->

    <TeamAppSingleTeam/>
  </NuxtLayout>
</template>

<script>
import { nexusAcumentUtils } from "~/utilits";

export default {
  name: "index",
  mounted() {
    nexusAcumentUtils.counterUp();
  },
};
</script>
