<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
<section>

     <div class="info text-center text-white">

        <h2 class="text-uppercase">

          Change a life today

        </h2>

        <div class="line my-4">

        </div>

        <p class="p-4">

            As long as poverty, injustice & inequality persist, none of us can truly rest. It doesn’t take much to change a life, Get in touch today and start making the difference.

        </p>

        <div>

          <span class="text-uppercase my-btn">

            <a href="#">

              Volunteer

            </a>
            
          </span>

          <span class="text-uppercase my-btn">

            <a href="#">

              Donate now

            </a>
            
          </span>
        
        </div>

        
    </div>
</section>
   
      
     
   
    
  
</template>

<style lang="scss" scoped>


section{

    width: 100%;
    padding:200px 0 400px;
    background-image: url('https://avada.website/charity/wp-content/uploads/sites/72/2016/08/home-footer.jpg');
    background-size: cover;
    background-position: bottom;
  .info{
      
    width: 60%;
    margin: 0 auto;
    padding-top: 100px;

    h2{

        font-size: 40px;
    }

    .line{

        background-color: $my-yellow;
        width: 200px;
        height: 2px;
        margin-left: calc(50% - 100px);
    }  

    p{

        font-size: 25px;
    }
    .my-btn{

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
      
    }
  }

</style>
