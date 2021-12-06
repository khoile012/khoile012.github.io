<template>
  <div>
    <section class="section pt-0">
      <!-- intro -->
      <Intro />
    </section>
    <!-- categories -->
    <Categories />
    <!-- contact -->
    <Contact />
  </div>
</template>
<script>
import Intro from "@/components/Intro.vue";
import Categories from "@/components/Categories.vue";
import Contact from "@/components/Contact.vue";

export default {
  components: {
    Intro,
    Categories,
    Contact,
  },
};
</script>
