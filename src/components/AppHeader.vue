<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
  <header>
    <div class="header-top d-flex justify-content-between align-items-center p-5">
      <div class="logo-header d-flex align-items-center">
        <img src="../pubblic/img/HelloIMG1669149314369.png" alt="Avada Chiarity">
      </div>
      <div class="list-page d-flex align-items-center">
        <ul class="d-flex align-items-center">
          <li class="text-uppercase">

            <a href="#">
              Home
            </a>

          </li>
          <li class="text-uppercase">

            <a href="#">
              Mission
            </a>

          </li>
          <li class="text-uppercase">

            <a href="#">
              Causes
            </a>

          </li>
          <li class="text-uppercase">

            <a href="#">
              Journal
            </a>

          </li>

          <li class="my-btn text-uppercase">
            
            <a class="button" href="#">

              Donate

            </a>

          </li>
        </ul>
      </div>
    </div>
    <div class="header-bottom text-white">
      <div class="info text-center">

        <h1 class="text-uppercase">

          Make a Difference

        </h1>

        <p class="p-4">

          As long as poverty, injustice & inequality persist, none of us can truly rest

        </p>

        <div>

          <span class="text-uppercase my-btn-mission">

            <a href="#">

              Our Mission

            </a>
            
          </span>

          <span class="text-uppercase my-btn-donate">

            <a href="#">

              Donate now

            </a>
            
          </span>
        
        </div>

        
      </div>
      
      <div class="d-flex flex-column button-right">
        <button class="p-2 text-secondary border-0 rounded-2 mb-2">

          <i class="fa-solid fa-folder"></i>

          <div>
            Prebuilts
          </div>

        </button>

        <button class="p-2 text-secondary border-0 rounded-2">

          <i class="fa-solid fa-cart-shopping"></i>

          <div>
            Buy Now
          </div>
        </button>
      </div>
    </div>
    
  </header>
</template>

<style lang="scss" scoped>

header{

  background-image: url('../pubblic/img/HelloIMG1669149393797.jpeg');
  width: 100%;
  height: 100vh;
  background-size: cover;

  .list-page{

    ul{
      list-style: none;
      margin-bottom: 0;
      li{
        padding:10px 30px;

        a{
          color: white;
          text-decoration: none;
          font-weight: bold;

          &:hover{

            color: $my-yellow;

            &.button{
              color: white;

            }
          }
        }
      }
    }
    .my-btn{
      background-color: $my-yellow;
    }
  }

  .header-bottom{

    position: relative;
    .info{
      
      width: 60%;
      margin: 0 auto;
      padding-top: 100px;

      h1{

        font-size: 100px;
      }

      p{

        font-size: 25px;
      }
      .my-btn-mission{

        a{
          color: white;
          text-decoration: none;
          padding: 10px 20px;
          margin-right: 20px;
          border: 1px solid white;
          &:hover{

            color: $my-yellow;
            border-color: $my-yellow;
          }
        }
        

      }
      .my-btn-donate{

        
        a{
          color: $my-yellow;
          text-decoration: none;
          padding: 10px 20px;
          border: 1px solid $my-yellow;
          &:hover{

            background-color: #262E44;
            color: white;
            border-color: white;
          }
        }

      }
      
    }.button-right{
        position: absolute;
        top: 0;
        right:20px;
        
      }
  }
}
</style>
