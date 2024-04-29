<template>
    <!-- Team Area start -->
    <section class="team-area pt-70 rpt-40">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-9">
            <div
              class="section-title text-center mb-50 wow fadeInUp delay-0-2s"
            >
              <span class="sub-title mb-20">Team</span>
              <h2>Meet The Founder</h2>
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div
          class="row row-cols-xl-5 row-cols-lg-4 row-cols-md-3 row-cols-sm-2 row-cols-1 justify-content-center"
        >
          <div class="col">
            <div class="team-member wow fadeInUp delay-0-2s">
              <div class="image">
                <img src="/assets/images/team/member1.jpg" alt="Team Member" />
              </div>
              <div class="content">
                <h4>Patrick V. Schroeder</h4>
                <span>UI/UX Designer</span>
                <NuxtLink class="read-more" href="team-details"
                  ><i class="far fa-arrow-right"></i
                ></NuxtLink>
              </div>
              <div class="btn-social">
                <NuxtLink class="read-more" href="team-details"
                  ><span>View Details</span> <i class="far fa-arrow-right"></i
                ></NuxtLink>
                <div class="social-style-two">
                  <a href="#"><i class="fab fa-facebook-f"></i></a>
                  <a href="#"><i class="fab fa-twitter"></i></a>
                  <a href="#"><i class="fab fa-instagram"></i></a>
                  <a href="#"><i class="fab fa-linkedin-in"></i></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Team Area end -->
</template>

<script>
import { nexusAcumentUtils } from "~/utilits";
export default {
  name: "AppSingleTeam"
}
</script>