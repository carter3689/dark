<template>
    <!-- Blog Style Two start -->
    <section class="blog-area-two pt-125 rpt-100 pb-70 rpb-40">
      <div class="container container-1290">
        <div class="row justify-content-center">
          <div class="col-xl-8 col-lg-10">
            <div
              class="section-title text-center mb-60 wow fadeInUp delay-0-2s"
            >
              <span class="sub-title mb-20">Blog & News</span>
              <h2>Read Our Latest News & Blog Get Every Updates</h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-xl-4 col-md-6">
            <div class="blog-item wow fadeInUp delay-0-2s">
              <div class="image">
                <img src="/assets/images/blog/blog1.jpg" alt="Blog" />
              </div>
              <ul class="blog-meta">
                <li>
                  <i class="far fa-calendar-alt"></i>
                  <a href="#">February 18, 2023</a>
                </li>
                <li>
                  <i class="far fa-comments"></i>
                  <a href="#">Comment (5)</a>
                </li>
              </ul>
              <hr />
              <h4>
                <NuxtLink href="blog-details"
                  >Voice Skills For Google Assistant And Amazon Alexa</NuxtLink
                >
              </h4>
              <NuxtLink class="read-more" href="blog-details"
                >Read More <i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
          </div>
          <div class="col-xl-4 col-md-6">
            <div class="blog-item wow fadeInUp delay-0-4s">
              <div class="image">
                <img src="/assets/images/blog/blog2.jpg" alt="Blog" />
              </div>
              <ul class="blog-meta">
                <li>
                  <i class="far fa-calendar-alt"></i>
                  <a href="#">February 18, 2023</a>
                </li>
                <li>
                  <i class="far fa-comments"></i>
                  <a href="#">Comment (5)</a>
                </li>
              </ul>
              <hr />
              <h4>
                <NuxtLink href="blog-details"
                  >Inclusive Design And Accessibility Stream Heydon
                  Pickering</NuxtLink
                >
              </h4>
              <NuxtLink class="read-more" href="blog-details"
                >Read More <i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
          </div>
          <div class="col-xl-4 col-md-6">
            <div class="blog-item wow fadeInUp delay-0-6s">
              <div class="image">
                <img src="/assets/images/blog/blog3.jpg" alt="Blog" />
              </div>
              <ul class="blog-meta">
                <li>
                  <i class="far fa-calendar-alt"></i>
                  <a href="#">February 18, 2023</a>
                </li>
                <li>
                  <i class="far fa-comments"></i>
                  <a href="#">Comment (5)</a>
                </li>
              </ul>
              <hr />
              <h4>
                <NuxtLink href="blog-details"
                  >Creating Online Environments The Work Well For Older
                  Users</NuxtLink
                >
              </h4>
              <NuxtLink class="read-more" href="blog-details"
                >Read More <i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Blog Style Two end -->
</template>

<script>
export default {
  name: "AppBlogArea",
};
</script>