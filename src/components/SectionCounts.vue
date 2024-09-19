<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
  <section class="d-flex">

    <div class="container-left">
    
        <div class="left">
            <h2 class="text-uppercase pt-5">
                Every moment counts
            </h2>
            <div class="line my-5">

            </div>  
            <div class="pb-4">
                <p>

                    Curabitur non mi et turpis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo, ac convallis nisi nibh id velit. Aliquam mattis metus a nisi pretium.
                
                </p>

                <p>

                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ac nibh vestibulum, laoreet ipsum quis, vestibulum nisi. Curabitur non mi et turpis pharetra vulputate. Ipsum dolor sit amet, consectetur adipiscing elit. Praesent ac nibh vestibulum, laoreet ipsum quis, vestibulum nisi.
                
                </p>

                <p>

                    Curabitur non mi et turpis pharetra vulputate. Cras consequat, risus nec commodo vehicula, nisi est laoreet leo, ac convallis nisi nibh id velit. 

                </p>
            </div>

            <span class="my-btn">
                <a href="#" class="text-uppercase">
                    Our mission
                </a>
            </span>
        </div>
        

    </div>

    <div class="container-right">
        <div class="right text-center text-white">
            
            <div>

                <i class="fa-regular fa-heart"></i>
                <span>

                    2032

                </span>

                <p>
                    Volunteers worldwide
                </p>
            </div>

            <div>
                <i class="fa-solid fa-earth-asia"></i>
                <span>
                    132
                </span>
                <p>Active projects</p>
            </div>

            <div>
                <i class="fa-solid fa-dollar-sign"></i>
                <span>
                    3.8m
                </span>
                <p>
                    Donated
                </p>
            </div>
        </div>
        <div class="bg-coral">
            
        </div>
    </div>
    
  </section>
</template>

<style lang="scss" scoped>

section{
    width: 100%;
    height: 70vh;
    
    .container-left{
        background-color: white;
        width: 65%;
        
        .left{

            width: 80%;
            margin: 0 auto;

            .line{

                background-color: $my-yellow;
                width: 200px;
                height: 2px;
            }

            p{
                line-height: 2rem;
                padding: 10px 0;
                color: gray;
            }
            .my-btn{

                background-color: $my-yellow;
                padding:10px 20px ;

                &:hover{
                    background-color: $my-dark-blue;
                }
                a{
                    color: white;
                    text-decoration: none;
                    
                    
                }
            }
        }
        
    }
    .container-right{
        position: relative;
        background-image: url('https://static.vecteezy.com/ti/vettori-gratis/p1/570547-mappa-del-mondo-grigio-su-sfondo-blu-vettoriale.jpg');
        background-size: cover;
        background-position-x: center;
        width: 35%;

        .right{
            position: relative;
            z-index: 2;
            width: 70%;
            margin: 0 auto;
            padding:100px 0 80px;
            
            i,span{

                font-size: 50px;
            }

            p{
                font-size: 25px;
            }
        }

        .bg-coral{
            position: absolute;
            top:0;
            right: 0;
            width: 100%;
            height: 100%;
            background-color: #ED6967;
            opacity: 0.85;
            

        }
    }   
  }
  

</style>
