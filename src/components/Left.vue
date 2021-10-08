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
                   <img src="@/assets/profile.jpg" alt="Profile pics" class="small-profile-pic">
                    <span>Pina</span> 
                </div>
                <a href="#" class="right-side">
                  <i class="fas fa-ellipsis-h"></i>  
                </a> 
            </div>
            <img src="@/assets/landscape.png" alt="Post pic" class="post-img">
            <div class="down">
                <div class="interactions">
                    <div class="icons">
                        <span><i class="far fa-heart"></i></span>
                        <span><i class="far fa-comment"></i></span>
                    </div>
                    <div class="likes">
                        <img src="@/assets/profile.jpg" alt="Profile pic" class="post-profile-pic mr-10">
                        <span class="lightgrey">Piace a TIZIO e altre PERSONE</span>
                    </div>
                    <div class="post-text">
                        <p>
                            <span class="mr-10">stark.jace</span>
                            <span class="grey">Queen of Hearts.</span>
                            
                        </p>
                    </div>
                    <div class="comments">
                        <span class="lightgrey">Mostra tutti e 4 i commenti</span>
                        <div>krajcik.leonard <span class="grey">I get</span> </div>
                        <div>Sabina<span class="grey"> Bellissimo!!</span></div>
                        <div>Lorenza<span class="grey"> a me non piace</span></div>
                        <div class="times">
                            <span class="lightgrey">33 Ore fa</span>
                        </div>
                        
                    </div>
                    
                </div>
                
            </div>
            
        </div>
        <div class="add-text">
            <input type="text" placeholder="Aggiungi un commento">
            <div class="public">Pubblica</div>
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
                max-width: 60px;
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
            border-bottom: none;
            margin: 10px 0 0 0;
            flex-direction: column;
            .up{
                
                display: flex;
                align-items: center;
                justify-content: space-between;
                padding:10px;
                .left-side{
                    display: flex;
                    align-items: center;
                    
                }
                
            }
            .post-img{
                width: 100%;
                object-fit: cover;
            }
            .interactions{
                padding: 10px;
                .icons{
                    span{
                        margin-right: 10px;
                        font-size: 25px;
                        color: rgb(24, 23, 23);
                    }
                }
                .likes{
                    margin:10px 0;
                    display: flex;
                    align-items: center;
                }
                .times{
                    margin: 10px 0;
                }
                
            }
            
        }
        .add-text{
            position:relative;
            width: 100%;
            height: 35px;
            input{
                width: 100%;
                height:35px;
                border: 1px solid lightgray;
                padding: 5px;
            }
            .public {
                position: absolute;
                right:10px;
                top:10px;
                color: dodgerblue;
            }
        }
        
        
    }
    
    
}

</style>