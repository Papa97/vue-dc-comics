<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="" />
      </div>
      <nav>
        <ul>
          <li>Characters</li>
          <li class="active">Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Collectibles</li>
          <li>Videos</li>
          <li>Fans</li>
          <li>News</li>
          <li>Shop</li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
.container {
  display: flex;
  justify-content: space-between;
}

.logo {
  width: 40%;
}

nav {
  width: 60%;
}

ul {
  list-style: none;
  display: flex;
  justify-content: space-between;

  li {
    text-transform: uppercase;
    line-height: 100px;
  }
}

.active {
  color: #0c7cec;
  border-bottom: 7px solid #0c7cec;
}
</style>