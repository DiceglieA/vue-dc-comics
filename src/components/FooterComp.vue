<template>
  <footer>
    <div class="bg">
      <div class="container">
        <div class="lists">
          <div>
            <ul>
                <h4>DC COMICS</h4>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <ul>
                <h4>SHOP</h4>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
          </div>
          <div>
            <ul>
                <h4>DC</h4>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshop</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
          </div>
          <div>
            <ul>
                <h4>SITES</h4>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
          </div>
        </div>

        <div class="dc-logo">
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
      </div>

    </div>
    <div class="bg-grey">
      <h3 class="signUp">SIGN-UP NOW!</h3>
      <div class="followUs">
          <h3>FOLLOW US</h3>
          <div>
              <img src="../assets/img/footer-facebook.png" alt="Facebook">
              <img src="../assets/img/footer-twitter.png" alt="Twitter">
              <img src="../assets/img/footer-youtube.png" alt="YouTube">
              <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
              <img src="../assets/img/footer-periscope.png" alt="Periscope">
          </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComp',
};
</script>

<style lang="scss" scoped>
.bg{
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-color: black;
    height: 400px;
}

ul{
    text-align: start;
    margin: 10px;
}

h4 {
  color: white;
}

li{
    font-size: 12px;
    color: gray;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  overflow: hidden;
  height: 400px;
}

.lists{
    display: flex;
}

.bg-grey{
    background-color: #2D2C2D ;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.followUs{
    display: flex;
    align-items: center;
}
img{
    padding: 15px
}

h3{
    color: #3B7CFF;
}

.signUp{
    color: white;
    padding: 7px;
    border: 2px solid #3B7CFF;
}
</style>
