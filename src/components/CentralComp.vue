<template>
  <main>
    <div class="dynamic-main">
      <div class="container">
        Content goes here
      </div>
    </div>
    <div class="blue-cards">
      <ul class="loghi container">
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <span>DIGITAL COMICS</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <span>DC MERCHANDISE</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <span>SUBSCRIPTION</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <span>COMIC SHOP LOCATOR</span>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <span>DC POWER VISA</span>
        </li>
      </ul>
    </div>
  </main>
</template>

<script>
export default {
  name: 'CentralComp',
};
</script>

<style lang="scss" scoped>
.dynamic-main {
  color: white;
  background-color: #1b1c1d;
  padding: 1.8rem;
  font-size: 30px;
}

.blue-cards {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #2F79F7;
}

.loghi {
    color: white;
    padding: 20px;
    font-size: 10px;
    img{
        width: 40px;
        vertical-align: middle;
        padding: 10px;
    }
}

li {
  display: inline-block;
  margin: 0 10px;
  align-items: center;
}
</style>
