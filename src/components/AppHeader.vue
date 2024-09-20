<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>

  <div class="bg-header">

  </div>
  <header>
    <div class="header-top d-flex justify-content-between align-items-center p-5">

      
      <div class="logo-header d-flex align-items-center">
        <img class="logo-small"  src="../pubblic/img/Logo-small.png" alt="Avada Chiarity">
      
        <h3 class="text-uppercase text-white ps-2">Avada Charity</h3>
      </div>

        
      <div class="list-page d-flex align-items-center">
        <ul class="d-flex flex-wrap align-items-center">
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

        <div class="d-flex flex-wrap justify-content-center">

          <span class="text-uppercase my-btn-mission me-2">

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
      
     
    </div>
    
  </header>
</template>

<style lang="scss" scoped>
.bg-header{
  position: fixed;
  z-index: -1;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-image: url('../pubblic/img/HelloIMG1669149393797.jpeg');
  background-size: cover; 
  
}

header{

  width: 100%;
  padding-bottom:200px ;

  .header-top{
      
    
    
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
  }
  

  .header-bottom{

    position: relative;
    .info{
      
      width: 60%;
      margin: 0 auto;
      padding-top: 100px;

      h1{

        font-size: 50px;
      }

      p{

        font-size: 25px;
      }
      .my-btn-mission{

        a{
          color: white;
          text-decoration: none;
          padding: 10px 20px;
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

            background-color: $my-dark-blue;
            color: white;
            border-color: white;
          }
        }

      }
      
    }
  }
}

@media only screen and (max-width:1100px){

  .header-top{

    .logo-header{
      h3{
        display: none;
      }
    }

  }
  
  

}

@media only screen and (max-width:796px){

  .logo-small{

    display: none;
  }

    
  
}


</style>
