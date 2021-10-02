<template>
  <div class="left">
    <div class="top">
        <div class="story">
            
                <img src="@/assets/profile.jpg" alt="Profile image">
                <span>Gino</span>
            
        </div>
        <div class="story">
            
                <img src="@/assets/profile.jpg" alt="Profile image">
                <span>Gino</span>
            
        </div>
        <div class="story">
            
                <img src="@/assets/profile.jpg" alt="Profile image">
                <span>Gino</span>
            
        </div>
        <div class="story">
            
                <img src="@/assets/profile.jpg" alt="Profile image">
                <span>Gino</span>
            
        </div>
        <div class="story">
            
                <img src="@/assets/profile.jpg" alt="Profile image">
                <span>Gino</span>
            
        </div>
        <div class="story">
            
                <img src="@/assets/profile.jpg" alt="Profile pics">
                <span>Gino</span>
            
        </div>


    </div>

    <div class="bottom">
        <div class="post">
            <div class="up">
                <div class="left-side">
                   <img src="@/assets/profile.jpg" alt="Profile pics">
                    <span>Pina</span> 
                </div>
                <a href="#" class="right-side">
                  <i class="fas fa-ellipsis-h"></i>  
                </a> 
            </div>
            <img src="@/assets/landscape.png" alt="Post pic" class="post-img">
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.left{
    width: 60%;
    height:100%;
    
    .top{
        width: 100%;
        height: auto;
        border: 1px solid lightgray;
        margin: 20px 0;
        display: flex;
        justify-content: space-around;
        padding: 10px 0;
        .story {
            flex-basis:  calc(100% / 6 - 30px);
            display: flex;
            flex-direction: column;
            align-items: center;
            img{
                width: 100%;
                max-width: 70px;
                height: auto;
                display: flex;
                flex-direction: column;
                border-radius: 50%;
                border: 2px solid pink;
                }
        }
    }

    .bottom{
        width: 100%;
        height: auto;
        margin: 10px 0 0 0;
        .post{
            width: 100%;
            display: flex;
            border: 1px solid lightgray;
            margin: 10px 0;
            flex-direction: column;
            .up{
                
                display: flex;
                align-items: center;
                justify-content: space-between;
                padding:10px;
                .left-side{
                    display: flex;
                    align-items: center;
                    
                    img{
                        width: 50px;
                        margin-right: 5px;
                        border-radius: 50%;
                        border: 2px solid pink;
                        } 
                }
                
                
            }
            
        }
        
        
    }
    .post-img{
        width: 100%;
    }
}

</style>