<template>
  <footer>
    <div class="footer-top">
      <div class="container">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <div>Digital Comics</div>
        </div>
        <div>
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />

          Dc Merchandise
        </div>
        <div>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />

          subscrition
        </div>
        <div>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          Comic Shop Location
        </div>
        <div>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          DC Power Visa
        </div>
      </div>
    </div>
    <div class="footer-mid">
      <div class="container container-gigantesco">
        <div id="container-ul">
          <div>
            <ul>
              <li>Dc Comics</li>
              <li>Characters</li>
              <li>Comic</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
            <ul>
              <li>Shop</li>
              <li>Shop DC</li>
              <li>Shop DC Collectbles</li>
            </ul>
          </div>

          <div>
            <ul>
              <li>Dc</li>
              <li>Term Of Use</li>
              <li>Privacy Policy(New)</li>
              <li>Ad Choises</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshops</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contact Us</li>
            </ul>
          </div>
          <div>
            <ul>
              <li>Sites</li>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
            </ul>
          </div>
        </div>
        <div class="logo-grande">
          <img src="../assets/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <div class="footer-bt">
      <div class="container">
        <div>
          <button id="sign-up">sign-up now!</button>
        </div>
        <div id="socials">
          <div>Follow Us</div>
          <div><img src="../assets/img/footer-facebook.png" alt="" /></div>
          <div><img src="../assets/img/footer-twitter.png" alt="" /></div>
          <div><img src="../assets/img/footer-youtube.png" alt="" /></div>
          <div><img src="../assets/img/footer-pinterest.png" alt="" /></div>
          <div><img src="../assets/img/footer-periscope.png" alt="" /></div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.container {
  width: 100%;
  justify-content: space-around;
  position: relative;

  ul {
    li:first-of-type {
      color: white;
      text-transform: uppercase;
      font-weight: 600;
    }
    list-style: none;
  }
}

.footer-top {
  background-color: #0c7cec;
  z-index: 99;

  display: flex;
  justify-content: space-between;
  div {
    color: white;
    text-transform: uppercase;
    font-size: 14px;
    height: 150px;
    display: flex;
    align-items: center;

    img {
      height: 60px;
    }
  }
}

.container-gigantesco {
  overflow: hidden;
}

.footer-mid {
  display: flex;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
  height: 400px;

  ul {
    color: rgb(92, 92, 92);
  }
}

.logo-grande {
  position: absolute;
  top: -75px;
  right: 0;
}

#container-ul {
  display: flex;
  justify-content: space-around;
  width: 50%;
  margin-top: 20px;
}

.footer-bt {
  background-color: rgb(58, 58, 58);
  height: 80px;

  .container {
    display: flex;
    justify-content: space-between;
  }
}

#socials {
  display: flex;
  justify-content: space-between;
  width: 50%;
  margin: 20px 0;

  div:first-child {
    color: #0c7cec;
    font-weight: 700;
    font-size: 20px;
  }
}

#sign-up {
  background-color: rgb(58, 58, 58);
  color: white;
  border: 3px solid #0c7cec;
  text-transform: uppercase;
  padding: 10px;
  margin: 20px 0;
}
</style>