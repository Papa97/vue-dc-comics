<template>
  <main>
    <div class="jumbo"></div>
    <div class="container"></div>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss" scoped >
main {
  height: 100px;
  background-color: rgb(29, 29, 29);
  div {
    color: white;
  }
}

.jumbo {
  height: 700px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
}
</style>