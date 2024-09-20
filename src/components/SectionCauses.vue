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
    <div class="causes-container">

        <div class="text-center">
            <h2 class="text-uppercase">
                Recent Causes
            </h2> 
            
            <div class="line my-5">

            </div> 

            
            <span>
                We run projects in over 30 countries in 5 contintents
            </span>
            
        </div>

        <div class="my-row row">
            <div class="my-card card col-sm-6 col-md-4 col-lg-3">
                <div class="my-img-card">
                    <img src="../pubblic/img/HelloIMG1669149317319.jpeg"  alt="...">    
                </div>

                

            

            <div class="my-card card-hover card col-sm-6 col-md-4 col-lg-3 text-uppercase ">

                <h4 class="text-center text-white text-uppercase">

                    Fair trade

                </h4>

            </div>
            
            
            </div>
            <div class="my-card card col-sm-6 col-md-4 col-lg-3">
                <img src="../pubblic/img/HelloIMG1669149318263.jpeg" alt="...">

                <div class="my-card card-hover card col-sm-6 col-md-4 col-lg-3 text-uppercase ">

                    <h4 class="text-center text-white text-uppercase">

                        Shelter

                    </h4>

                </div>
            
            </div>
            <div class="my-card card col-sm-6 col-md-4 col-lg-3">
                <img src="../pubblic/img/HelloIMG1669149319450.jpeg" alt="...">

                <div class="my-card card-hover card col-sm-6 col-md-4 col-lg-3 text-uppercase ">

                    <h4 class="text-center text-white text-uppercase">

                        Farming

                    </h4>

                </div>
                                
            </div>
            <div class="my-card card col-sm-6 col-md-4 col-lg-3">
                <img src="../pubblic/img/HelloIMG1669149321401.jpeg" alt="...">

                <div class="my-card card-hover card col-sm-6 col-md-4 col-lg-3 text-uppercase ">

                    <h4 class="text-center text-white text-uppercase">

                        Vaccines

                    </h4>

                </div>
            
            </div>
        </div>

    </div>

    <div class="bottom-section p-5">
        <h4 class="text-center p-2">
            <a href="#" class="text-uppercase">
                View all our causes
            </a>
        </h4>
    </div>
  </section>
</template>

<style lang="scss" scoped>

section{
    position: relative;
    width: 100%;
    background-color: white;

    .causes-container{

        width: 80%;
        margin: 0 auto;
        padding-top: 100px;
        

        div{

            h2{

                font-size:50px;
            }

            .line{

                background-color: $my-yellow;
                width: 200px;
                height: 2px;
                margin-left:calc(50% - 100px);
            }

            span{
                font-size: 25px;
            }
        }
        .my-row{

            padding: 100px 0 200px;

            .my-card{
                
                background:none;
                border: none;
                margin-bottom: 10px;
                img{
                    border-radius: 5px;
                    width: 100%;
                    height: 100%;
                    display: block;
                    
                }
                

                .card-hover{

                    display: none;
                    position: absolute;
                    top: 0;
                    left: 3%;
                    width: 94%;
                    height: 100%;

                    h4{
                        margin-top:calc(50% - 50px);
                        line-height: 20px;
                        
                    }
                    
                    
                }
                
                &:hover .card-hover{

                    display: block;
                    align-items: center;
                    background-color: rgba($color: $my-yellow, $alpha: 0.7);
                }

            }
            }
        }

    }

    

    .bottom-section{
        position: absolute;
        bottom: 0;
        left: 0;
        background-color: #ED6967;
        width: 100%;

        &:hover{

            background-color: #408292;
        }

        h4{
            width: 100%;
            a{
                width: 100%;
                color: white;
                text-decoration: none;

            }
        }

    }


  
  

</style>
