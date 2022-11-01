
<template>
  <Home />
  <About />
  <Service />
  <Projects />
</template>
<script>
import Home from "@/components/Home.vue";
import About from "@/components/About.vue";
import Service from "@/components/Service.vue";
import Projects from "@/components/Projects.vue";

export default {
  components: {
    Home,
    About,
    Service,
    Projects,
  },
  data() {
    return {};
  },
};
</script>
  