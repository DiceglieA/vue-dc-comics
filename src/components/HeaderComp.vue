<template>
  <header>
    <nav class="container">
      <div>
        <img src="../assets/img/dc-logo.png" alt="logo">
      </div>
      <ul>
        <li
          v-for="eleMenu in arrMenu"
          :key="eleMenu.text"
        >
          <a :href="eleMenu.url">{{ eleMenu.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
  data() {
    return {
      arrMenu: [
        {
          url: '#CHARACTERS',
          text: 'CHARACTERS',
        },
        {
          url: '#COMICS',
          text: 'COMICS',
        },
        {
          url: '#MOVIES',
          text: 'MOVIES',
        },
        {
          url: '#TV',
          text: 'TV',
        },
        {
          url: '#GAMES',
          text: 'GAMES',
        },
        {
          url: '#COLLECTIBLES',
          text: 'COLLECTIBLES',
        },
        {
          url: '#VIDEOS',
          text: 'VIDEOS',
        },
        {
          url: '#FANS',
          text: 'FANS',
        },
        {
          url: '#NEWS',
          text: 'NEWS',
        },
        {
          url: '#SHOP',
          text: 'SHOP',
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
 nav {
  display: flex;
  justify-content: space-between;
 }

 ul {
  display: flex;
  align-items: center;
 }

 li {
  margin: 0 8px;
  font-size: 10px;
 }

 a {
   color: black;
 }
</style>
