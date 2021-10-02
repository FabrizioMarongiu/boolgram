<template>
  <header>
      <img src="@/assets/logo.png" alt="Logo Boolgram">
      <input type="text" placeholder="CERCA">
      <div class="keys">
          <i class="fas fa-home">HOME</i>
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
header{
    display:flex;
    width:100vh;
    justify-content:space-around;
    align-items:center;
    i{
        font-size: 20px;
        color: green;
    }

}
</style>