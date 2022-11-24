<template>
  <header>
    <nav>
      <div>
        <img src="../assets/img/dc-logo.png" alt="logo">
      </div>
      <ul>
        <li>
          <a href="#!">CHARACTERS</a>
        </li>
        <li>
          <a href="#!">COMICS</a>
        </li>
        <li>
          <a href="#!">MOVIES</a>
        </li>
        <li>
          <a href="#!">TV</a>
        </li>
        <li>
          <a href="#!">GAMES</a>
        </li>
        <li>
          <a href="#!">COLLECTIBLES</a>
        </li>
        <li>
          <a href="#!">SHOP</a>
        </li>
        <li>
          <a href="#!">VIDEOS</a>
        </li>
        <li>
          <a href="#!">FANS</a>
        </li>
        <li>
          <a href="#!">NEWS</a>
        </li>
        <li>
          <a href="#!">SHOP</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
};
</script>

<style lang="scss" scoped>
 nav {
  display: flex;
  justify-content: space-around;
 }

 ul {
  display: flex;
  align-items: center;
 }

 li {
  margin: 0 10px;
 }

 a {
   color: black;
 }
</style>
