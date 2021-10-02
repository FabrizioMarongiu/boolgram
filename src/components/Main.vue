<template>
  <main>
      <div class="container main-content">
        <Left/>
        <Right/>
      </div>
      
      
  </main>
</template>

<script>
import Left from '../components/Left.vue'
import Right from '../components/Right.vue'

export default {
  name: 'Main',
  components: {
    Left,
    Right
  }
}
</script>

<style scoped lang="scss">
@import '../styles/utilities.scss';


main{
    .main-content{
        display: flex;
        justify-content: space-between;
    }
}

</style>