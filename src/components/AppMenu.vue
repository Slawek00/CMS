<template>
  <div class="nav-bar d-flex mb-3">
      <div class="me-auto p-2">
        <img src="../assets/menu_FILL0_wght400_GRAD0_opsz48.png" alt="">
      </div>
      <div class="p-2">
        <h2>Sławomir</h2>
      </div>
      <div class="p-2">
        <img src="../assets/297581004_2360329557442961_6136335452899520745_n.jpg" alt="">
      </div>
      <div class="p-2">
        <img src="../assets/logout_FILL0_wght400_GRAD0_opsz48.png" alt="">
      </div>
  </div>
</template>

<script>

export default {
  name: "AppMenu"
}

</script>

<style scoped>

.nav-bar{
  width: 100%;
  height: 70px;
  background-color: dodgerblue;
}

.nav-bar img:nth-child(1){
  height: 50px;
  width: 50px;
  border-radius: 100px;
}

.nav-bar img:hover{
  background-color: deepskyblue;
  border-radius: 100px;
  padding:2px;
}

</style>