<template>
  <div class="card">
    <img :src="card.thumb" alt="">
    <div>{{card.series}}</div>
  </div>
</template>

<script>
export default {
  name: 'CardComp',
  props: {
    card: Object,
  },
};
</script>

<style scoped lang="scss">
.card {
  width: calc((100% - 5rem) / 6);
}

img{
      width: 100%;
      aspect-ratio: 1/1;
      object-fit:cover;
      object-position: top;
   }</style>
