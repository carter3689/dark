<template>
  <div class="row justify-content-between">
    <div class="col-xl-2 col-lg-3 col-6">
      <div class="counter-item counter-text-wrap wow fadeInUp delay-0-2s">
        <i class="fal fa-check-circle"></i>
        <span class="count-text" data-speed="3000" data-stop="94">94</span>
        <span class="counter-title">Percent of First Impressions via the web are design-related</span>
      </div>
    </div>
    <div class="col-xl-2 col-lg-3 col-6">
      <div class="counter-item counter-text-wrap wow fadeInUp delay-0-3s">
        <i class="fal fa-check-circle"></i>
        <span class="count-text" data-speed="3000" data-stop="89">89</span>
        <span class="counter-title">Percent of consumers switch to a competitor's if the User Experience is bad.</span>
      </div>
    </div>
    <div class="col-xl-2 col-lg-3 col-6">
      <div class="counter-item counter-text-wrap wow fadeInUp delay-0-4s">
        <i class="fal fa-check-circle"></i>
        <span class="count-text" data-speed="3000" data-stop="50">50</span>
        <span class="counter-title">that's how long it takes for users to form an opinion about your website (Oh and BTW. Yes -- that's Milliseconds)</span>
      </div>
    </div>
    <div class="col-xl-2 col-lg-3 col-6">
      <div class="counter-item counter-text-wrap wow fadeInUp delay-0-5s">
        <i class="fal fa-check-circle"></i>
        <span class="count-text" data-speed="3000" data-stop="75">75</span>
        <span class="counter-title">percent of users judge your company's credibility based on your company's website design</span>
      </div>
    </div>
  </div>
</template>

<script>
import { nexusAcumentUtils } from "~/utilits";
export default {
  name: "Counter",
  mounted() {
    nexusAcumentUtils.counterUp();
  },
};
</script>
