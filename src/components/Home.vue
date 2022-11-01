<template>
  <div class="home">
    <Navbar class="navbar" />

    <div class="home-wrapper">
      <p class="home-wrapper__subtitle">Передовая <span>IT</span> студия</p>
      <h3 class="home-wrapper__title">
       <span>Мы создаем</span>  легкие решения сложных задач и проблем
      </h3>
    </div>
  </div>
</template>
<script>
import Navbar from "@/components/TheNavbar.vue";

export default {
  components: {
    Navbar,
  },
  data() {
    return {};
  },
};
</script>
  