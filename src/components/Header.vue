<template>
  <header>
    <div class="container content">
      <div class="logo">
        <img src="@/assets/logo.png" alt="Logo Boolgram">
      </div>
      <div class="search">
        <input type="text" placeholder="CERCA">
      </div>
      <div class="right">
          <a href="#">
            <i class="far fa-heart"></i>
          </a>
          <a href="#">
            <i class="fas fa-home"></i>
          </a>
          <a href="#" class="profile">
              <img src="@/assets/profile.jpg" alt="Profile">
          </a>
          
      </div>
    </div>
      
  </header>
</template>

<script>
export default {

}
</script>


<style scoped lang="scss">

@import '../styles/utilities.scss';
header{
  border-bottom: 1px solid lightgray;
  .content{
      display:flex;
      
      justify-content:space-between;
      align-items:center;
      
      .logo img{
          width:150px;
          height:auto;
      }
      input{
          background-color: none;
          border: 1px solid lightgray;
          text-align: center;
      }
      .right{
          display: flex;
          justify-content: space-around;
          align-items: center;
          width: 150px;
          i{
          font-size: 20px;
          color:#000
          }
          .profile img{
              width:50px;
              height: auto;
              border-radius: 50%;
              border: 2px solid pink;
          }
      }
}
    

}
</style>