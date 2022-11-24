<template>
  <div>
    <HeaderComp />
    <CentralComp />
    <FooterComp />
  </div>
</template>

<script>
import HeaderComp from '@/components/HeaderComp.vue';
import CentralComp from '@/components/CentralComp.vue';
import FooterComp from '@/components/FooterComp.vue';

export default {
  name: 'App',
  components: {
    HeaderComp,
    CentralComp,
    FooterComp,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  width: 70%;
  margin: auto;
}

ul {
  list-style-type: none;
}

a {
  text-decoration: none;
}
</style>
