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
      <div class="container">
        <div class="container-ul">
          <div>
            <ul>
              <li>Dc Comics</li>
              <li>#</li>
              <li>#</li>
            </ul>
            <ul>
              <li>ciao</li>
            </ul>
          </div>

          <div>
            <ul>
              <li>prova</li>
            </ul>
          </div>
          <div>
            <ul>
              <li>prova1</li>
            </ul>
          </div>
        </div>
        <div class="logo-grande">
          <img src="../assets/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <div class="footer-bt"></div>
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

.footer-mid {
  display: flex;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
  height: 400px;
}

.logo-grande {
  z-index: 0;
  position: absolute;
  top: -75px;
  right: 0;
}

.container-ul {
  display: flex;
  justify-content: space-around;
  width: 50%;
}
</style>