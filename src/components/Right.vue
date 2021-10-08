<template>
  <div class="right">
      <div class="top">
          <img src="@/assets/profile.jpg" alt="Profile" class="profile-pic">
          <div class="user">
              <div class="profile">michelepapagni</div>
              <div class="name lightgrey">Michele Papagni</div>
          </div>
          <a href="#" class="change blue">Passa a</a>
      </div>
      <div class="bottom">
          <div class="up">
              <span class="lightgrey">Suggerimenti per te</span>
              <span>Mostra tutti</span>
          </div>
          <div class="list">
              <div class="new">
                  <div class="new-profile">
                    <img src="@/assets/profile.jpg" alt="Profile" class="small-profile-pic mr-10">
                    <span class="name">Tess</span>  
                  </div>
                  <div class="add blue">Segui</div>
              </div>
              <div class="new">
                  <div class="new-profile">
                    <img src="@/assets/profile.jpg" alt="Profile" class="small-profile-pic mr-10">
                    <span class="name">Tess</span>  
                  </div>
                  <div class="add blue">Segui</div>
              </div>
              <div class="new">
                  <div class="new-profile">
                    <img src="@/assets/profile.jpg" alt="Profile" class="small-profile-pic mr-10">
                    <span class="name">Tess</span>  
                  </div>
                  <div class="add blue">Segui</div>
              </div>
              <div class="new">
                  <div class="new-profile">
                    <img src="@/assets/profile.jpg" alt="Profile" class="small-profile-pic mr-10">
                    <span class="name">Tess</span>  
                  </div>
                  <div class="add blue">Segui</div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

@import '../styles/utilities.scss';

.right{
    width: 38%;
    height:100%;
    .top{
        margin: 20px 0;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    .bottom{
        padding: 20px;
        .up{
            display: flex;
            justify-content: space-between;
        }
        .list{
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 10px 0;
            .new{
                display: flex;
                justify-content: space-between;
                align-items: center;
                width: 100%;
                margin: 10px 0;
                .new-profile{
                    display: flex;
                    align-items: center;
                }
            }
        }
    }
}


</style>