<template>
  <ul class="navigation clearfix">
    <li><NuxtLink href="/about">About Us</NuxtLink></li>
    <li><NuxtLink href="/pricing">Pricing</NuxtLink></li>
    <li><NuxtLink href="/contact">Contact</NuxtLink></li>
  </ul>
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {
      dropdown:
        '<div class="dropdown-btn"><span class="far fa-plus"></span></div>',
    };
  },
};
</script>
